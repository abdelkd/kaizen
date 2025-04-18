---
tags:
  - type/zettel
  - concept/router
  - concept/hono
  - concept/backend
aliases: 
created: 2025-04-17 10:16:45
---
# The RegExpRouter

Although this router may be similar to Express' router, it is quite different (and more performant). Express' uses `path-to-regexp` library for route matching and uses linear matching. Hono on the other hand has its own built-in RegExpRouter which compiles down all the routes into a single regular expression.

When a request comes in it performs a single match against the built regular expression, the result is then used to determine which handler is more specific to handle the request.

It comes also with some limitations: [[Hono's RegExpRouter Limitations]]

## References

- [[What are The Hono Framework Routers]]


## Questions/Thoughts