# RISC-V Single-Cycle Processor (RV32I)

A 32-bit **RISC-V (RV32I) Single-Cycle Processor** implemented in **Verilog HDL**. This project demonstrates the complete processor design flow, including RTL design, functional simulation, synthesis, and FPGA implementation.

## Features

* 32-bit RV32I architecture
* Single-cycle processor design
* Modular Verilog implementation
* ALU, Register File, Control Unit, Immediate Generator
* Instruction and Data Memory
* Branch and Jump support
* Functional verification using testbenches
* FPGA implementation on Basys3

## Project Structure

```
├── processor.v
├── PC.v
├── PC_adder.v
├── register_file.v
├── instruction_mem.v
├── data_memory.v
├── ALU.v
├── ALU_control_unit.v
├── main_control_unit.v
├── imm_gen.v
├── mux.v
├── mux4to1.v
└── testbench/
```

## Tools Used

* Verilog HDL
* Xilinx Vivado


## Applications

This project is intended for learning:

* Computer Architecture
* Digital Logic Design
* Verilog HDL
* FPGA Design
* RTL Synthesis
* VLSI Design Flow

## Future Improvements

* Five-stage pipelined processor
* Hazard detection and forwarding
* Cache memory integration
* Branch prediction
* Additional RISC-V ISA extensions

## License

This project is intended for educational and learning purposes.
