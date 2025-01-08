# samsung-riscv

# Task 1

![WhatsApp Image 2025-01-08 at 19 58 22_2f5673fd](https://github.com/user-attachments/assets/cbad160a-4182-4e25-b851-ac8a48acf9bf)

This image showcases a terminal session in Ubuntu where the user compiles and executes a C program named sum1ton.c.

Compilation: The gcc compiler is used to compile the sum1ton.c file, resulting in the executable a.out.

First Execution: The executable is run, calculating the sum of numbers from 1 to 10, which is displayed as 55.

Recompilation and Second Execution: The program is recompiled, and the executable is run again, this time calculating the sum of numbers from 1 to 9535, which is displayed as 45462880.

This demonstrates the process of compiling and running a program as well as how program input/output changes based on different parameters.

![WhatsApp Image 2025-01-08 at 19 58 22_b4bea782](https://github.com/user-attachments/assets/e8907208-ce22-49d3-a4cd-a7a7e1052f43)


# Task 2

This image displays the disassembled assembly code of a compiled C program, showing the instructions generated for the RISC-V instruction set architecture.

<main>: Contains the main logic of the program.
  
Instructions for initializing the stack pointer (sp), performing arithmetic operations, and function calls like printf.

<atexit>:Responsible for registering cleanup functions to be executed at the program's termination.

Includes simple move (mv) and jump (j) instructions.

<exit>: Final cleanup and termination routine.
Invokes any registered functions for resource deallocation and system restoration.
