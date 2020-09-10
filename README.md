# KISS PowerPC
Unofficial KISS Linux port for 32-bit PowerPC architectures.

## Installation
General installation instructions can be found upstream at https://k1ss.org/install.

See [qemu documentation](https://wiki.qemu.org/Documentation/Platforms/PowerPC) for virtual machine support.

Prebuilt [Debian images](https://people.debian.org/~aurel32/qemu/powerpc/) are useful as a development environment.

## Packages
core:
- baselayout
- binutils
- bison
- busybox
- bzip2
- curl
- flex
- gcc
- git
- gzip
- kiss
- libressl
- linux-headers
- m4
- make
- musl
- pkgconf
- xz
- zlib

All packages compiled with
```
export CFLAGS="-mcpu=native -mtune=native -pipe -0s"
export CXXFLAGS="-mcpu=native -mtune=native -pipe -0s"
```
