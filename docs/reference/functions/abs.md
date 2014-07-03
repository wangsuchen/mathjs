---
layout: default
---

<h1 id="function-abs">Function abs</h1>

Calculate the absolute value of a number. For matrices, the function is
evaluated element wise.


<h2 id="syntax">Syntax</h2>

```js
math.abs(x)
```

<h3 id="parameters">Parameters</h3>

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; BigNumber &#124; Boolean &#124; Complex &#124; Array &#124; Matrix |  A number or matrix for which to get the absolute value

<h3 id="returns">Returns</h3>

Type | Description
---- | -----------
Number &#124; BigNumber &#124; Complex &#124; Array &#124; Matrix |  Absolute value of `x`


<h2 id="examples">Examples</h2>

```js
math.abs(3.5);                // returns Number 3.5
math.abs(-4.2);               // returns Number 4.2

math.abs([3, -5, -1, 0, 2]);  // returns Array [3, 5, 1, 0, 2]
```


<h2 id="see-also">See also</h2>

[sign](sign.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->