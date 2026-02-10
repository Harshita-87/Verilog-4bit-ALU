# 32-bit ALU in Verilog

## Overview
This repository contains the RTL design and verification of a 32-bit Arithmetic Logic Unit (ALU) implemented using Verilog HDL. The design supports basic arithmetic and logical operations and generates standard status flags.

## Supported Operations
- AND
- OR
- ADD
- SUB

Operation selection is controlled using a 2-bit control signal.

## Design Details
- 32-bit combinational ALU
- Control-driven operation selection
- Status flags generated:
  - Carry
  - Zero
  - Negative
  - Overflow
- Written using synthesizable Verilog

## Verification
- Custom Verilog testbench
- Functional verification using multiple input combinations
- Output and flag behavior verified through waveform analysis
- Simulated using Xilinx Vivado

## Repository Structure
- `src/alu.v` – ALU RTL design
- `tb/alu_tb.v` – Testbench

## Tools
- Verilog HDL
- Xilinx Vivado
