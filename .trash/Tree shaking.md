**Definition:** Tree Shaking is a dead code elimination technique that removes unused variables, functions or modules from the final JavaScript bundle.

## How it Works

* A bundler like **Webpack, Rollup, Esbuild** checks code and finds unused parts
* The bundler then eliminates the unused parts from the JavaScript bundle.

## What Gets Removed?

* **Named Exports** gets removed: when you export a function but do not use it anywhere
* **Unused Function Values:** When you call a function but do not use the function returned value, this happens only if function is pure (meaning it doesn't have side effects like logging, fetch call...etc)

## What are The Benefits

* Smaller bundle size
* Faster loading time
* Better performance
* Less bandwith usage on web apps