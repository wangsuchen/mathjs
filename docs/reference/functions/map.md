---
layout: default
---

<h1 id="function-map">Function map</h1>

Create a new matrix or array with the results of the callback function executed on
each entry of the matrix/array.


<h2 id="syntax">Syntax</h2>

```js
math.map(x, callback)
```

<h3 id="parameters">Parameters</h3>

Parameter | Type | Description
--------- | ---- | -----------
`x` | Matrix &#124; Array | The matrix to iterate on.
`callback` | Function | The callback method is invoked with three parameters: the value of the element, the index of the element, and the matrix being traversed.

<h3 id="returns">Returns</h3>

Type | Description
---- | -----------
Matrix &#124; array | Transformed map of x


<h2 id="examples">Examples</h2>

```js
math.map([1, 2, 3], function(value) {
  return value * value;
});  // returns [1, 4, 9]
```




<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->