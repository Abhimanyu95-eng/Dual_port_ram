# Dual_port_ram
Overview:
This project implements a 64x8 Dual-Port RAM using Verilog and is tested on Xilinx Vivado.
The RAM has two independent ports (A & B) that can read and write simultaneously at different addresses.

Files:
Ram.v → Dual-Port RAM design file.
Ram_tb.v → Testbench file.

Features:
Memory size: 64 x 8 bits.
Independent Port A and Port B.
Synchronous read/write operations with clock.
Tested in Vivado Simulator.

Steps to Run (Vivado):
Open Vivado → Create New Project → Add Ram.v and Ram_tb.v.
Set Ram_tb as the top module for simulation.
Run Behavioral Simulation.
Open the waveform window to check:
Write/Read on Port A
Write/Read on Port B
Concurrent operations on both ports

Testbench Verification:
The testbench checks:
Write → Read operations on Port A
Write → Read operations on Port B
Concurrent write to different addresses
Concurrent read from different addresses
