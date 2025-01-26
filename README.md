# Type Error in TypeScript: Passing an Array to a Function Expecting a String

This repository demonstrates a common type error in TypeScript: passing an array to a function that expects a string.  The error occurs because the function's type signature explicitly requires a string argument, and the code attempts to pass an array instead. This leads to a compilation error, preventing the code from running.

The solution involves either modifying the function to accept an array or modifying the call site to pass a string argument. This example highlights the importance of type safety in TypeScript and demonstrates how type errors can be effectively identified and corrected.