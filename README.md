# 16-bit Multiplier Accumulator Unit (MAC) in Verilog

## Project Overview
This project implements a 16-bit Multiplier Accumulator Unit (MAC) using Verilog. The design includes a Wallace tree radix-4 Booth multiplier and operates at a frequency of 150 MHz.

## Specifications
- **Multiplier and Multiplicand:**
  - 1 sign bit
  - 3 integer bits
  - 12 fractional bits
- **Accumulator:**
  - 1 sign bit
  - 16 integer bits
  - 11 fractional bits

## Design Details
- **Multiplier Type:** Wallace tree radix-4 Booth multiplier
- **Operating Frequency:** 150 MHz

## Tools Used
- **Synthesis:** Cadence Genus
- **Place and Route:** Cadence Innovus
- **Simulation:** ModelSim

## Synthesis Results
- **Area:** 5186.52 µm²
- **Timing Analysis:**
  | Timing Stage | Hold Slack | Setup Slack |
  |--------------|------------|-------------|
  | Pre-CTS      | +0.042 ns  | +0.061 ns   |
  | Post-CTS     | +0.006 ns  | +0.042 ns   |

## Verification
- No DRC (Design Rule Check) violations
- No LVS (Layout Versus Schematic) violations

## Project Files
The repository contains the following files:
- Verilog source code
- Timing analysis reports (Check [Project_Report.pdf](docs/Project_Report.pdf) in docs)
- Documentation (Check [Project_Report.pdf](docs/Project_Report.pdf) in docs)

## Getting Started
To clone and run this project, use the following commands:
```bash
git clone https://github.com/rahulk200013/mac-16bit-verilog.git
