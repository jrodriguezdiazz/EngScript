# EngScript Language and Compiler Documentation

## Overview

EngScript is a high-level programming language designed to be intuitive for English speakers. It's tailored for educational purposes, making it easier to grasp fundamental programming concepts. This documentation covers the basics of the EngScript language and its Java-based compiler.

## Language Features

### Data Types and Variables

- **`INT`**: For integer numbers.
- **`DOUBLE`**: For decimal numbers.
- **`STRING`**: For text strings.

### Operations

- **Arithmetic**: `+` (addition), `-` (subtraction), `*` (multiplication), `/` (division).
- **Comparison**: `=` (equals), `>` (greater than), `<` (less than), `>=` (greater than or equal to), `<=` (less than or equal to).
- **Logical**: `AND`, `OR`, `NOT`.

### Control Structures

- **`IF`**: Executes code blocks based on a condition.
- **`FOR`**: Loops with a predetermined number of iterations.
- **`WHILE`**: Loops based on a condition.
- **`READ`**: Reads user input.
- **`WRITE`**: Writes output to the user.

### Comments

- Use `//` for single-line comments.
- Use `/*` and `*/` for multi-line comments.

## Basic Syntax

```java
// Variable definitions
INT counter = 0;
DOUBLE total = 10.5;
STRING name = "EngScript";

// Conditional structure
IF (counter < 10) {
    WRITE("Counter is less than 10.");
}

// Loop structure
FOR (INT i = 0; TO 10; STEP 1) {
    WRITE("Loop iteration: " + i);
}

// Reading user input
STRING userInput;
READ("Enter your name: ", userInput);
WRITE("Hello, " + userInput);
```

## EngScript Compiler

The EngScript compiler, `EngScriptCompiler`, is a Java application that translates EngScript code into Java bytecode, which can then be executed on any Java Virtual Machine (JVM).

### Requirements

- Java SDK version 8 or higher.
- A development environment that supports Java (such as IntelliJ IDEA, Eclipse, or NetBeans).

### Advanced Compiler Features

- **Lexical Analysis**: Breaks down the code into tokens.
- **Syntactic Analysis**: Checks that the code structure is correct.
- **Code Generation**: Produces Java bytecode corresponding to the EngScript code.

## Conclusions and Future Work

EngScript aims to be a gateway for programming beginners, offering syntax and semantics close to English. Future developments will include support for functions, arrays, and more complex data structures.

This document provides an overview and serves as a starting point for more detailed documentation covering all aspects of the language and its compiler.
