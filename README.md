# SPI Controller

This repository contains a Verilog implementation of an SPI Master
controller developed as part of my FPGA/VLSI internship.

## Overview
The SPI controller supports basic serial communication between
a master and slave device using the SPI protocol.

## Features
- SPI Master
- 8-bit data transfer
- Configurable clock divider
- Supports CPOL and CPHA
- Simple testbench for verification

## Folder Structure
rtl/  - Verilog source files  
tb/   - Testbench files  
docs/ - Notes and diagrams  

## Tools Used
- Verilog HDL
- ModelSim / Vivado

## Future Work
- Add FIFO buffering
- Integrate with AXI bus
- Use in RISC-V SoC
