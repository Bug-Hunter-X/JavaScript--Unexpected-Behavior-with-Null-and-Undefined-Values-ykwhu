# JavaScript Null and Undefined Handling Bug

This repository demonstrates a common error in JavaScript related to handling null and undefined values. The original code handles null values correctly but fails to account for undefined values, potentially causing unexpected behavior or runtime errors.

The `bug.js` file contains the problematic code.  The `bugSolution.js` file shows the improved code that addresses these issues.

## Bug Description
The `foo` function adds two numbers.  It correctly handles cases where one or both arguments are `null`. However, if either argument is `undefined`, the addition will result in `NaN`. The improved solution handles both `null` and `undefined`.

## Solution
The solution includes additional checks for `undefined` values using the strict equality operator (`===`).