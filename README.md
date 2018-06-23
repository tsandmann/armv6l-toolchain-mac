# armv6l-toolchain-mac
A cross-compiler toolchain for macOS (10.13) host and armv6l-linux-gnueabihf target optimized for arm1176jzf-s (Raspberry Pi / Raspberry Pi Zero (W)).

#### Installation
Checkout to `/usr/local/armv6l-unknown-linux-gnueabihf` and add `/usr/local/armv6l-unknown-linux-gnueabihf/bin` to *PATH*.

#### Components and Versions
* gcc 8.1.0 (patched against 85764), glibc 2.26, binutils 2.30, gdb 8.1 (built with crosstool-ng)
* boost 1.67.0
