---
tags:
  - type/source
  - source/youtube
  - topic/react
  - topic/loader
author:
  - Cosden Solutions
link:
  - https://youtu.be/iO6px_wz1oc
created: 2025-04-12
status: finished
rating:
---
# Source: [Youtube](https://youtu.be/iO6px_wz1oc)

A react pattern that uses Tanstack Router and suspense boundary to load requests starting from route request which improves performance.

## Summary / Key Takeaways

The video discusses a react pattern that aims to start fetch request on server using the `loader` function. The function will start as soon as the client requests the route. This pattern aims to reduce complexity of the client component, since the request is prefetched on loader. in the case of Tanstack Router the package also handles suspense and error boundary.

## Notes & Highlights

- This pattern is better than fetching on client only since the app would not wait for the bundle to load on client to start fetching [[React Bundling and Loading]]
* We prefetch the request using Tanstack Query `prefetchQuery` function [[Tanstack Query How to Prefetch]]
* If there are multiple queries to be made, we make use of `Promise.all` or `Promise.allSettled` [[Handling multiple promises]]
* On the component we use the hook `useSuspenseQuery` which will defer the loading and error to the nearest suspense boundary. [[React Query useSuspenseQuery]]
* Since all of the component fetch related state is handled by suspense boundary, we do not need to handle loading and error inside of our component [[React Suspense Boundary]]
* Tanstack Router wraps each route with suspense boundary which can be defined on `pendingComponent` and `errorComponent` [[Tanstack Router Handle Pending State]] [[React Router Handle Error State]]

## Related Concepts / MOCs

* [[JavaScript Fetch]]
* [[Javascript Promises]]
* [[Tanstack Router]]
* [[React Patterns]]

## Generated Zettel

```dataview
LIST FROM "40_ZETTELKASTEN"
WHERE contains(Context/Source, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name ASC