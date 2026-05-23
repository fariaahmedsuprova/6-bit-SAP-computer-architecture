## Demo Video
[Watch Demo](https://youtu.be/yz37hjO9mIA?si=JJ6gpPwuq34-c18G)
**6-bit SAP Computer Architecture – Digital Logic Design & Functional Verification**

---

## Project Overview

This project focuses on the design and simulation of a complete **6-bit Simple-As-Possible (SAP) Computer Architecture** using digital logic principles in **Proteus**.

The CPU was built entirely from first principles, implementing the complete **fetch–decode–execute cycle** along with core processor components such as:

- Arithmetic Logic Unit (ALU)
- Program Counter (PC)
- Instruction Register (IR)
- Control Unit
- Memory and Bus System

The project demonstrates how low-level processor architecture works internally through datapath design, clock synchronization, and control signal generation.

---

## Development Environment

- **Simulation Software:** Proteus
- **Architecture Type:** 6-bit SAP CPU
- **Domain:** Digital Logic Design & Computer Architecture

---

## Features

- Complete 6-bit CPU implementation
- Fetch–Decode–Execute instruction cycle
- Arithmetic Logic Unit (ALU)
- Program Counter (PC)
- Instruction Register (IR)
- Shared bus architecture
- Register transfer operations
- Clocked synchronous system design
- Functional verification of all opcodes
- Control signal tracing and debugging

---

## Core Components

### Arithmetic Logic Unit (ALU)

Performs arithmetic and logical operations for instruction execution.

### Program Counter (PC)

Tracks and updates the address of the next instruction.

### Instruction Register (IR)

Stores the currently executing instruction.

### Control Unit

Generates timing and control signals for coordinated CPU operation.

### Bus System

Transfers data between registers, memory, and processing units.

---

## CPU Workflow

### 1. Fetch Cycle

The Program Counter retrieves the next instruction address from memory.

### 2. Decode Cycle

The Instruction Register decodes the opcode and determines required operations.

### 3. Execute Cycle

The ALU and datapath execute the instruction while control signals manage data flow.

---

## Functional Verification

The system was tested and verified across all implemented opcodes by tracing:

- Bus states
- Register values
- Timing sequences
- Control signals

This verification process closely resembles:

- Block-level digital IP verification
- Datapath validation
- Hardware debugging workflows

---

## Concepts Used

- Digital logic design
- Sequential circuits
- Clocked systems
- Finite state machines
- Datapath and control separation
- Register transfer operations
- Bus architecture
- Instruction cycle execution
- Functional verification
- Timing analysis

---

## Skills & Learning Outcomes

Through this project, the following concepts were explored deeply:

- CPU architecture fundamentals
- Processor datapath implementation
- State-machine based control logic
- Hardware-level debugging
- Verification methodology
- Synchronous digital system behavior

The project also strengthened understanding of concepts foundational to:

- SoC verification
- RTL design
- Digital IC verification
- Embedded processor architecture

---

## Verification Highlights

- Verified correct instruction execution for all opcodes
- Traced real-time register and bus behavior
- Analyzed timing and synchronization issues
- Validated control logic correctness under clocked operation

---

## Applications

This project serves as a strong foundation for understanding:

- Modern processor architecture
- Hardware verification workflows
- Digital system implementation
- Embedded computing systems
- FPGA and RTL development concepts

---

## Limitations

- Limited to 6-bit architecture
- Basic instruction set implementation
- Simulation-only environment
- No pipelining or cache architecture

---

## Conclusion

This project demonstrates the complete design and verification of a functional 6-bit SAP computer architecture using digital logic principles.

It combines:

- CPU architecture design
- Clocked digital systems
- Datapath implementation
- Functional verification
- Hardware debugging

The project provides practical insight into how processors operate internally and builds a strong foundation for advanced work in:

- Digital system design
- Computer architecture
- RTL development
- SoC verification
- Embedded hardware engineering
