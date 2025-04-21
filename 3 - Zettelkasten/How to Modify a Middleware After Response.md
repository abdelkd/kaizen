---
tags:
  - type/zettel
  - concept/hono
  - concept/server
  - concept/backend
aliases: 
created: 2025-04-17 18:48:39
---
# How to Modify a Middleware After Response

Sometimes, you'd want to do something with the response before it is fully sent to the user. you can still be able to modify a response by changing the value of the `c.res` like the following:

```ts
const stripRes = createMiddleware(async (c, next) => {
  const res = await next();
  c.res = undefined;
})
```

The `stripRes` middleware will now remove any response that was sent from handler


## References

- [[What is a Middleware in Hono Framework]]
