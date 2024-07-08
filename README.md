# C0 Compiler
![Haskell](https://img.shields.io/badge/haskell-%235D4F85?style=for-the-badge&logo=haskell)

## About
A basic compiler that reads C0[^1] language code and generates a code in Assembly for MIPS architecture.

[^1]: A simplified version of C language created for teaching programming created by University Carnegie Mellon. See [C0 Reference Guide](https://c0.cs.cmu.edu/docs/c0-reference.pdf).

## Commands Accepted
  - Basic types (int, bool) and constants such as `true`, `false` and integer numbers.
  - String type
  - Comments in line or block multiline: `//` or `/* multiline comment */`
  - Arithmetic expressions: `+`, `-`, `*`, `/` and `%`
  - Variable declarations, and variable simple attributions of value: `variable_name = expression`
  - Comparison operators: `==`, `!=`, `<`, `<=`, `>`, `>=`
  - Conditional executors:
    ```
    if(expression)
      //single line instruction or instruction block
    ```
    ```
    if(expression)
      //single line instruction or instruction block
    else
      //single line instruction or instruction block
    ```
  - Instruction blocks:
    ```
    {
      //instructions
    }
    ```
  - Cycles `for` or `while`:
    ```
    while(expression)
      //single line instruction or instruction block
    ```
  - Function definitions with argument parameters and possible return of a value
  - Functions for IO of integers: `scan_int()`, `print_int()`
  - Printing function for string: `print_str()`
  - Flux control: `break` and `continue`
  - Logical operators with *short-circuit* evaluation: `!`, `&&` and `||`

## Contributors
  - Rui Santos
