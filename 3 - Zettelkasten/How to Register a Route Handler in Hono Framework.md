---
tags:
  - type/zettel
  - concept/hono
  - concept/framework
  - concept/server
aliases: 
created: 2025-04-17 16:36:08
---
# How to Register a Route Handler in Hono Framework

The `Hono` class comes with many methods for several use cases such as: *registering routes, middlewares...etc*. There are specific methods for handling HTTP requests. but they share the same parameters types.

```typescript
app.HTTP_METHOD([path,] handle | middleware...)
```

In the code above, `HTTP_METHOD` refers to the routing function (*get, post, put, delete*). The first argument of the function is a string, like the following:

```typescript
app.get('/api/hello', getHandler)
app.post('/user/comment/:id', postHandler)
app.put('/user/comment/:id', putHandler)
app.delete('/user/:id', deleteUserHandler)
```

like you see in the code above and the signature from before, the second argument is a variadic parameter, it accepts a route handler, middleware or both. usually the middleware is provided before the route handler.

When a request matches the Framework will start running the request context over the functions defined, for example:

```typescript
app.get('/hello', authMiddleware, getHadler)
```

In this example, if a request matches `/hello` it will run `authMiddleware` which probably if the request isn't authorized, it will respond before the request reaches the handler. If request is authorized, The framework will pass the middleware and run the handler.


## References

- [[What are Route handlers]]
- [[Example of Route handler in Hono]]
