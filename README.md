# TypeScript Type Error: Passing Array to String Function

This repository demonstrates a common type error in TypeScript where an array is passed to a function expecting a string. The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides a corrected version.

## Bug Description
The `greeter` function expects a string argument. However, an array is passed to it, resulting in a type error.

## Solution
The solution involves either changing the function signature to accept an array or modifying the function to handle arrays appropriately.  The `bugSolution.ts` file showcases how to handle this using type guards.