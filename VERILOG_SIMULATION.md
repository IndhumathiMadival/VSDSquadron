As per the Update given for the next task "Should Use the RISC-V Core Verilog netlist and testbench for functional Simulation.
Veriog code is being executed and the waveforms are generated using the gtkwave
Aim: To verify the Functional Simulation:-
Table of contents
1.RISC-V RV32I

2.BLOCK DIAGRAM OF RISC-V RV32I

3.INSTRUCTION SET OF RISC-V RV32I

4.FUNCTIONAL SIMULATION

4.1 About iverilog and gtkwave
4.2 Installing iverilog and gtkwave
4.3 The output waveform

1. RISC-V RV32I
   
This project provides an insight into the working of a few important instructions of the instruction set of a Single cycle Reduced Instruction Set
Computer - Five(RISC-V) Instruction Set Architecture suitable for use across wide-spectrum of Applications from low-power embedded devices
to high-performance Cloud-based Server processors. The base RISC-V is a 32-bit processor with 31 general-purpose registers, so all the
instructions are 32-bit long. Some Applications where the RISC-V processors have begun to make some significant threads are in Artificial
intelligence and machine learning, Embedded systems, ultra-low power processing systems, etc.

2.BLOCK DIAGRAM OF RISC-V RV32I
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/ff24463c-8650-4186-ae2f-7cb7fa8d0ac8)


INSTRUCTION SET OF RISC-V RV32I

![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/5cdab503-621d-4321-a800-63948d3710d0)
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/4204d035-9112-4533-9310-65a4882801f8)

 FUNCTIONAL SIMULATION
4.1 About iverilog and gtkwave
Icarus Verilog is an implementation of the Verilog hardware description language.
GTKWave is a fully featured GTK+ v1. 2 based wave viewer for Unix and Win32 which reads Ver Structural Verilog Compiler generated AET files as well as standard Verilog VCD/EVCD files and allows their viewing.

4.2 Installing iverilog and gtkwave
For Ubuntu Open your terminal and type the following to install iverilog and GTKWave

$   sudo apt get update
$   sudo apt get install iverilog gtkwave

![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/e906db05-8adc-4b5b-bc8e-8fd62afe1d98)

To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.
$ git clone https://github.com/IndhumathiMadivalgithub/VSDSQUADRON-MINI/blob/main/README.md
$ cd indhu

![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/b17ab1e7-c46c-4094-9a00-ee8cd95602f4)

To simulate and run the Verilog code, enter the following commands in your terminal.

$ iverilog -o hello hello.v hello_tb.v

$ ./hello

![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/c92ef55b-0878-4ec2-adff-3fb0193f9c29)
To see the output wave orm in gtkwave, enter the following commands in your terminal. $ gtkwave hello.vcd

![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/fa7f5675-8de7-44e4-963d-e522a22166f8)

4.3 The output waveform The output waveform showing the instructions performed in a 5-stage pipelined architecture.

Instruction 1:add r6,r2,r2
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/90ac070d-0d08-4709-8cc5-4f933bfa0588)
Instruction 2:sub r7,r1,r2 
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/5fb5cab7-d50c-496c-8270-537c6cb8f345)
 
 Instruction 3:and r8,r1,r3
 ![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/aae9d9d3-f9e6-4d82-bd44-29b831874698)
Instruction 4:or r9,r2,r5
 ![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/ac17bccd-c3f5-41de-94e9-9d1b369f8c84)
Instruction 5:xor r10,r1,r4
 ![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/e33dbdfa-e826-4a9c-9ca0-6f215096b214)
Instruction 6:slt r11,r2,r4
 ![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/6e80bd16-23f1-4b3a-8840-f265966ddad3)
Instruction 7:addi r12,r4,5
 ![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/18393ae1-2ce9-46f4-a33e-80b180a30c48)
Instruction 8:sw r3,r1,2
 ![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/91f2edff-e25a-471e-81b1-7d711a12e5af)
Instruction 9:lw r13,r1,2
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/3d6506bb-f12b-4c9e-b0cd-72bd741aa43e)
Instruction 10:beq r0,r0,15
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/d4ab1dbb-9e21-4ef3-977d-eccbf7146ccd)
After branching, performing Instruction 11:add r14,r2,r2
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/d6d710fe-ae4f-4bb4-b1ee-6c0d90c8880b)

Full 5-stage instruction pipeline and pc-increment description Waveform
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/c670507e-f67c-458e-b47b-698eba6d3061)
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/4d7298c8-ef1f-4c10-95d0-3f2dca83fba6)
![image](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/69805f4a-acd0-4310-9ea9-6feda1cf9d95)





















