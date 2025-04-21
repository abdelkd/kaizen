---
tags:
  - type/zettel
  - concept/hono
  - concept/server
  - concept/backend
aliases: 
created: 2025-04-17 18:53:25
---
# How to Extends Context inside of Middleware

Sometimes you want to associate a value in the context from middleware and use it later on inside of the handler.

This is available by using the `createMiddleware` helper and providing a type with `Variables` object and the set the variable by using `c.set(key, value)` before calling `next` :

```ts
import { createMiddleware } from 'hono/factory';

type EchoMiddlewareVars = {
  Variables: {
    echo: (str: string) => string
  }
}

const echoMiddleware = createMiddleware<EchoMiddlewareVars>(async (c, next) => {
  c.set('echo', (str) => str);
  await next();
})

app.get('/echo', async (c) => {
  return c.text(c.vars.echo('Hello'))
})
```

## References

- [[What is a Middleware in Hono Framework]]

## Questions/Thoughts