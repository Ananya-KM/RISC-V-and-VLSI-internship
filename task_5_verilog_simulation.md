# As per the Update given for the next task "Should Use the RISC-V Core Verilog netlist and testbench for functional Simulation.
# Veriog code is being executed and the waveforms are generated using the gtkwave

# Aim: To verify the Functional Simulation:-

  
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


