---
tags:
  - type/zettel
  - concept/hono
  - concept/server
  - concept/backend
  - concept/framework
aliases: 
created: 2025-04-17 19:35:38
---
# How to Access Path Parameters in Hono Framework

Hono context provides way to access path parameters (which defined as `:something` in route) This is possible using `c.req.params(key)` where *key* is the param name.

```ts
app.get('/user/:userid', async (c) => {
  const userId = c.req.params('userid')
  // ... we can use userId
})
```

## References

- [[How to Access Query Parameters in Hono Framework]]
