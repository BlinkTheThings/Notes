# GHDL Build Instructions

Run the following commands to download, build, and install the latest version of GHDL from
the GitHub master branch on Ubuntu 18.04 LTS:

    sudo apt install build-essential gnat zlib1g-dev
    mkdir -p ~/sources
    cd ~/sources
    wget -O ghdl-master.tar.gz https://github.com/ghdl/ghdl/archive/master.tar.gz
    tar -xvf ghdl-master.tar.gz
    mkdir ghdl-build
    cd ghdl-build
    ../ghdl-master/configure
    make
    sudo make install
