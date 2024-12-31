# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numeric field. However, if you provide a string value instead of a number, the operation will fail silently or produce unexpected results.

## Bug
The original code attempts to increment the 'field' value by '1', but it provides the value as a string causing the update to fail.

## Solution
The solution shows the correct usage of the `$inc` operator with the numerical value.