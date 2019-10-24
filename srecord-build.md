# SRecord Build Instructions

Run the following commands to download, build, and install SRecord 1.64 on Ubuntu 18.04

    sudo apt install build-essential libtool-bin ghostscript libgcrypt20-dev libboost-dev
    mkdir source
    cd source
    wget http://srecord.sourceforge.net/srecord-1.64.tar.gz
    tar -xvf srecord-1.64.tar.gz
    cd srecord-1.64
    ./configure
    make
    make sure
    sudo make install
    sudo ldconfig
