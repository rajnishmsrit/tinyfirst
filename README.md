# @rajnishkr/tinyfirst

[![npm (scoped)](https://img.shields.io/npm/v/@rajnishkr/tinyfirst.svg)](https://www.npmjs.com/package/@bamblehorse/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@rajnishkr/tinyfirst.svg)](https://www.npmjs.com/package/@bamblehorse/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @rajnishkr/tinyfirst
```

## Usage

```js
const tiny = require("@rajnishkr/tinyfirst");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
