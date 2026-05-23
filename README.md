# Lexical Analyzer in C

## Overview
This project is a simple Lexical Analyzer developed using the C programming language. The program reads a C source file and identifies different lexical components such as keywords, identifiers, operators, special symbols, numbers, and header files. It also performs basic error checking like missing semicolons and unmatched braces.

The project demonstrates concepts used in compiler design and helps understand the first phase of a compiler called Lexical Analysis.

---

## Features

- Detects C keywords
- Identifies identifiers and variables
- Recognizes operators and special symbols
- Detects numeric constants
- Identifies header files
- Counts lines, words, and characters
- Detects missing semicolons
- Checks unmatched braces
- Verifies presence of main() function
- Reads source code line by line using file handling

---

## Technologies Used

- C Programming
- File Handling
- String Handling Functions
- Compiler Design Concepts

---

## Project Structure

lexical-analyzer-c/
│
├── main.c
├── definitions.c
├── header.h
├── sample.c
└── README.md

---

## File Description

### main.c
Contains the main function and controls the overall flow of the lexical analyzer.

### definitions.c
Contains functions used for lexical analysis such as keyword checking, operator checking, counting, and error detection.

### header.h
Contains function declarations, macros, and required header file inclusions.

### sample.c
Input source file used to test the lexical analyzer.

---

## How It Works

1. The program opens the sample C file.
2. Reads the file line by line.
3. Separates tokens using delimiters.
4. Compares tokens with predefined keywords and operators.
5. Displays identified lexical components.
6. Performs basic syntax error checking.

---

## Compilation and Execution

### Compile

gcc main.c definitions.c

### Run

./a.out

---

## Sample Output

Keyword       : int
Identifier    : main
Operator      : =
Special Symbol: {
Number        : 10
Header File   : stdio.h

---

## Concepts Covered

- Lexical Analysis
- Tokenization
- File Handling in C
- Compiler Design Basics
- Error Detection
- Pattern Matching

---

## Applications

- Compiler Design Projects
- Academic Mini Projects
- Understanding Tokenization
- Syntax Checking Systems
- Learning File Processing in C

---

## Future Enhancements

- Add syntax analysis phase
- Support more operators and tokens
- Generate symbol table
- Add GUI interface
- Support multiple programming languages

---

## Conclusion

This project demonstrates the implementation of a basic lexical analyzer using the C programming language. It helps in understanding how source code is broken into tokens during the compilation process and provides practical exposure to compiler design fundamentals.

---

## Author

Gagan Bhairamatti
