# 🔥 4-Bit Arithmetic Logic Unit (ALU) using Verilog

## 📌 Project Overview

This project implements a 4-Bit Arithmetic Logic Unit (ALU) using Verilog HDL.

The ALU is a fundamental digital circuit used to perform arithmetic and logical operations based on a select/control signal.

The design was simulated and verified using a custom testbench in Xilinx Vivado.

---

## 🚀 Features

The 4-bit ALU supports multiple arithmetic and logical operations.

| Select | Operation |
|--------|-----------|
| `000`  | Addition (A + B) |
| `001`  | Subtraction (A - B) |
| `010`  | Bitwise AND |
| `011`  | Bitwise OR |
| `100`  | Bitwise XOR |
| `101`  | Bitwise NOT (~A) |
| `110`  | Left Shift (A << 1) |
| `111`  | Right Shift (A >> 1) |

---

## 🛠️ Tools & Technologies

- Verilog HDL
- Xilinx Vivado
- RTL Design
- Behavioral Simulation
- Testbench Verification

---

## 📂 Project Files

```text
4-bit-ALU-using-Verilog/
│
├── alu.v
├── alu_tb.v
├── waveform.png
├── rtl_schematic.png
└── README.md
