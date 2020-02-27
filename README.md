# OrangePiZero-OpenWrt
OpenWrt for OrangePiZero

just record how to make  Openwrt for OrangePi Zero

problem: 1 wifi cann't work

Secondary compilation
source：https://github.com/Lienol/openwrt

Self-compiling method
 sudo apt-get update
 sudo apt-get -y install build-essential asciidoc binutils bzip2 gawk gettext git libncurses5-dev libz-dev patch python3 unzip zlib1g-dev lib32gcc1 libc6-dev-i386 subversion flex uglifyjs git-core gcc-multilib p7zip p7zip-full msmtp libssl-dev texinfo libglib2.0-dev xmlto qemu-utils upx libelf-dev autoconf automake libtool autopoint device-tree-compiler
 
 git clone （source）
 
 ./scripts/feeds clean
 ./scripts/feeds update -a && ./scripts/feeds install -a
 
 make menuconfig

make -j1 V=s

Learn to communicate, not commercial
