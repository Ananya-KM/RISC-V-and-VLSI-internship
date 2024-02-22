# Let's learn various types of RISC-V instructions
<p align="justify">RISC-V instructions are encoded using a fixed-length 32-bit format, which simplifies decoding and execution. The instruction formats are categorized into six types: R, I, S, B, U, and J. Each format serves a specific purpose and has a unique encoding structure:</p>

<details>
<summary><b>R-type instructions:
</b></summary>
<br>
<p align="justify">R-type instructions are a category of instructions in computer architectures, particularly in the RISC-V instruction set architecture, where they are commonly used for register-to-register operations. These instructions typically include three register operands: two source registers and one destination register. Eg:- add (Add 2 registers and store results in another)</p>
  </details>
<details>
<summary><b>I-type instructions:
</b></summary>
<br>
<p align="justify">I-type instructions are utilized for store operations in computer architectures, particularly within the RISC-V instruction set architecture, where they facilitate storing data from a register to memory. These instructions encompass two register operands and a 12-bit immediate value utilized as the memory address offset.  Eg:- li (Load immediate value)</p>
  </details>
<details>
<summary><b>S-type instructions:
</b></summary>
<br>
<p align="justify">S-type instructions in RISC-V architecture facilitate store operations by transferring data from a register to memory. They involve two register operands and a 12-bit immediate value for the memory address offset Eg:- sw (store the value in register)</p>
  </details>
<details>
<summary><b>B-type instructions:
</b></summary>
<br>
<p align="justify">B-type instructions in RISC-V architecture execute conditional branch operations, altering control flow based on a condition. They comprise two register operands and a 12-bit immediate value for the branch target address.. Eg:- beq (compare and label)</p>
  </details>
<details>
<summary><b>U-type instructions:
</b></summary>
<br>
<p align="justify">U-type instructions in RISC-V architecture manage operations with a 20-bit immediate value, like loading a 20-bit constant into a register or setting the upper 20 bits of a register.
 Eg:- lui (load upper immediate value)</p>
  </details>
<details>
<summary><b>J-type instructions:
</b></summary>
<br>
<p align="justify">J-type instructions in RISC-V architecture execute unconditional jump operations, transferring control to a different instruction unconditionally. They consist of one register operand and a 20-bit immediate value for the jump target address.. Eg:- J (jump)</p>
</details>

# Base Instructions Format

<p align="justify">In RISC-V, the base instruction format is a 32-bit instruction word divided into several fields. The basic format consists of opcode, rd (destination register), funct3 (function 3), rs1 (source register 1), imm (immediate value), and funct7 (function 7). This design allows for a wide range of instructions while maintaining simplicity and flexibility, which are key principles of the RISC-V architecture.</p>

<details>
<summary><b>Instruction code format </b></summary>
	<br>
![instruction code formats]![WhatsApp Image 2024-02-22 at 12 49 06 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/f22e20a2-184e-4add-b06a-9849c623a74b)

</details>


# RISC-V REGISTER FILE: 
 <p align="justify">The RISC-V register file is a key component of the RISC-V architecture, providing a set of storage locations for holding data during the execution of instructions. The register file is organized into a set of integer registers and floating-point registers, depending on the extensions implemented in the processor. Registers play a crucial role in the RISC-V architecture, as they enable fast access to data and help improve the performance and efficiency of the processor.</p>
