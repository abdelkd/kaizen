---
tags: type/zettel, 
aliases: 
created: 2025-04-20 11:13:17
---
# How to configure tsup

Even though tsup can be used with no config (through the `tsup` command) it needs configuration whne you want to customize the output (minify, sourcemap...etc).
To configure tsup, all you have to do is create a configuration file (see: [[What is tsup]]) and here's an example of a configuration file:

```ts
import { defineConfig } from 'tsup'

export default defineConfig({
  input: ['src/index.ts'],
  sourcemap: true,
  clean: true,
})
```

`defineConfig` also accepts a function which takes `options` As an argument and returns configuration object.

```ts
import { defineConfig } from 'tsup'

export default defineConfig((options) => ({
  input: ['src/index.ts'],
  sourcemap: true,
  clean: true,
  minify: !options.watch,
}))
```
## Connections


## Questions/Thoughts