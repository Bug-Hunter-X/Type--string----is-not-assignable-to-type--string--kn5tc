# Type 'string[]' is not assignable to type 'string'
This bug demonstrates a common type error in TypeScript where an array of strings is passed to a function expecting a single string.

## Bug
The `greeter` function expects a single string as input, but the `user` variable is an array of strings.  This mismatch leads to a type error.

## Solution
The solution involves either modifying the `greeter` function to accept an array of strings or modifying the way the `user` variable is handled to provide a single string to the `greeter` function.