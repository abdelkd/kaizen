---
tags:
  - type/zettel
  - concept/hono
  - concept/router
  - concept/server
  - concept/backend
aliases: 
created: 2025-04-17 13:41:19
---
# Example of Route handler in Hono

A handler is a function that runs on the specified request (see: [[What are Route handlers]]) here's an example of a route handler in Hono:

```typescript
app.get('/api/hello', (c) => {
  return c.json({ response: 'Hello, Hono!' })
})
```

In this example, we setup `/api/hello` as a route that accepts GET request, it returns a JSON response with `response` as `Hello, Hono!`

the `c` argument contains details about the request and methods to help respond to the request and set headers/cookies


## References

- [[What is The Hono Framework]]
