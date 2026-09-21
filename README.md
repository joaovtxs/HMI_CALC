# HMI Modular C Calculator

A modular, command-line calculator built in C. The project utilizes a strict separation of concerns between the Human-Machine Interface (HMI) and mathematical operations.

## Features
* **Basic Arithmetic:** Addition, Subtraction, Multiplication, Division.
* **Algebra:** Exponential power functions.
* **Linear Algebra:** n x n Matrix Determinant calculation utilizing dynamic memory allocation and Gaussian elimination.
* **Input Validation:** Robust handling of user inputs to prevent crashes from invalid keystrokes.

## Project Structure
* `main.c`: Application entry point and menu routing.
* `hmi.c` / `hmi.h`: Handles all terminal display outputs, console menus, and validated user data entry.
* `op.c` / `op.h`: Contains the core mathematical algorithms.
