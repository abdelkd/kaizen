---
tags: type/zettel, 
aliases: 
created: 2025-04-17 12:15:25
---
# LinearRouter

This router registers router as first-registered-first-matched, which means that routes are checked in the order they're registered in. similar to Express' router but the catch is LinearRouter is optimized for Edge and Serverless environments while Express' router is general purpose router.

This router is still generally faster that Express' own router

## References

- [[What are The Hono Framework Routers]]
- [[What is Hono's RegExpRouter]]
- [[What is Hono's LinearRouter]]