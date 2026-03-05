# RISC-V 32-bit

A simple 32-bit RISC-V processor implementation written in **Verilog/SystemVerilog**, designed for educational and research purposes.  
This project focuses on understanding the internal architecture of a RISC-V CPU, including datapath design, control logic, and key hardware components such as the register file, ALU, and instruction decoder.

The processor follows the **RV32I base integer instruction set architecture** defined by RISC-V.

---

## 📖 Introduction

RISC-V is an open standard instruction set architecture (ISA) that has gained significant attention in academia and industry due to its simplicity, extensibility, and openness.

This project implements a basic RISC-V CPU to explore:

- Computer architecture fundamentals
- Hardware design using SystemVerilog
- CPU datapath and control logic
- Implementation of the RV32I instruction set

The processor is designed as a learning platform for understanding how modern processors work internally.

---

## 🏗 Architecture Overview

The processor is based on the RISC-V **RV32I ISA** and includes the following core components:

- Program Counter (PC)
- Instruction Memory
- Register File (32 × 32-bit registers)
- Arithmetic Logic Unit (ALU)
- Control Unit
- Immediate Generator
- Data Memory
- Multiplexers and Control Signals

### Datapath Structure

The datapath coordinates instruction fetch, decode, execution, memory access, and write-back operations.

Typical instruction flow:

1. Instruction Fetch  
2. Instruction Decode  
3. Execute (ALU)  
4. Memory Access  
5. Write Back

---

## 📂 Project Structure
