---
tags:
  - type/zettel
  - concept/hono
  - concept/backend
  - concept/framework
aliases: 
created: 2025-04-17 18:00:43
---
# What is The Execution Order in a Request in Hono Framework

The middlewares are run based on the order they're registered in. here's an example of the register order.

```typescript
app.use(async (_, next) => {
  console.log('middleware 1 start')
  await next()
  console.log('middleware 1 end')
})
app.use(async (_, next) => {
  console.log('middleware 2 start')
  await next()
  console.log('middleware 2 end')
})
app.use(async (_, next) => {
  console.log('middleware 3 start')
  await next()
  console.log('middleware 3 end')
})

app.get('/', (c) => {
  console.log('handler')
  return c.text('Hello!')
})
```

the result would be:

```
middleware 1 start
  middleware 2 start
    middleware 3 start
      handler
    middleware 3 end
  middleware 2 end
middleware 1 end
```

if any of the middlewares or handler throws, Hono will call `app.onError()` callback. That means `await next()` will never throw so no need to wrap it in `try/catch/finally`
## References

- [[What is a Middleware in Hono Framework]]


## Questions/Thoughts