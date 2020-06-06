# RISC V RV32I verilog implementation

This project is an implementation for the pipelined processor/datapath. It includes the five stages of the pipeline and a working forwarding unit. It also includes a data path

This working implementation includes all RV32I instructions except for CRS and FENCE instructions. It also includes all compressed "C" instructions that expand to RV32I instruction.

The datapath features a single unified memory in place of two independant memory memories designated to instructions and data.
