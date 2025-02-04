# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is designed to increment numeric values, but if you try to use it with a string, it will throw an error.

## Bug
The `bug.js` file contains the incorrect code that attempts to increment a field by a string value. This results in a MongoDB error.

## Solution
The `bugSolution.js` file provides the corrected code. It uses a numeric value to increment the field, fixing the error.