---
tags:
  - type/zettel
  - concept/hono
  - concept/backend
  - concept/server
aliases: 
created: 2025-04-17 11:56:58
---
# TrieRouter

This is another router from Hono, it uses the [[trie-tree algorithm]]. This builds a tree for the router, each node represents one segment. This allows for fast lookups. It also supports all patters unlike [[What is Hono's RegExpRouter]].


## References

- [[What are The Hono Framework Routers]]