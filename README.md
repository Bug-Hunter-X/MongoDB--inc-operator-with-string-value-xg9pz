# MongoDB $inc Operator with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is designed to increment a numeric field by a specified value. However, if you provide a string value, it will lead to incorrect results. 

The `bug.js` file showcases the problematic code and the `bugSolution.js` provides the corrected version.

## Problem
The provided code attempts to increment a field with a string value, leading to an unintended outcome.

## Solution
The corrected code ensures that the value passed to the `$inc` operator is a number, resulting in the correct incrementation of the field.