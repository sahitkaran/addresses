/*
README.md
# Virtual Address Breakdown – addresses.c

This simple C program takes a virtual memory address as input and outputs its **page number** and **offset**, assuming a **page size of 4096 bytes (4 KB)**.

# What It Does?

Given an unsigned integer address from the command line, the program:
1. Parses it as an integer.
2. Computes:
   - Page number = address / 4096
   - Offset      = address % 4096
3. Displays the results.

# Example
----------
$ ./addresses 57005
The address 57005 contains:
page number = 13
offset = 1741

# How to Compile & Run

Compile:
    gcc -o addresses addresses.c

Run:
    ./addresses <virtual_address>. (Replace <virtual_address> with a positive integer)

# Notes

- The program expects exactly one command-line argument.
- Page size is fixed at 4096 bytes.
- Input is assumed to be a valid positive integer.
*/

