# Function multiply

Multiply two values, `x * y`.


## Syntax

```js
math.multiply(x, y)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x`       | Number &#124; BigNumber &#124; Boolean &#124; Complex &#124; Unit &#124; Array &#124; Matrix | First value to multiply
`y`       | Number &#124; BigNumber &#124; Boolean &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Second value to multiply

### Returns

Type | Description
---- | -----------
Number &#124; BigNumber &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Multiplication of `x` and `y`, `x * y`


## Examples

```js
math.multiply(4, 5.2);        // returns Number 20.8

var a = math.complex(2, 3);
var b = math.complex(4, 1);
math.multiply(a, b);          // returns Complex 5 + 14i

var c = [[1, 2], [4, 3]];
var d = [[1, 2, 3], [3, -4, 7]];
math.multiply(c, d);          // returns Array [[7, -6, 17], [13, -4, 33]]

var e = math.unit('2.1 km');
math.multiply(3, e);          // returns Unit 6.3 km
```


## See also

[divide](divide.md)