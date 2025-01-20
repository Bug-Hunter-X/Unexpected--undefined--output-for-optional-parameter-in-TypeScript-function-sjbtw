# Unexpected 'undefined' output for optional parameter in TypeScript function

This repository demonstrates a subtle issue with optional parameters in TypeScript functions. When an optional parameter is not provided, the function prints 'undefined' to the console instead of an empty string or nothing.

## Bug Description
The `printName` function is defined to accept an optional string parameter. When called without an argument, it should ideally print an empty string or nothing. However, it prints 'undefined'.

## Bug Solution
The bug is resolved by providing a default value of an empty string to the optional parameter in the function's definition.