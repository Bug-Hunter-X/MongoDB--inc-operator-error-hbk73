# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB.

The error occurs when a string is used as an increment value instead of a number.  The `$inc` operator requires a numeric value to perform the increment operation. Using a string will lead to an error or unexpected behavior.

## Bug Description

The bug is caused by providing a string value ('1') to the `$inc` operator which expects a numerical value to increment the field. The correct usage is to pass a numerical value (1) to the `$inc` operator.

## Solution

The solution involves changing the increment value from a string ('1') to a number (1).