Ananya K M</p>
**A 4-week Research Internship on RISC-V using VSDSquadron Mini RISC-V Dev Board**</p>

task 1</p>
1.#To install git </p> sudo apt install git-all</p>
sudo apt-get install autoconf automake autotools-dev curl python3 libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev 
![WhatsApp Image 2024-02-21 at 2 52 14 PM (1)](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/7bdb07fa-2027-4bff-ace5-199552eb6984)
 git clone https://github.com/riscv/riscv-gnu-toolchain</p>
 ![WhatsApp Image 2024-02-21 at 2 52 14 PM (3)](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/9412c67c-b04f-4200-a6ae-455e8bfdcfab)
 Create a opt dir
mkdir /opt/riscv  try sudo incase of permission denial</p>

create a driectory mkdir riscv and chmod 777 home/ananya/riscv

Config and make inside the risc-v gnu toolchain dir
./configure --prefix=/opt/riscv

In my case ./configure --prefix=/home/ananya/riscv

Then make </p>
![WhatsApp Image 2024-02-21 at 2 52 14 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/be231609-945a-43a8-9cb8-250138af59c2)


INSTALLING IVERILOG GTKWAVE & YOSYS</p>
YOSYS</p>

![WhatsApp Image 2024-02-21 at 2 52 17 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/cd901b86-4a4f-49e1-a564-378d9329c4e9)
![WhatsApp Image 2024-02-21 at 2 52 25 PM (1)](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/14b3f301-8022-443f-99b5-420e6c5dd429)

iVerilog</p>
sudo apt-get install iverilog</p>
![WhatsApp Image 2024-02-21 at 2 52 26 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/f874e977-c3d6-44ff-83bf-db344f212b0a)

GTkWave</p>
sudo apt-get install gtkwave

![WhatsApp Image 2024-02-21 at 2 52 27 PM](https://github.com/Ananya-KM/Ananya-KM/assets/160317297/54b2d75b-41a5-465e-b04c-38d4b8899f5c)



