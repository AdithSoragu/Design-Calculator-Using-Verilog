# Design of a Calculator Using Verilog

This repository contains the hardware description and implementation of a digital calculator using **Verilog HDL**. The design focuses on a modular architecture, separating the computational logic from the control flow to ensure scalability and efficient hardware synthesis.

## 🚀 Features
* **Arithmetic Operations:** Supports Addition, Subtraction, Multiplication, and Division.
* **8-bit Architecture:** Designed to handle 8-bit operands (parameterized for easy expansion to 16 or 32-bit).
* **FSM-Based Control:** Uses a Finite State Machine to manage operand input, operation selection, and result output.
* **Status Flags:** Real-time generation of Zero (Z), Carry (C), and Overflow (V) flags.

## 🏗️ Architecture
The project is structured into three main functional blocks:
1.  **ALU (Arithmetic Logic Unit):** The core module that performs the mathematical computations.
2.  **Control Unit:** Manages the state transitions and enables the correct operation based on the user opcode.
3.  **Data Path:** Handles the routing of data between input pins, internal registers, and the ALU.

## 🛠️ Tools Used
* **Language:** Verilog HDL
* **Simulation:** ModelSim

Developed as part of the [adithprojects](https://github.com/AdithSoragu/adithprojects) collection.
