# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value.  However, providing a non-numeric value results in an error.

## Bug
The `bug.js` file shows an incorrect usage of `$inc`, attempting to increment a field with a string value. This will produce a MongoDB error.

## Solution
The `bugSolution.js` file corrects the error by ensuring the value used with `$inc` is a number.