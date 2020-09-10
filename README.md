# KISS PowerPC
Unofficial KISS Linux port for 32-bit PowerPC architectures.

## Installation
General installation instructions can be found upstream at https://k1ss.org/install.

See [qemu documentation](https://wiki.qemu.org/Documentation/Platforms/PowerPC) for virtual machine support.

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

All packages compiled natively on PowerPC with
```
export CFLAGS="-mcpu=native -mtune=native -pipe -0s"
export CXXFLAGS="-mcpu=native -mtune=native -pipe -0s"
```

## See Also
- dylanaraps [kiss-repo](https://github.com/kisslinux/repo/tree/master/core) (upstream)
- arvl130 - [kiss32-repo](https://github.com/arvl130/kiss32-repo)
- jedavies-dev [kiss-ppc64le](https://github.com/jedavies-dev/kiss-ppc64le)
