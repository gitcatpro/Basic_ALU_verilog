# Basic_ALU_verilog
# 4-Bit Arithmetic Logic Unit (ALU) – Verilog

## Overview
This project implements a 4-bit Arithmetic Logic Unit (ALU) using Verilog HDL.  
The ALU performs basic arithmetic and logical operations and is verified using a testbench simulation.

## Operations Supported
The ALU supports the following operations based on a 3-bit select input (sel):

| sel | Operation        |
|-----|------------------|
| 000 | Addition (A + B) |
| 001 | Subtraction (A - B) |
| 010 | Bitwise AND      |
| 011 | Bitwise OR       |
| 100 | Bitwise XOR      |
| 101 | Bitwise NOT (A)  |

## Design Details
- 4-bit inputs: A and B  
- 3-bit control signal: sel  
- 4-bit output: result  
- Carry output for arithmetic operations  
- Implemented using combinational always block with case statement  

## Simulation
The design was verified using a Verilog testbench.  
Simulation confirms correct functionality for all supported operations.

Example Test Case:
A = 0101 (5)  
B = 0011 (3)

Results:
- Addition → 1000  
- Subtraction → 0010  
- AND → 0001  
- OR → 0111  
- XOR → 0110  
- NOT → 1010  

## Tools Used
- Verilog HDL  
- Icarus Verilog  
- EDA Playground  

## Author
Nayasa Seth  
B.Tech, Electronics & Communication Engineering  
Banasthali Vidyapith
