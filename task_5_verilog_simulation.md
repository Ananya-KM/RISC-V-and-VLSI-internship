# As per the Update given for the next task "Should Use the RISC-V Core Verilog netlist and testbench for functional Simulation.
# Veriog code is being executed and the waveforms are generated using the gtkwave

# Aim: To verify the Functional Simulation:-
# Table of contents
- [1.RISC-V RV32I](#1-RISC-V-RV32I)
 - [2.BLOCK DIAGRAM OF RISC-V RV32I](#2-BLOCK-DIAGRAM-OF-RISC-V-RV32I)
 - [3.INSTRUCTION SET OF RISC-V RV32I](#3-INSTRUCTION-SET-OF-RISC-V-RV32I)
 - [4.FUNCTIONAL SIMULATION](#4-FUNCTIONAL-SIMULATION)
    - [4.1 About iverilog and gtkwave](#41-About-iverilog-and-gtkwave)
    - [4.2 Installing iverilog and gtkwave](#42-Installing-iverilog-and-gtkwave)
    - [4.3 The output waveform](#43-The-output-waveform)
  
   ## 1. RISC-V RV32I

This project provides an insight into the working of a few important instructions of the instruction set of a Single cycle Reduced Instruction Set Computer - Five(RISC-V) Instruction Set Architecture suitable for use across wide-spectrum of Applications from low-power embedded devices to high-performance Cloud-based Server processors. The base RISC-V is a 32-bit processor with 31 general-purpose registers, so all the instructions are 32-bit long. Some Applications where the RISC-V processors have begun to make some significant threads are in Artificial intelligence and machine learning, Embedded systems, ultra-low power processing systems, etc.

## 2. BLOCK DIAGRAM OF RISC-V RV32I
![1](https://github.com/Abdulbitm/Abdul/assets/160620896/ba781b31-81bb-4003-9b93-cff8f7825d9a)

## 3. INSTRUCTION SET OF RISC-V RV32I
![2](https://github.com/Abdulbitm/Abdul/assets/160620896/9b986703-34be-4527-8558-1e2cea21f4f9)


![3](https://github.com/Abdulbitm/Abdul/assets/160620896/0b2e2308-186c-4f70-9081-54ff8b3190ca)

## 4. FUNCTIONAL SIMULATION

### 4.1 About iverilog and gtkwave
- Icarus Verilog is an implementation of the Verilog hardware description language.
- GTKWave is a fully featured GTK+ v1. 2 based wave viewer for Unix and Win32 which reads Ver Structural Verilog Compiler generated AET files as well as standard Verilog VCD/EVCD files and allows their viewing.
  
### 4.2 Installing iverilog and gtkwave

- **For Ubuntu**

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 ```
![WhatsApp Image 2024-03-02 at 2 16 08 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/7db9c30b-48b8-466c-ab2c-d42d63adacdb)



- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**

 ```
 $ git clone https://github.com/AnanyaKM/AnanyaKM
 
```
![WhatsApp Image 2024-03-02 at 2 15 36 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/fe7fb60f-7adf-48d6-bda5-8cde09d2b82a)


- **To simulate and run the Verilog code, enter the following commands in your terminal.**

```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello

```

![WhatsApp Image 2024-03-02 at 2 18 30 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/3eec8e32-84ef-4658-b7a9-2c5cc3d3b5e6)



- **To see the output waveform in gtkwave, enter the following commands in your terminal.**

`$ gtkwave hello.vcd`


![WhatsApp Image 2024-03-02 at 2 18 19 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/b3b73f1f-aac7-4703-88c0-a731c8eb77e8)



### 4.3 The output waveform

 The output waveform showing the instructions performed in a 5-stage pipelined architecture.
 
![WhatsApp Image 2024-03-02 at 2 18 31 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/19479e1e-3812-47b8-a5e0-3271f86bad0e)


![WhatsApp Image 2024-03-02 at 2 18 01 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/980520eb-1c58-48b2-9350-42cd17b15e89)


