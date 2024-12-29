# Unhandled Error in Arithmetic Operations

This repository demonstrates a common error in JavaScript: an unhandled error that causes the program to crash. The specific error in this case is division by zero.

## The Bug

The `divide` function does not handle the case where the divisor is zero. When attempting to divide by zero, a runtime error occurs, halting the program's execution.

## The Solution

The solution involves adding error handling to gracefully handle potential division by zero. This is done by checking the divisor before performing the division and throwing an error or returning an appropriate value if the divisor is zero.
