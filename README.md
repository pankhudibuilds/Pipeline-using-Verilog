# Pipeline-using-Verilog
32-bit MIPS32 RISC Processor in Verilog

This project implements a 32-bit MIPS32 RISC processor using Verilog HDL, designed with a 5-stage pipelined architecture to improve instruction throughput and execution efficiency. The processor follows the standard pipeline stages: Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), Memory Access (MEM), and Write Back (WB).

Key Features

Supports arithmetic, logical, memory (LW/SW), and branch instructions.

Includes a 32 × 32-bit register file for efficient data storage and access.

Implements two-phase clocking to enhance operational stability.

Designed with a modular hardware architecture, making the processor easier to extend and debug.

Design Approach

The processor is structured using modular Verilog components, including the ALU, register file, control unit, and pipeline stages. This modular design allows each unit to be tested and verified independently before integrating the complete processor.
