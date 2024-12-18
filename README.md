# Pipelined_Single_Cycle_Implementation

**Project Overview**
This project implements a pipelined single-cycle processor for the RISC-V instruction set architecture (ISA) using Verilog. The implementation provides a detailed, modular approach to designing a basic RISC-V processor with pipeline stages.

**Features**

Full support for RISC-V RV32I base integer instruction set
5-stage pipeline implementation:

Instruction Fetch (IF)
Instruction Decode (ID)
Execute (EX)
Memory Access (MEM)
Write Back (WB)


Comprehensive hazard handling
Configurable data and instruction memory
Support for arithmetic, logical, and control flow instructions

**Supported Instructions**
The processor supports the following RISC-V RV32I instructions:

Arithmetic: ADD, ADDI, SUB
Logical: AND, ANDI, OR, ORI, XOR, XORI
Shift: SLL, SLLI, SRL, SRLI, SRA, SRAI
Load/Store: LW, SW
Branch: BEQ, BNE, BLT, BGE
Jump: JAL, JALR

**Hazard Handling**
The implementation includes mechanisms for:

Structural Hazards
Data Hazards
Control Hazards
Forwarding and stalling logic

**Performance Characteristics**

Clock Frequency: Configurable
CPI (Cycles Per Instruction): Approximately 1
Memory Bandwidth: Configurable

**Limitations**

Implements base RV32I instruction set
No floating-point or extended instruction support
Simplified branch prediction

**Future Improvements**

Add support for floating-point instructions
Implement more advanced branch prediction
Optimize critical path
Add cache memory implementation
