# MongoDB $inc Operator Bug
This repository demonstrates a common bug related to the MongoDB `$inc` operator. The bug involves incorrectly using `$inc` to increment a counter, leading to unexpected behavior. The solution shows the correct way to use the operator for decrementing the counter. 

## Bug Description
The original code demonstrates an incorrect implementation of the `$inc` operator in a MongoDB update operation. This results in the counter being incremented instead of decremented.

## Solution
The correct implementation uses `$inc` with a negative value to properly decrement the counter.