---
tags:
  - type/zettel
  - concept/router
  - concept/hono
  - concept/backend
aliases: 
created: 2025-04-17 11:38:15
---
# Limitations of the Router

## 1. No Support for wildcard matching in the middle of the route

RegExpRouter does not support Wildcard Matching (\*) **in the middle of the route**. for example `/api/*/action` this path would accept `/api/some/action` but it would not support `/api/some/other/action` it cannot escape `/`

## 2. No Support for Optional Parameters

RegExpRouter does not support optional parameters, the following pattern `/user/:id?` would work well with `/user/23` but not `/user/`

## 3. No Support for Mixed Parameter Types in One Segment

Mixing static parts and parameters (e.g: `/file-:name.json`) are not supported. A route like: `/api/file-:id.json` would not work, it must be either full static segment or single parameter.


## References

- [[What is Hono's RegExpRouter]]
- [[What are The Hono Framework Routers]]