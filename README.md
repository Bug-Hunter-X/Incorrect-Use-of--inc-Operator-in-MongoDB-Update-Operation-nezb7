# Incorrect Use of $inc Operator in MongoDB Update Operation

This repository demonstrates a common error encountered when using the `$inc` operator in MongoDB update operations. The error arises from incorrect usage of the operator, leading to unexpected results.  The `bug.js` file shows the erroneous implementation, while `bugSolution.js` provides the corrected version.

## Problem
The `$inc` operator is designed to increment a numerical field by a specified value. However, providing incorrect input, such as non-numerical values or incorrect type usage can cause the operation to fail or produce unexpected results. This example shows such a scenario.

## Solution
The corrected version ensures that the input value is of the correct type (number) and handles potential errors gracefully.  The solution emphasizes the importance of data validation and proper usage of MongoDB operators to avoid unexpected behaviour.
