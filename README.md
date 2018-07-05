# ESLint Config Node Flex Serve

This package provides Node Flex Serve's .eslintrc as an extensible shared config.

## Install

```bash
npm i -D eslint-config-node-flex-serve
```

## Usage

Node Flex Serve's eslint config contains all of our ESLint rules, including ECMAScript 6+ and is similar to [Webpack's ESLint base rules](https://github.com/webpack-contrib/eslint-config-webpack). It requires `eslint` and `eslint-plugin-import`.

## eslint setup

_In your .eslintrc.js || .yml || .json add ..._

```js
// Add to your .eslintrc

"extends": "node-flex-serve"
```