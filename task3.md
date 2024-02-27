**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****
![WhatsApp Image 2024-02-24 at 8 31 34 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/c2539fc5-cd4c-4c95-addb-b9e0d98418a7)


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![Leafpad_editor]![WhatsApp Image 2024-02-24 at 8 31 34 PM (1)](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/369a9ebf-478c-4ea2-8f18-0f3561338566)


**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**
![WhatsApp Image 2024-02-24 at 8 31 33 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/94876e45-2a5b-43a9-b08d-53f99b542d3c)

**gcc sum1ton.c**
**Step 5: Check the output by using the command**
**./a.out**

![WhatsApp Image 2024-02-24 at 8 31 33 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/8c03ce0f-806d-49c9-adac-efa344d8d9f0)

**The results will be displayed as** 

**Sum of numbers from 1 to 5 is 15**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![view in the C code in notepad]

![WhatsApp Image 2024-02-27 at 10 19 33 AM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/7e0d36ae-cadb-4e46-8892-536e392749a0)

**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![WhatsApp Image 2024-02-27 at 10 19 33 AM (1)](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/95a198d2-b7a7-44ae-84a0-f2504a31c904)


![WhatsApp Image 2024-02-27 at 10 16 51 AM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/f11114a5-c0fa-4c81-892b-dc4e011d7fb3)



**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**


![WhatsApp Image 2024-02-27 at 10 16 51 AM (1)](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/4217c854-3fa5-4e6d-8fe7-802d66800891)


![WhatsApp Image 2024-02-27 at 10 16 50 AM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/6262431b-2115-445d-83be-50d13e8cacc7)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**


![WhatsApp Image 2024-02-27 at 10 16 50 AM (1)](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/765d2f24-1897-4900-80e6-613ed714e550)


![WhatsApp Image 2024-02-27 at 10 16 49 AM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/4994ce85-ce5d-4a3a-9a1d-c85feab12778)

