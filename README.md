# raspberry-os-cross-compilers
Precompiled Standalone ARM &amp; ARM64 Toolchains for Raspberry Pi SBCs.

## Description
Toolchains are built with `buildroot`, and intended to be executed on Linux. Tests are performed on Ubuntu.

## Toolchain Setup
These precompiled toolchains setup requires just three easy steps - Downloading, Extracting and Linking.
Prefer extracting the toolchain in `/opt` folder.
A `CMakefile` is provided with each toolchain.

## Toolchain Downloads

| Toolchains | Tested Host OS | Target OS | `CMakefile` | Precompiled GCC versions available |
| :---------- | :-----------: | :-------: | :--------: | :------------------------: |
| **Raspberry Pi GCC 64-Bit Cross-Compiler Toolchain (Bookworm)** | Ubuntu 22.04 | Bookworm **64-bit OS** (Debian Version 12) only | - | [12.3.0][nc-bookworm64-1000] |
| **Raspberry Pi GCC 32-Bit Cross-Compiler Toolchain (Bookworm)** | Ubuntu 24.04 | Bookworm **32-bit OS** (Debian Version 12) only | - | [14.2.0][nc-bookworm32-2000] |

[nc-bookworm64-1000]:https://www.embeddedsystems.tn/cross/cross-pi64_rpi3_ker6.6_gcc12.3.0.tar.gz
[nc-bookworm32-2000]:https://www.embeddedsystems.tn/cross/cross_pi32_ker6.12_gcc14.2.0.tar.gz


