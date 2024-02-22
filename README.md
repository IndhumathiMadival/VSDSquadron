
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
  



<b></p>2.install Yosys:</p> 

>- git clone https://github.com/YosysHQ/yosys.git</br>
>- cd yosys</br>
>- sudo apt install make </br>
>- sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \graphviz xdot pkg-config python3 libboost-system-dev \libboost-python-dev libboost-filesystem-dev zlib1g-dev</br>
>- make config-gcc</br>
>- make</br>
>- sudo make install</br>




<b></p>3.install iverilog: </p>
>sudo apt-get install iverilog</br>



<b></p>4.install gtkwave: </p>
>sudo apt-get install gtkwave</br>
