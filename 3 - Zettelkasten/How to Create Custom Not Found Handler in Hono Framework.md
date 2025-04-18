---
tags:
  - type/zettel
  - concept/hono
  - concept/server
  - concept/backend
aliases: 
created: 2025-04-17 19:03:40
---
# How to Create Custom Not Found Handler in Hono Framework

Hono gives the developer the power to customize the response in case of a not found. this handler will run when the request is accessing a route that's not defined:

```ts
app.notFound((c) => c.text('Oops! not found', 404))
app.get('/hello', (c) => c.text('Hello'))
```

Now if there's a request other than `/hello` it will return `Oops! not found` with status 404

## References

- [[What is The Hono Framework]]

## Questions/Thoughts