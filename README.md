# Unexpected NaN result when using null in arithmetic operations

This example demonstrates a common source of confusion in JavaScript: the inconsistent behavior of `null` in arithmetic operations.

In some cases, `null` is automatically converted to `0`, leading to seemingly correct results. However, in other cases, it results in `NaN` (Not a Number), which can be difficult to debug.

The `bug.js` file demonstrates this inconsistency. The solution `bugSolution.js` offers a way to handle this by explicitly checking for `null` before performing arithmetic operations.

## How to run

1. Save the code from `bug.js` and `bugSolution.js` to separate files.
2. Open your browser's developer console or use Node.js to execute the files.  You'll observe the unexpected behavior and the fix provided by `bugSolution.js`.

## Further Reading

* JavaScript Type Conversion: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Type_coercion
* NaN in JavaScript: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN