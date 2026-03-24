## MIPS Assembler: Label Table & Pass 1
This project implements the core logic for the first pass of a MIPS assembler, focusing on Label Table (Symbol Table) management and label parsing.

## Features
Dynamic Label Table: Implemented using an ArrayList that automatically resizes as needed.

Pass 1 Simulation: Parses labels from MIPS assembly files and calculates memory addresses.

Robust Error Handling: Detects and reports duplicate labels.

Memory Efficient: Supports both static and dynamic label allocation.

How to Build
To compile all test drivers and the assembler components, simply run:

make all

## How to Run
The project includes two primary test drivers:

## 1. Label Table Unit Test
Verifies the internal logic of the label table (adding, searching, and resizing).

./testLabelTable
## 2. Pass 1 Label Parser (Test with Your Own Files)
To process your own MIPS assembly file and view the generated label table:

./testPass1 <your_file>.mips
Note: Ensure your .mips file uses standard label syntax (e.g., main:, loop:).
