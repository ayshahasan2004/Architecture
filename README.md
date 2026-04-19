Pipelined RISC Processor in Verilog

This project presents the design and verification of a 32-bit pipelined RISC processor implemented in Verilog.
The processor includes 16 general-purpose registers, separate instruction and data memories, and a custom instruction set.
A 5-stage pipeline architecture is implemented: IF, ID, EX, MEM, and WB.
Supported instructions include arithmetic, logical, memory access, and control flow operations.
The design integrates hazard detection to handle data and control hazards efficiently.
Forwarding and stalling techniques are used to maintain correct execution flow.
The datapath and control unit are fully designed at RTL level.
Verification is performed using testbenches and simulation to ensure correctness.
Results confirm accurate execution of instructions and proper pipeline behavior.
This project demonstrates key concepts in computer architecture and digital design.# Architecture
