# Recursive Descent Parser + 

## Overview
Compiler and Interpreter for the **tinyL** programming language, translating tinyL source code into intermediate RISC-like instructions (`tinyL.out`), executed by the interpreter. 

## Features
- **Compiler (`compile`)**
  - Parses tinyL code.
  - Generates `tinyL.out` with executable instructions.
  
- **Interpreter (`run`)**
  - Executes the instructions from `tinyL.out`.
  
- **Utilities**
  - Code formatting with Linux guidelines.
  - Comprehensive error handling.


## Project Structure

- `Compiler.c`: Source code for the compiler.
- `Interpreter.c`: Source code for the interpreter.
- `Instr.h` & `InstrUtils.c`: Instruction definitions and utilities.
- `Utils.h` & `Utils.c`: Utility functions for error handling.
- `Makefile`: Build configuration.
- `tests/`: Directory containing sample tinyL programs.

## License

This project is released under the MIT License.
