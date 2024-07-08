# C0 Compiler
![Haskell](https://img.shields.io/badge/haskell-%235D4F85?style=for-the-badge&logo=haskell)

## About
A basic compiler for C0 language[^1]. This compiler reads C0 code and generates a code in Assembly for MIPS architecture.

[^1]: A simplified version of C language created for teaching programming created by University Carnegie Mellon. See [C0 Reference Guide](https://c0.cs.cmu.edu/docs/c0-reference.pdf).

## Commands Accepted
  - Basic types (int, bool) and constants such as `true`, `false` and integer numbers.
  - String type
  - Arithmetic expressions: `+`, `-`, `*`, `/` and `%`.
  - Variable declarations, and variable simple attributions of value: `var = expr`.
  - Comparison operators: `==`, `!=`, `<`, `<=`, `>`, `>=`
  - Conditional executors:
    ```bash
    if(expression)
      *instruction or instructionblock*
    ```
    ```bash
    if(expression)
      *instruction or instructionblock*
    else
      *instruction or instructionblock*
    ```
  - Instruction blocks: `{ instructions }`
  - Cycles: `while(expr) intr` or `for`
  - Function definitions with argument parameters and possible return of a value
  - Functions for IO of integers: `scan_int()`, `print_int()`
  - Printing function for string: `print_str()`
  - Flux control: `break` and `continue`
  - Logical operators with *short-circuit* evaluation: `!`, `&&` and `||`

## Contributors
  - Rui Santos
