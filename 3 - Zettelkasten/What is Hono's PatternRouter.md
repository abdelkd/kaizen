---
tags:
  - type/zettel
  - concept/router
  - concept/backend
  - concept/framework
aliases: 
created: 2025-04-17 12:28:27
---
# PatternRouter

The smallest out of the 5 routers of Hono. It uses a simple implementation where registered routers are saved in a list along with its handler. Then on each request, it loops over the list, matching each segment with the route. 

This router is well suited in environment restricted by resources such as serverless or edge.

## References

- [[What are The Hono Framework Routers]]

## Questions/Thoughts