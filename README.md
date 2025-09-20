# RISC-V-Tapeout-chip-program-week-0-
Welcome to my journey of RISC-V  this program deals with design , verification and tapeout of a custom processsor based on open source RISC-V instruction set . week-0 contains the design flow of an SoC. the design flow starts with the C level program which is further converted into RTL Level then sub divided into processor and peripherals/IPs.this is the basic SoC design flow which is used to obtain the the GDSII 
# intallation of tools 
   1) yosys
   2) Iverilog
   3) GTKWAVE
# Resizing ubuntu 
$ sudo apt update 

$ sudo apt install build-essential dkms linux-headers-$(uname -r)

$ cd /media/mohit-yadav/VBox_GAs_7.2.0/

# YOSYS
$ sudo apt-get update

$ git clone https://github.com/YosysHQ/yosys.git

$ cd yosys

$ sudo apt install make

$ sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \graphviz xdot pkg-config python3 libboost-system-dev \libboost-python-dev libboost-filesystem-dev zlib1g-dev

$ make config-gcc

$ git submodule update --init --recursive

$ make

$ sudo make install

# Iverilog installation

$ sudo apt-get update

$ sudo apt install iverilog

<img width="806" height="261" alt="Screenshot 2025-09-20 222110" src="https://github.com/user-attachments/assets/5dbf1ca3-5726-4aba-bd84-4d7a79503001" />

# GTKWAVE

$ sudo apt-get update

$ sudo apt install gtkwave

<img width="716" height="127" alt="Screenshot 2025-09-20 222412" src="https://github.com/user-attachments/assets/1c1fa733-5e83-4b39-bf89-cec7dfc83fd7" />

# Acknowledgement

I'm very grateful to be part of VSD for this RISC V Tapeout SOC Program.
