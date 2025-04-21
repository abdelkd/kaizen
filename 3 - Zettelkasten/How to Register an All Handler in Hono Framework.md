---
tags:
  - type/zettel
  - concept/hono
  - concept/backend
aliases: 
created: 2025-04-17 17:01:31
---
# How to Register an All Handler in Hono Framework

Sometimes, you would want to register an all router which is effectively register a certain route path to accept all HTTP methods (*GET, POST, PUT, DELETE*)

Hono provides a similar function to the ones on [[How to Register a Route Handler in Hono Framework]]. It handles all the incoming requests for that route no matter what the HTTP method is, here's an example:

```typescript
app.all('/hello', handler)
```

this handler will run on all requests targeting `/hello`

## References

- [[What are Route handlers]]