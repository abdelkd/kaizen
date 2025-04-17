---
tags:
  - type/zettel
  - field/web
  - lang/js
  - lang/ts
  - topic/treeshaking
aliases: []
created: 2025-04-11 22:19:27
---
# What Gets Removed During Tree Shaking

There are several things that get removed from the final JavaScript  bundle, which are:

## Named Exports

Functions that are exported but not used gets removed from the final bundle. In the following code `unused` will not be on the bundled javascript file.

```javascript
// utils.js
export used = () => {
  return 44;
}
export unused = () => {
  return 77;
}

// main.js
import { used } from './utils.js'
console.log(used())
```

## Unused Pure function calls:

pure functions are functions with no side effects (fetching, logging...etc). In the previous code `used` and `unused` are both pure functions. An unsed function call is calling a function without assigning the returned value into a variable.

```javascript
used() // This line won't get into the final bundle
```


## Connections

* [[Tree Shaking Definition]]
* [[How Does Tree Shaking Work]]
* [[Benefits of Tree Shaking]]