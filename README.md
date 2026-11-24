# Queue Implementation in C++

A generic **Queue Data Structure** implemented from scratch in C++ using a custom Doubly Linked List.

## Overview

This project demonstrates the Queue data structure and its main operations.

The Queue follows the **FIFO (First In, First Out)** principle, where the first element inserted is the first one removed.

The implementation uses a custom Doubly Linked List as its underlying data structure.

## Features

### Basic Queue Operations
- `push()` — Add an element to the back of the queue.
- `pop()` — Remove the front element.
- `front()` — Get the first element.
- `back()` — Get the last element.
- `Size()` — Get the number of elements.
- `IsEmpty()` — Check whether the queue is empty.
- `Print()` — Display queue elements.

### Additional Operations
- Get an item by index.
- Update an item.
- Reverse the queue.
- Insert an item after a specific index.
- Insert at the front.
- Insert at the back.
- Clear all elements.

## Project Structure

- `Main.cpp` — Demonstrates queue operations.
- `clsMyQueue.cpp` — Contains the Queue implementation.
- `clsDblLinkedList.cpp` — Contains the underlying Doubly Linked List implementation.

## Technologies

- C++
- Templates
- Object-Oriented Programming
- Pointers
- Dynamic Memory Allocation
- Data Structures

## How to Run

Compile using g++:

```bash
g++ Main.cpp -o Main
```

Run on Windows:

```powershell
.\Main.exe
```

## Learning Objectives

- Understanding the FIFO principle.
- Implementing a Queue from scratch.
- Using a Doubly Linked List to build another data structure.
- Practicing C++ templates and class composition.
- Understanding how data structures can be built on top of each other.

---

**Author:** Ali Abunjm

**GitHub:** [@aliabunjm](https://github.com/aliabunjm)
