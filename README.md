# Unexpected Type Coercion in JavaScript Arithmetic

This example demonstrates a common error in JavaScript related to type coercion in arithmetic operations.  Due to JavaScript's dynamic typing, adding a number to a string results in string concatenation rather than numerical addition. This can lead to unexpected behavior and bugs that are difficult to track down.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version that addresses the type coercion issue by explicitly converting the input to numbers before performing the addition.