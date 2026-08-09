# ROM (Read Only Memory) Using Verilog HDL

## Overview

This project implements a simple ROM (Read Only Memory) using Verilog HDL. ROM is a non-volatile memory device used to store fixed data that can only be read during operation.

## Features

* 8-bit data width
* 3-bit address input
* Predefined memory contents
* Combinational read operation
* Verilog testbench for verification

## Files

* `rom.v` – ROM design module
* `rom_tb.v` – Testbench file
* `simulation_results.png` – Simulation waveform screenshot

## Memory Map

| Address | Data |
| ------- | ---- |
| 000     | 0x11 |
| 001     | 0x22 |
| 010     | 0x33 |
| 011     | 0x44 |
| 100     | 0x55 |
| 101     | 0x66 |
| 110     | 0x77 |
| 111     | 0x88 |

## Tools Used

* Verilog HDL
* ModelSim
* Icarus Verilog
* GTKWave

## Simulation Procedure

1. Compile `rom.v` and `rom_tb.v`.
2. Run the simulation.
3. Open the waveform viewer.
4. Verify the output data for each address.
5. Compare results with the memory map.

## Applications

* Microcontroller Firmware Storage
* Lookup Tables (LUTs)
* FPGA Designs
* Embedded Systems
* Digital Signal Processing

## Results

The ROM successfully outputs the predefined data corresponding to each input address, demonstrating correct read-only memory functionality.

## Author

Akula Rajini Yadav

B.Tech – Electronics and Communication Engineering (ECE)
