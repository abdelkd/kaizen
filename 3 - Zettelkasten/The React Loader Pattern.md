---
tags:
  - type/zettel
  - concept/web
  - concept/router
  - concept/ssr
aliases: 
created: 2025-04-12 12:42:23
---
# Loader Pattern

This is a pattern used in React and makes use of `loader` function present in Tanstack Router and Tanstack Query to kickstart the request starting from the route request instead of awaiting the load of the component on the client side.

## How to use the Pattern

- We define a `loader` function in our route and call `prefetchQuery` with the required arguments. [[Tanstack Query How to Prefetch]]
- If multiple queries need to be prefetched, we make use of `Promise.all` [[Handling multiple promises]]
- We then consume the prefetched requests on client using the `useSuspenseQuery` hook instead of the regular `useQuery` hook.
- In the case of using Tanstack Router we don't need to explicitly handle pending and error state as this is handled by Tanstack Router's suspense boundary. [[Tanstack Router Handle Pending State]] [[React Router Handle Error State]]

## Connections

- [[React Patterns]] - This pattern is a part of broader list of react patterns
- [[Tanstack Router]] - This routing library is helpful as it provides the `loader` function and the implicit suspense boundary
- [[Tanstack Query]] - Required to prefetch and fetch requests 
- [[React Suspense Boundary]] - This is helpful for understanding how to handle fallback UI and handling errors outside if the components 