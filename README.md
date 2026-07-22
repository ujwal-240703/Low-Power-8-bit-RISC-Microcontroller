# Low-Power-8-bit-RISC-Microcontroller
Design and Verification of a Synthesizable Low-Power 8-bit RISC Microcontroller using Verilog HDL with Clock Gating, Power Gating, and Dynamic Voltage Scaling (DVS). Simulated using Xilinx ISE and synthesized using Cadence Genus.

# Design and Verification of a Synthesizable Low-Power 8-bit RISC Microcontroller

## Overview

This project presents the design, implementation, synthesis, and verification of a synthesizable low-power 8-bit RISC microcontroller. The processor is designed for embedded and battery-powered applications where power efficiency is a major concern.

The architecture follows the Reduced Instruction Set Computer (RISC) philosophy, using a compact instruction set and simple control logic to achieve efficient execution while minimizing hardware complexity.

To further reduce power consumption, three low-power design techniques are implemented:

- Clock Gating
- Power Gating
- Dynamic Voltage Scaling (DVS)

The complete design is developed in Verilog HDL, simulated using Xilinx ISE 14.2, and synthesized using Cadence Genus.

---

## Features

- 8-bit RISC Architecture
- 4-bit Opcode Instruction Set
- 16 Instructions
- 8-bit ALU
- Program Counter
- Control Unit
- Instruction Register
- Memory Address Register
- SRAM
- Register File
- Ring Counter Based Control Logic
- Sequential Instruction Execution
- Clock Gating
- Power Gating
- Dynamic Voltage Scaling (DVS)
- RTL Simulation
- ASIC Synthesis
- Power Analysis

---

## Processor Specifications

| Specification | Value |
|--------------|-------|
| Architecture | 8-bit RISC |
| Data Width | 8-bit |
| Address Width | 4-bit |
| Memory | 16 × 8 SRAM |
| Instruction Width | 8-bit |
| Opcode Width | 4-bit |
| Pipeline | Sequential (Ring Counter Based) |
| Instruction Count | 16 |
| ALU Operations | Arithmetic and Logic |

---

## Instruction Set

| Opcode | Instruction |
|---------|-------------|
|00H|LDA|
|01H|ADD|
|02H|SUB|
|03H|AND|
|04H|OR|
|05H|XOR|
|06H|NOT|
|07H|SHL|
|08H|SHR|
|09H|MUL|
|0AH|DIV|
|0BH|INC|
|0CH|DEC|
|0DH|CMP|
|0EH|OUT|
|0FH|HLT|

---

## Architecture

The microcontroller consists of the following modules:

- Arithmetic Logic Unit (ALU)
- Control Unit
- Program Counter
- Memory Address Register
- Instruction Register
- SRAM
- Register File
- Ring Counter
- Accumulator
- Output Register

Each module was individually verified before full system integration.

---

## Low Power Techniques

### Clock Gating

Disables the clock signal to inactive modules, reducing unnecessary switching activity and dynamic power consumption.

### Power Gating

Disconnects inactive blocks from the power supply to reduce leakage power.

### Dynamic Voltage Scaling (DVS)

Adjusts the operating voltage based on workload to improve overall energy efficiency.

---

## Design Flow

1. RTL Design using Verilog HDL
2. Functional Simulation using Xilinx ISE
3. Module Verification
4. Top-Level Integration
5. RTL Synthesis using Cadence Genus
6. Power Optimization
7. Power Analysis
8. Performance Comparison

---

## Tools Used

- Verilog HDL
- Xilinx ISE 14.2
- Cadence Genus
- ASIC Design Flow



## Results

The implemented low-power techniques successfully reduced overall power consumption while maintaining functional correctness.

Comparative analysis was performed for:

- Base Design
- Clock Gating
- Power Gating
- Dynamic Voltage Scaling
- Combined Low-Power Techniques

Power reports generated using Cadence Genus demonstrate the effectiveness of these optimization methods.

---

## Applications

- Embedded Systems
- Internet of Things (IoT)
- Wearable Electronics
- Battery Powered Devices
- Educational Processor Design
- FPGA and ASIC Prototyping

---

## Future Scope

- 16-bit Processor
- 32-bit Processor
- Multi-stage Pipeline
- Cache Memory
- Interrupt Handling
- UART/SPI/I2C Interfaces
- FPGA Hardware Implementation
- Advanced Power Optimization
