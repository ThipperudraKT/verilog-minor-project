# Verilog Minor Project

Unlox Academy, VLSI Design Program (September 2026 batch)

- **Student:** Thipperudra K T
- **Roll No.:** 4SM23EE037
- **Instructor:** Kuldeep Sompura
- **Date:** 31 October 2026

## Contents

| Part | Topic | Where |
|------|-------|-------|
| Part 1 | Verilog Data Types | `Thipperudra_KT_Verilog_Minor_Project_Parts_1_to_3.pdf` |
| Part 2 | Lexical Tokens | `Thipperudra_KT_Verilog_Minor_Project_Parts_1_to_3.pdf` |
| Part 3 | Programming Assignments | `src/program1.v` to `src/program5.v` and the PDF |

## Programs

| File | Description |
|------|-------------|
| `src/program1.v` | Two reg variables assigned in an initial block, shown with `$display` |
| `src/program2.v` | Integer addition |
| `src/program3.v` | AND operation on a wire using `assign` |
| `src/program4.v` | `reg`, `integer` and `time` data types |
| `src/program5.v` | OR gate module with continuous assignment and testbench |

## Run with Icarus Verilog

```
iverilog -o p1 src/program1.v && vvp p1
iverilog -o p5 src/program5.v && vvp p5
```
