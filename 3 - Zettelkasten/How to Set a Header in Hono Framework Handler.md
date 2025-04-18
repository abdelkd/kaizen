---
tags:
  - type/zettel
  - concept/hono
  - concept/server
  - concept/backend
aliases: 
created: 2025-04-17 19:45:04
---
# How to Set a Header in Hono Framework Handler

Headers are essential part of REST APIs and Hono allows us to set custom headers using the `c.header(name, value)`

```ts
c.header('X-Header-Name', 'Header-Value')
```

## References

- [[How to Access Path Parameters in Hono Framework]]
- [[How to Access Query Parameters in Hono Framework]]
- [[Example of Route handler in Hono]]
## Questions/Thoughts