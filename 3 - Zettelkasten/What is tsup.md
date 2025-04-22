---
tags:
  - type/zettel
  - topic/typescript
  - topic/bundling
aliases: 
created: 2025-04-20 11:05:15
---
# What is tsup

`tsup` is a bundler 'wrapper' that uses the `esbuild` under the hood,  It is usually used by Typescript Library for bundling, All of the bundling config is usually defined on a config file (`tsup.config.ts`, `tsup.config.js`, `tsup.config.mjs` or tsup property inside of `package.json`)

Tsup supports anything that's supported by Node.js (`.js`, `.mjs`, `.cjs`, `.json`) as well as `.ts` and `.tsx`

## References

- [[What is a bundler]]