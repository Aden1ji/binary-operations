# Binary Operations Project

## Overview

This project extends a Binary class by adding three binary operations: logical OR, logical AND, and binary multiplication. Each operation takes two binary values as input and returns a binary result.

The project includes an interactive application and automated unit tests.

## Implemented Operations

### Logical OR

Performs a bitwise logical OR operation between two binary values. Each output bit is 1 if at least one of the corresponding input bits is 1.

### Logical AND

Performs a bitwise logical AND operation between two binary values. Each output bit is 1 only if both corresponding input bits are 1.

### Binary Multiplication

Performs multiplication between two binary values. This operation is implemented using repeated binary addition to reuse existing logic.

## Application Updates

The App class was updated to call the new binary operations. Users can input two binary values, select an operation, and view the resulting binary output.

## Testing

Unit tests were written using the JUnit framework. At least three test cases were created for each new operation to verify correctness and edge cases.

## Build and Run

## Build and Run

### Build the project
```bash
mvn clean package
```

### Run tests
```bash
mvn test
```
