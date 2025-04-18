---
tags:
  - type/zettel
  - concept/hono
  - concept/framework
  - concept/backend
aliases: 
created: 2025-04-17 16:28:09
---
# How to Respond with JSON in The Hono Framework

In APIs responding with JSON is crucial and almost always is the default. Hono provides a helper function inside of the context argument that will transform JavaScript objects into valid response value. like the following example:

```typescript
app.get('/api/hello', (c) => {
  return c.json({
    ok: true,
    message: 'Hello Hono!',
  })
})
```

## References

- [[Example of Route handler in Hono]]

## Questions/Thoughts