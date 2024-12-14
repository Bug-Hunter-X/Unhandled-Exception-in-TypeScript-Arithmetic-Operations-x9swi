# Unhandled Exception in TypeScript Arithmetic Operations

This repository demonstrates a common error in TypeScript: unhandled exceptions. The `bug.ts` file shows a simple arithmetic function that throws an error if the divisor is zero. However, the calling code does not handle this exception, leading to program termination. The `bugSolution.ts` file provides a solution using try-catch blocks to gracefully handle potential errors.

## Bug
The `divide` function throws an exception when the second parameter is 0.

## Solution
The improved version uses a try-catch block to handle the potential error, preventing the program from crashing.