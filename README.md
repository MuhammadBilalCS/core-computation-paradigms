# Foundations of Digital Systems

> *Bridging the gap between abstract computation, hardware design, and low-level software.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤%20-red)](https://github.com)

##  Overview

This repository serves as a comprehensive lab notebook and implementation hub for the three core pillars of computer engineering:

1. **Theory of Automata (TOC)** – Exploring Finite Automata and Turing Machines.
2. **Digital Logic Design (DLD)** – Solving realistic hardware problems using logic gates.
3. **Assembly Programming** – Handling complex data types (like floating-point numbers) at the bit level.

Whether you are a student preparing for exams or an engineer revisiting fundamentals, this repo contains documented solutions, visual simulations, and executable code.

---------------------------------------------------------------------------------------------------------------------------------


---

##  1. Theory of Automata (TOC)

### Deterministic Finite Automata (DFA)
- **Content**: A curated set of DFA problems focusing on language acceptance, string patterns, and state minimization.
- **Visuals**: Every DFA solution is accompanied by high-quality images generated using industry-standard simulators (e.g., JFLAP, Automata Tutor). Check the `/automata/dfa/simulator-images` folder for visual representations of states, transitions, and acceptance paths.

### Turing Machines
- **Content**: Implementation of fundamental arithmetic operations using Turing Machines.
- **Included Algorithms**:
  - **Adder**: Performs binary/unary addition.
  - **Subtractor**: Executes binary subtraction using complement logic.
  - **Incrementer / Decrementer**: Demonstrates sequential state changes for ±1 operations.
- **Format**: State-transition tables and `.tm` files compatible with standard TOC simulators.

---

##  2. Digital Logic Design (DLD)

### Logic Gate Solutions
- **Objective**: Bridge theoretical Boolean algebra with practical hardware.
- **Content**: Step-by-step solutions to realistic digital circuit problems—from designing a simple alarm system to constructing multiplexers and encoders.
- **Interfaces**: Focus on both **combinational** (adders, comparators) and **sequential** (flip-flops, counters) circuits. All designs are rendered using standard logic gate symbols (AND, OR, NOT, NAND, NOR, XOR).

### Key Features
- Simplified truth tables and Karnaugh Maps (K-Maps).
- Optimized gate-level implementations to minimize chip usage.

---

##  3. Assembly Language (Low-Level Programming)

### Floating-Point Handling
- **Challenge**: High-level languages abstract floating-point arithmetic. This section dives into the **IEEE 754 standard** to understand how real numbers are stored and manipulated in memory.
- **Codebase** (`/assembly/floating-point`):
  - **Conversion**: Assembly routines to convert decimal numbers into 32-bit/64-bit IEEE 754 binary representation.
  - **Arithmetic**: Addition and subtraction of floating-point numbers using bitwise operations and integer arithmetic units.
  - **Environment**: Written for x86/8086 architectures (MASM/NASM compatible), with detailed comments explaining register usage and stack management.

---

##  Prerequisites & Tools

To run or visualize the contents of this repository, you may need the following:

| Component          | Recommended Tools                                                                 |
|--------------------|-----------------------------------------------------------------------------------|
| **Automata**       | [JFLAP](https://www.jflap.org/), [Turing Machine Simulator](https://mikecoon.org/turing-machine-simulator/) |
| **DLD / Circuits** | [Logisim](http://www.cburch.com/logisim/), [Digital](https://github.com/hneemann/Digital) |
| **Assembly**       | MASM (DOSBox), NASM (Linux/WSL), or any x86 debugger (GDB)                        |

---

