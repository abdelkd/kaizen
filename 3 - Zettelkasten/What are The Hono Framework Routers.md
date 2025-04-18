---
tags:
  - type/zettel
  - concept/server
  - concept/backend
  - concept/framework
aliases: 
created: 2025-04-17 10:05:05
---
# What are The Hono Framework Routers

Unlike Express which employs path-matching algorithm (see: [[What is path-matching algorithm]]), Hono comes with 5 routers and each one of them has its pros and cons and use case. This gives the developer the power to choose between each router and each use case.

## 1. RegExpRouter

This is the fastest Hono route and is more faster than Express' own router. (see: [[What is Hono's RegExpRouter]]) and its limitations [[Hono's RegExpRouter Limitations]]

## 2. TrieRouter

Although it is not as fast as RegExpRouter, it still faster than Express' router. (see: [[What is Hono's TrieRouter]]) The only know cons of this router is that it is not as fast as RegExpRouter

## 3. SmartRouter

Since RegExpRouter does have some drawbacks, what this router does is it acts like a Frontend (or a router of routers). it defaults to RegExpRouter but if a route is not supported or limited (see: [[Hono's RegExpRouter Limitations]]) then it would route it to TrieRouter.

## 4. LinearRouter

This is a router for a special use case, it is made for environments where routes are registered frequently. (see: [[What is Hono's LinearRouter]])

### 5. PatternRouter

The smallest router out of the five, It is made for environments where resources are limited. such as serverless and edge environments. (see: [[What is Hono's PatternRouter]])

## References

- [[What is The Hono Framework]]
- [[Where Can Hono be Used]]