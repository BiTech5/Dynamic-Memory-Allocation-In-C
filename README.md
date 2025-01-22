# Dynamic-Memory-Allocation-In-C


This repository demonstrates the concepts and practical implementation of dynamic memory allocation in C. Dynamic memory allocation is a key aspect of C programming, enabling developers to allocate and manage memory during runtime efficiently.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Examples](#examples)
- [Contributing](#contributing)


## Introduction

Dynamic memory allocation allows programs to request memory during runtime and release it when it is no longer needed. This is particularly useful for:

- Handling variable-sized data structures like arrays or linked lists.
- Optimizing memory usage by freeing unused memory.
- Managing memory in applications with unpredictable resource requirements.

This project provides code examples that illustrate the use of dynamic memory allocation functions such as:

- `malloc()`
- `calloc()`
- `realloc()`
- `free()`

## Features

- Simple and clear code examples.
- Demonstrates memory allocation for arrays and linked lists.
- Includes examples of resizing memory blocks with `realloc()`.
- Shows proper usage of `free()` to avoid memory leaks.

## Prerequisites

To run the code in this repository, you need:

- A C compiler (e.g., GCC, Clang).
- Basic understanding of C programming.

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/BiTech5/Dynamic-Memory-Allocation-In-C.git
   cd Dynamic-Memory-Allocation-In-C
   ```

2. Compile the code:

   ```bash
   gcc -o dynamic_memory_example dynamic_memory_example.c
   ```

3. Run the executable:

   ```bash
   ./dynamic_memory_example
   ```

4. Observe the outputs and modify the code as needed for further experimentation.

## Code Overview

### Key Files

- `dynamic_memory_example.c`: Contains examples demonstrating various dynamic memory allocation techniques.

### Functions Explained

- **`malloc()`**: Allocates a specified number of bytes and returns a pointer to the allocated memory.
- **`calloc()`**: Allocates memory for an array of elements, initializes them to zero, and returns a pointer to the memory.
- **`realloc()`**: Changes the size of previously allocated memory.
- **`free()`**: Deallocates memory previously allocated by `malloc()`, `calloc()`, or `realloc()`.

## Examples

Below are some practical examples included in the repository:

1. **Array Allocation**
   - Allocates memory for an array and demonstrates reading and writing elements.

2. **Linked List**
   - Dynamically allocates memory for linked list nodes and shows traversal.

3. **Resizing Memory**
   - Uses `realloc()` to dynamically resize arrays based on runtime requirements.

## Contributing

Contributions are welcome! If you have improvements or additional examples to share, feel free to:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your branch.
4. Open a pull request.


Thank you for exploring dynamic memory allocation in C through this repository! If you have any questions or suggestions, feel free to open an issue or contribute directly.
