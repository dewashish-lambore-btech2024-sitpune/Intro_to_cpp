# C++ Experiment 1: Hello World and Calculator Application

---

## Aim

To:
1. Display a simple "Hello, World!" message through a basic C++ program.
2. Build a calculator that performs fundamental arithmetic operations based on user input.

---

## Tool Used

- Visual Studio Code (VS Code)

---

## Objectives

- Comprehend the structure of a C++ program.
- Understand the usage of `#include` directives for importing libraries.
- Utilize `cin` and `cout` for input and output handling.
- Implement basic arithmetic operations in C++.
- Grasp syntax elements like `using namespace std;`, function structure, and data types.
- Learn to add comments using `//` for code clarity and ease of understanding.

---

## Theory

C++ is a versatile, high-level programming language derived from the C language. It incorporates object-oriented features, strong type checking, and a rich set of libraries. C++ is commonly used in system programming, embedded applications, and software development requiring high performance and efficiency.

### Why C++ is Superior to C

C++ provides several advantages over C, making it more suitable for contemporary software development:

- C++ supports **Object-Oriented Programming (OOP)** concepts such as classes, objects, inheritance, and polymorphism. This facilitates better program organization, code reuse, and easier maintenance.
- It allows **function overloading** and **operator overloading**, enabling different implementations of the same function/operator based on parameters.
- The **Standard Template Library (STL)** in C++ offers ready-to-use data structures like vectors, lists, stacks, queues, maps, and common algorithms.
- C++ enforces **stronger type safety**, which helps identify errors at compile time.
- It supports **encapsulation and abstraction**, concealing implementation details and improving program manageability.
- Memory handling is enhanced via **constructors, destructors, and RAII (Resource Acquisition Is Initialization)**.
- **Namespaces** help prevent name clashes in large projects by logically grouping related functions, classes, and objects.

These features make C++ a more robust, scalable, and developer-friendly language compared to C, especially for complex and large-scale applications.

### Program Structure in C++

- `#include <iostream>` is a preprocessor command to include the standard input-output stream library, which provides `cin`, `cout`, and `endl`.
- `using namespace std;` instructs the compiler to use the standard C++ namespace so that we don’t need to prefix `std::` before standard functions.
- `int main()` is the entry point of every C++ program. Every executable C++ program requires a main function.
- `cout` is used to display data on the console, and `cin` is used to accept user input.
- Conditional statements like `if` and `else` allow the program to make decisions based on certain conditions.
- Arithmetic operators (`+`, `-`, `*`, `/`) are used to perform basic mathematical operations.
- Data types such as `int`, `float`, and `double` define the kind of data a variable can hold.
- `return 0;` indicates the successful completion of the program.
- Comments are added using `//` and are ignored during compilation. They are used to clarify code logic.

---

## Program Description

### Part 1: Hello World

- A simple program that prints “Hello, World!” on the console.
- It demonstrates the basic syntax of a C++ program including header inclusion, main function, and output commands.

### Part 2: Calculator Program

This program prompts the user to enter two numbers and performs the following operations:
- Addition
- Subtraction
- Multiplication
- Division

The results of these operations are then displayed using `cout`. The program uses basic arithmetic operators and variables to hold the results.

---

## Concepts Used

- Header files: `#include <iostream>`
- Namespaces: `using namespace std;`
- Input/Output: `cin`, `cout`
- Functions: `main()`, `return 0;`
- Variables and Data Types: `int`, `float`, `double`
- Operators: `+`, `-`, `*`, `/`
- Conditional Statements: `if`, `else`
- Comments: `//`

---

## Sample Output

