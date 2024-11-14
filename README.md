# Multi-threaded String Manipulation Program

This C++ program demonstrates the use of **POSIX threads (pthread)** and **mutex locks** for multi-threaded string manipulation tasks. The program includes various threads that perform different operations on a user-provided string.

## 🗂️ Features

1. **Main Thread**: Initializes the program.
2. **Input Thread**: Prompts the user to input a string.
3. **Reverse Thread**: Reverses the input string and displays it.
4. **Capitalize Thread**: Converts the string to uppercase.
5. **Shift Thread**: Shifts each character in the string by two positions in the ASCII table.

## 💻 How to Compile and Run

Ensure you have a C++ compiler that supports POSIX threads (e.g., g++). Use the following commands:

```bash
g++ -o string_threads string_threads.cpp -lpthread
./string_threads
