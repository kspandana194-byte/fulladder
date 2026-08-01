# 1-Bit Full Adder using Verilog

## Project Description
This project implements a **1-bit Full Adder** using Verilog HDL. A Full Adder adds three binary inputs:
- A
- B
- Cin (Carry Input)

It produces:
- Sum
- Cout (Carry Output)

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|

## Logic Equations

Sum  = A ^ B ^ Cin

Cout = (A & B) | (B & Cin) | (A & Cin)

## Files

- `full_adder.v` – Verilog design
- `full_adder_tb.v` – Testbench
- `simulation.png` – Simulation waveform

## Software Used

- ModelSim / Vivado / Xilinx ISE / GTKWave

## Expected Output

The simulation verifies that the Full Adder produces the correct Sum and Carry for all eight input combinations.

## Author

Your Name