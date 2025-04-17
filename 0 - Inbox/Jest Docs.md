# Jest Docs

## What is Jest

Jest is a testing framework made by Meta (facebook) aims to help developers create and run tests of their applications

## Getting started

You can start using Jest simply by installing using your favorite package manager.

```sh
npm install --save-dev jest
```

After installing it you have to add *test* script to `package.json` like following:
```json
{
  "scripts": {
    "test": "jest"
  }
}
```

To start testing, you create the module where you define your functions, then create a testing file (eg. sum.test.js) and import the function or module you want to test.

```javascript
const sum = require('./sum.js')

test('adds 1 + 2 equals 3', () => {
  expect(sum(1,2)).toBe(3)
})
```

## Using TypeScript with Jest

To use TypeScript with jest you'll have to install additional package called `ts-jest` this will help with transpilation process.

It is as easy as installing and invoking init command.
```sh
npm install --save-dev ts-jest # Install ts-jest
npx ts-jest config:init # Initialize configuration 
```

An then add the TypeScript Jest types using:
```sh
npm install --save-dev @jest/global
```


## Matchers

### Common Matchers

To test if a value is the equal we use `.toBe` which uses `Object.is` for checking. Not equal can be done by using `.not.toBe` function, we an use `.toEqual` or `toStrictEqual` to check for objects.:

```javascript
test("describe your test", () => {
  test("2 + 2", () => {
    expect(2 + 2).toBe(4)
    expect(3-2).not.toBe(0)
    expect({name: "hello"}).toEqual({name: "hello"})
  })
})
```

Jest contains helpers to handle truthiness.
- **toBeNull** Matches only `null`
- **toBeUndefined** matches only `undefined`
- **toBeDefined** the opposite of undefined
- 