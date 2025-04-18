---
tags:
  - type/zettel
  - concept/hono
  - concept/server
  - concept/backend
aliases: 
created: 2025-04-17 19:19:33
---
# How to Throw Exceptions in Hono Framework

Sometimes things could go wrong and you'd want to throw errors instead of continuing, Hono provides us this by using `HTTPException` error provided from `hono/http-exception`

```ts
import { HTTPException } from 'hono/http-exception'

// ...

app.use(async (_, next) => {
  const authorized = false;
  if (authorized === false) {
    throw new HTTPException(401, { message: 'Custom error message' })
  }
  await next()
})
```

The response to the user could be customized by providing `res` instead of `message`:

```ts
const errorRes = new Response('Unauthorized', {
  status: 401,
  headers: {
    authorization: 'error="invalid-error"'
  }
})
```

## References

