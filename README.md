# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The issue arises from providing a string value instead of a numeric value to the `$inc` operator, leading to unexpected results or errors.

The `bug.js` file shows the incorrect usage. The `bugSolution.js` file demonstrates the corrected implementation.

## Bug
Incorrectly using a string value ('1') with the `$inc` operator results in an error or unexpected behavior. The `$inc` operator expects a numeric value to increment the field.

## Solution
Correctly use a numeric value (1) with the `$inc` operator to increment the field by 1. 