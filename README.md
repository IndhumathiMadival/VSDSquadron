
## VSDSQUADRON-MINI
###  Install RISC-V GNU Toolchain first, then install Yosys, iverilog, gtkwave.

<b></p>1.install RISC-V GNU Toolchain :</p>

>- git clone https://github.com/riscv/riscv-gnu-toolchain</br>
  >- sudo apt-get install autoconf automake autotools-dev curl python3 python3-pip libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool
patchutils bc zlib1g-dev libexpat-dev ninja-build git cmake libglib2.0-dev</br>
>- ls
>- cd riscv-gnu-toolchain
  >- ./configure --prefix=/opt/riscv</br>
  >- make</br>
  

![Screenshot from 2024-02-21 16-11-10](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/12661b7c-ebbf-441d-a3b7-49a64834156b)


<b></p>2.install Yosys:</p> 

>- git clone https://github.com/YosysHQ/yosys.git</br>
>- cd yosys</br>
>- sudo apt install make </br>
>- sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \graphviz xdot pkg-config python3 libboost-system-dev \libboost-python-dev libboost-filesystem-dev zlib1g-dev</br>
>- make config-gcc</br>
>- make</br>
>- sudo make install</br>


![Screenshot from 2024-02-21 15-26-40 (2)](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/1d1946f7-0d80-4346-808c-7dc04a0ee1c9)


<b></p>3.install iverilog: </p>
>sudo apt-get install iverilog</br>


![Screenshot from 2024-02-21 17-16-20](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/992b7a17-d1ec-4c49-b2be-a1cee3a00731)

<b></p>4.install gtkwave: </p>
>sudo apt-get install gtkwave</br>
![Screenshot from 2024-02-21 17-17-20](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/53d9af21-ce20-43c3-8eab-c269dc448602)
