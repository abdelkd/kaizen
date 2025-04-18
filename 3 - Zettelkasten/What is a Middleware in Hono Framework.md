---
tags:
  - type/zettel
  - concept/hono
  - concept/backend
  - concept/framework
aliases: 
created: 2025-04-17 17:35:27
---
# What is a Middleware in Hono Framework

Hono allows to assign middlewares, which are functions that runs on all the incoming requests, you still can restrict which paths they run on though. middleware should return nothing.

```typescript
app.use(async (c, next) => {
  console.log('running middleware 1 start')
  await next()
  console.log('running middleware 2 end')
})
```

The first parameter is the request context and second is the next function which is called to go to the next middleware/handler.


## References


## Questions/Thoughts