---
tags:
  - type/zettel
  - concept/backend
  - concept/hono
  - concept/framework
  - concept/server
aliases: 
created: 2025-04-17 13:32:29
---
# What are Route handlers

In the context of backend or web frameworks such as Hono, a handler is usually a function that is mapped to a route path. When the route is matched with the request (usually using router) the framework will run the handler function with arguments (in case of Hono it is `context` argument).

The parameters given to the handler function allows it to access request data such as: *request params, IP, body data, headers, cookies...etc*. and also perform actions such as: *setting headers, cookies or respond with JSON or binary data*

The value returned by the handler is sent as a response.


## References

- [[What is The Hono Framework]]
- [[What are The Hono Framework Routers]]

