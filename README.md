# Object-Oriented Programming (C++)

Notes, examples and small projects from the *Object-Oriented Programming* course, written in C++.

> **Credit:** the seminar materials in this repository are based on
> [MariaGrozdeva/Object-oriented_programming_FMI](https://github.com/MariaGrozdeva/Object-oriented_programming_FMI).

Follows on from [introduction-to-programming](https://github.com/alifrommars/introduction-to-programming).

## Topics

| # | Topic |
|---|---|
| [01](Sem_01) | Intro to OOP. Structures. Creating instances. Passing/returning instances. Alignment, padding, unions. |
| [02](Sem_02) | Enums (`enum` and `enum class`). Namespaces. Streams. Text files. Put/get pointers. Working with CSV files. |
| [03](Sem_03) | Binary files. Reading and writing binary files. A simple hex viewer. |
| [04](Sem_04) | Methods. Constructors and destructors and their order. Composition. Encapsulation. Getters and setters. |
| [05](Sem_05) | The compilation process. Separate compilation – `.h` and `.cpp` files. |
| [06](Sem_06) | Dynamic memory in classes. The Big Four. The `static` keyword. |
| [07](Sem_07) | Exceptions. |
| [08](Sem_08) | Operator overloading. Friend classes and functions. |
| [09](Sem_09) | Value categories – glvalue, prvalue, xvalue, lvalue, rvalue. Move semantics. |
| [10](Sem_10) | Inheritance (is-a relationship). |
| [11](Sem_11) | Static and dynamic binding. Virtual functions. `override` and `final`. Polymorphism. Abstract classes. |
| [12](Sem_12) | Collections of objects in a polymorphic hierarchy. Factory method. |
| [13](Sem_13) | Multiple inheritance. The diamond problem. |
| [14](Sem_14) | Parametric polymorphism (templates). |
| [15](Sem_15) | Trees of objects in a polymorphic hierarchy. Chess. Set calculator. Type casting. |

## Running the code

Most examples are a `Source.cpp` plus matching `.h`/`.cpp` files. Compile all of them together:

```bash
cd "Sem_06/Big4 examples/Person"
g++ *.cpp -o person
./person
```
