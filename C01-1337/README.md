# C01-1337

## Description

This repository contains exercises for the **C01 module**. Each exercise is implemented with a `.c` source file, and some exercises include precompiled binaries (`a.exe`). The exercises are designed to deepen understanding of C programming concepts, such as working with pointers, basic arithmetic operations, string manipulation, and function implementations.

---

## Repository Structure

The repository is organized as follows:

- `ex00/`
  - `ft_ft.c`: A function that assigns a value to a pointer.
- `ex01/`
  - `ft_ultimate_ft.c`: A function to manipulate a chain of pointers.
- `ex02/`
  - `ft_swap.c`: A function to swap the values of two integers.
  - `a.exe`: Compiled binary for `ft_swap.c`.
- `ex03/`
  - `ft_div_mod.c`: A function that divides two integers and calculates the remainder.
  - `a.exe`: Compiled binary for `ft_div_mod.c`.
- `ex04/`
  - `ft_ultimate_div_mod.c`: A function that performs division and modulus operations while updating variables through pointers.
  - `a.exe`: Compiled binary for `ft_ultimate_div_mod.c`.
- `ex05/`
  - `ft_putstr.c`: A function to print a string to the standard output.
  - `a.exe`: Compiled binary for `ft_putstr.c`.
- `ex06/`
  - `ft_strlen.c`: A function to calculate the length of a string.
  - `a.exe`: Compiled binary for `ft_strlen.c`.

---

## Detailed Explanation of Functions

### `ft_ultimate_ft.c` (ex01)
- **Functionality**: Assigns the value `42` to an integer through a chain of nine pointers.
- **Prototype**:
  ```c
  void ft_ultimate_ft(int *********nbr);
### `ft_swap.c` (ex02)
- **Functionality: Swaps the values of two integers using their memory addresses.
- **Prototype**:
  ```c
  void ft_swap(int *a, int *b);
### `ft_div_mod.c` (ex03)
- **Functionality: Divides two integers and calculates the remainder, storing them in the provided memory locations.
- **Prototype:
  ```c
  void ft_div_mod(int a, int b, int *div, int *mod);
### `ft_ultimate_div_mod.c` (ex04)
- **Functionality: Updates two integer pointers to store the division result and modulus of two numbers.
- **Prototype:
  ```c
  void ft_ultimate_div_mod(int *a, int *b);
 ### `ft_putstr.c` (ex05)
- **Functionality: Functionality: Prints a string character by character to the standard output.
- **Prototype:
  ```c
  void ft_putstr(char *str);
### `ft_strlen.c` (ex06)
- **Functionality: Calculates and returns the length of a given string.
- **Prototype:
  ```c
  int ft_strlen(char *str);
 ## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/saadfahmi/C01-1337.git
   cd C01-1337
  














  
