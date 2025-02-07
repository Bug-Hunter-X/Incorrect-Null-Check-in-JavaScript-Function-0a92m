# Incorrect Null Check in JavaScript Function

This repository demonstrates a common error in JavaScript: incorrect handling of null or undefined values in function parameters. The `foo` function in `bug.js` only explicitly checks for strict equality (`===`) with `null`. This is insufficient as JavaScript also has `undefined`.  The corrected version in `bugSolution.js` shows a more robust approach.

## Bug

The `bug.js` file contains a function that doesn't handle `undefined` values properly, leading to potential issues.

## Solution

The `bugSolution.js` file shows how to correctly handle both `null` and `undefined` parameters using a more comprehensive check.

This example highlights the importance of thorough null and undefined checks when writing JavaScript functions for increased robustness and fewer runtime errors.  A simple `if (a == null || b == null)` check is better than using the strict `===` operator.  We also might want to explicitly check for `undefined`.
