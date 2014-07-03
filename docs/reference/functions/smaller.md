---
layout: default
---

<h1 id="function-smaller">Function smaller</h1>

Test whether value x is smaller than y.

The function returns true when x is smaller than y and the relative
difference between x and y is larger than the configured epsilon. The
function cannot be used to compare values smaller than approximately 2.22e-16.

For matrices, the function is evaluated element wise.


<h2 id="syntax">Syntax</h2>

```js
math.smaller(x, y)
```

<h3 id="parameters">Parameters</h3>

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; BigNumber &#124; Boolean &#124; Unit &#124; String &#124; Array &#124; Matrix | First value to compare
`y` | Number &#124; BigNumber &#124; Boolean &#124; Unit &#124; String &#124; Array &#124; Matrix | Second value to compare

<h3 id="returns">Returns</h3>

Type | Description
---- | -----------
Boolean &#124; Array &#124; Matrix | Returns true when the x is smaller than y, else returns false


<h2 id="examples">Examples</h2>

```js
math.smaller(2, 3);            // returns true
math.smaller(5, 2 * 2);        // returns false

var a = math.unit('5 cm');
var b = math.unit('2 inch');
math.smaller(a, b);            // returns true
```


<h2 id="see-also">See also</h2>

[equal](equal.html),
[unequal](unequal.html),
[smallerEq](smallerEq.html),
[larger](larger.html),
[largerEq](largerEq.html),
[compare](compare.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->