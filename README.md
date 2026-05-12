# Adaptive-FIR-filter-using-LMS-algorithm

## Project Description
This project implements a 10-tap Adaptive FIR Filter using the LMS algorithm in Verilog HDL for FPGA-based real-time signal processing. The design uses CLA adders, pipelined multipliers, and shift register delay elements to achieve high speed and efficient hardware utilization.

## Features
- 10-tap adaptive FIR filter
- LMS coefficient adaptation
- 16-bit architecture
- High-speed CLA adder
- Pipelined multiplier
- FPGA optimized design

## Tools Used
- Verilog HDL
- Xilinx Vivado 2018.2
- MATLAB


## Equations

FIR Output:
y(n) = Σ h(k)x(n-k)

Error Equation:
e(n) = d(n) - y(n)

LMS Update:
h(n+1) = h(n) + μx(n)e(n)


