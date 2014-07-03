---
layout: default
---

<h1 id="function-squeeze">Function squeeze</h1>

Squeeze a matrix, remove outer singleton dimensions from a matrix.


<h2 id="syntax">Syntax</h2>

```js
math.squeeze(x)
```

<h3 id="parameters">Parameters</h3>

Parameter | Type | Description
--------- | ---- | -----------
`x` | Matrix &#124; Array | Matrix to be squeezed

<h3 id="returns">Returns</h3>

Type | Description
---- | -----------
Matrix &#124; Array | Squeezed matrix


<h2 id="examples">Examples</h2>

```js
math.squeeze([3]);           // returns 3
math.squeeze([[3]]);         // returns 3

var A = math.zeros(1, 3, 2); // returns [[[0, 0], [0, 0], [0, 0]]] (size 1x3x2)
math.squeeze(A);             // returns [[0, 0], [0, 0], [0, 0]] (size 3x2)

// only outer dimensions will be squeezed, so the following B will be left as as
var B = math.zeros(3, 1, 1); // returns [[[0]], [[0]], [[0]]] (size 3x1x1)
math.squeeze(B);             // returns [[[0]], [[0]], [[0]]] (size 3x1x1)
```


<h2 id="see-also">See also</h2>

[subset](subset.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->