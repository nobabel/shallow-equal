<a href="https://codeship.com/projects/168228" target="_blank"><img src="https://img.shields.io/codeship/53d0b900-42a9-0134-35d6-5a9bff506e9c/master.svg" alt="Build Status"></a>
<a href="https://codecov.io/gh/moroshko/shallow-equal" target="_blank"><img src="https://img.shields.io/codecov/c/github/moroshko/shallow-equal/master.svg" alt="Coverage Status"></a>
<a href="https://www.bithound.io/github/moroshko/shallow-equal" target="_blank"><img src="https://www.bithound.io/github/moroshko/shallow-equal/badges/score.svg" alt="bitHound Overall Score"></a>
<a href="https://npmjs.org/package/shallow-equal" target="_blank"><img src="https://img.shields.io/npm/v/shallow-equal.svg" alt="NPM Version"></a>

## Description

If you know you have two arrays or two objects in hand, and you want to know if they are shallowly equal or not, this library is for you.

## Features

* Super light
* No dependencies
* Thoroughly tested

## Installation

```shell
npm install shallow-equal --save
```

## Usage

```js
var shallowEqualArrays = require('shallow-equal/arrays');

shallowEqualArrays([1, 2, 3], [1, 2, 3])     // => true
shallowEqualArrays([{ a: 5 }], [{ a: 5 }])   // => false
```

```js
var shallowEqualObjects = require('shallow-equal/objects');

shallowEqualObjects({ a: 5, b: 'abc' }, { a: 5, b: 'abc' })   // => true
shallowEqualObjects({ a: 5, b: {} }, { a: 5, b: {} })         // => false
```

## License

<a href="http://moroshko.mit-license.org" target="_blank">MIT</a>
