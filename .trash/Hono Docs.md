**Hono** is a simple, fast web framework that unlike *express.js*, it relies in web standards and works on any JavaScript runtime such as: **Deno, Bun, Node.js, Cloudflare, Vercel ...etc**

## What are use-cases of Hono

Hono is a simple framework similar to Express, it runs on CDN edges. When combined with middlewares, it allows you to construct larger applications. Using Hono you can build a variety of things such as:
- Web APIs
- Fullstack Applications
- Proxy of a backend server [[Reverse Proxy]]
- Front of a CDN

## Hono has multiple routers

Hono comes with multiple routes to be used with **RegExpRouter** being the fastest.

- **RegExpRouter:** although it has *RegExp* in its name, it's not like Express' route matching that uses linear matching. What this router does is it transforms all routes into one big RegEx which gets the result with a single match.
- **TrieRouter:** this router uses the trie-tree algorithm, its not as fast as *RegExpRouter* but it is much faster than Express' router. This router does support all route matching unlike *RegExpRouter*.
- **Smart Router:** since *RegExpRouter* has some drawbacks like not supporting all route matching, this rouuter tries to find the best router when the application starts and continue using it.
- **LinearRouter:** This router comes handy in environment where route gets registered on each request, in situations like this it is more faster than *RegExpRouter* it uses linear approach without compiling the strings.
- **PatternRouter:** This is the smallest router in hono, even though hono is small it is good where resources are limited.

## Hello World in Hono

Creating a Hello World example in hono is so simple, you just import it, create app instance and return it as default export. 

First, you create the application using the following command:

```sh
npm create hono@latest my-app
```

Then inside of `my-app/src/index.ts` you create the app.

```javascript
import { Hono } from 'hono'

const app = new Hono()

app.get('/', (c) => {
  return c.text('Hello, World')
})

export default app
```

The `/` endpoint now returns a text `Hello, World`. We can replace `c.text` with `new Response` and it will work the same.

### Responding with JSON

To make a response with json, we use `c.json` passing it the JavaScript object needed.

```javascript
app.get('/api/hello', (c) => {
  return c.json({
    ok: true,
    message: 'Hello Hono!',
  })
})
```

### Different HTTP methods

Like Express or fastify, Hono handles all HTTP methods. POST, DELETE, PUT are also available.

```javascript
app.post('/posts', (c) => c.text('Created!', 201))
app.delete('/posts/:id', (c) =>
  c.text(`${c.req.param('id')} is deleted!`)
)
```

### Accessing path parameters 

Path parameters are accessible through `c.req.param` function and they can be defined by appending colon `:` to the route. Query parameters are accessible through `c.req.query` function too. Response headers could be created using `c.header(KEY, VALUE)` function where `KEY` is the header name and `VALUE` is the header value.

```javascript
app.get('/posts/:id', (c) => {
  const page = c.req.query('page')
  const id = c.req.param('id')
  c.header('X-Message', 'Hi!')
  return c.text(`You want to see ${page} of ${id}`)
})
```

## Middlewares

Middlewares are useful in such a framework since they'd do the hard work and provide a better DX (Developer Experience) to use a middleware simply import (or define) it and use `app.use` with the route pattern and the middleware call, like the following:

```javascript
import { basicAuth } from 'hono/basic-auth'

// ...

app.use(
  '/admin/*',
  basicAuth({
    username: 'admin',
    password: 'secret',
  })
)

app.get('/admin', (c) => {
  return c.text('You are authorized!')
})
```

## Adapters

Adapters are platform-dependent function calls, although Hono is expected to work seamlessly with all environments, sometimes having platform-dependent functionality is needed.

```javascript
import { upgradeWebSocket } from 'hono/cloudflare-workers'

app.get(
  '/ws',
  upgradeWebSocket((c) => {
    // ...
  })
)
```


## The `Hono` Object

The `Hono` Object is the main focus, it is the most used object in Hono since it has almost all the methids needed to make your app. It is the first object you'd use and until the end.

### Methods

An Hono instance has many methods to use:
- **app.HTTP_METHOD([path,]handler|middleware...)** this method is what you'd use to define endpoint. The *path* argument is a string or an array of paths usually starts with slash. The second argument passed to the function  *handler (see: [[Hono Handlers, definition]]) or a variadic parameter [[What are variadic parameters]]* of either of those. Multiple middlewares could be chained together. *HTTP_METHOD* could be any of the following: *get, post, delete, put* TODO
- **app.all([path,]handler|middleware...)** Similar to `app.HTTP_METHOD`, this function accepts a two arguments, a path string or array of paths (see: [[Hono route paths]]). Second argument is a variadic parameter (see: [[What are variadic parameters]]) of either middleware or route handler. What makes this method different is that it runs on each request while also following the path pattern.
- **app.on(method|method[], path|path[], handler|middleware...)** What this method does is it takes Http Method or an array of http method (get, post, delete, put, update), second argument is path or an array of paths and third is variadic parameter of either middlewares or handler. This method provides flexibility of assigning a handler to routes with multiple http methods without the need to call for example `.get` or `.post` methods multiple times.
- **app.use([path,]middleware)** The use method is used for assigning middlewares for specific routes. It takes path array or string and a middleware that would be ran on thise paths.