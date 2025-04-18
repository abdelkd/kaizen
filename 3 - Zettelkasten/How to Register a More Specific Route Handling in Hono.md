---
tags:
  - type/zettel
  - concept/hono
  - concept/framework
  - concept/backend
aliases: 
created: 2025-04-17 17:17:44
---
# How to use `on` Method for More Specific Routing

Even though Hono provides two ways of handling routes (see: [[How to Register a Route Handler in Hono Framework|How to Register a Single Route]] and [[How to Register an All Handler in Hono Framework|Register a Catch All Route]]). Sometimes you'd want to an in-between path, maybe register a handler that works only on two or three methods. This is where the `on` method comes for.

the `on` framework is defined as `app.on(method|method[], path|path[], handler|middleware...)`. The only difference from the other methods is that it takes a method or an array of methods as the first argument. `method` refers to any HTTP method.

```typescript
app.on(['get', 'post', 'delete'], '/hello', (c) => {
  return c.text('Hello')
})
```

This route handler will run on GET, POST and DELETE requests matching the route.

## References