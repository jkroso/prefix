# prefix

add a vendor prefix to a css attribute

## Installation

```sh
npm install prefix
```

then in your app:

```js
var prefix = require('prefix')
```

## API

### prefix(key)

  Prefix `key`. This function memoizes its results so you don't need to worry about any performance issues, just treat it like a map.

```js
prefix('transform') // => WebkitTransform
prefix('color') // => color
```

### dash(key)

  create a dasherize version of a vendor prefix

```js
prefix.dash('transform') // => -webkit-transform
prefix.dash('color') // => color
```

## Running the tests

Just run `make` and navigate your browser to the test directory.
