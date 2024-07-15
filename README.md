# aarch64-linux-gnu
The `PKGBUILD` is mainly from the archlinux package repository, I just made some minor modifications to compile an older version of GCC.  

Component | Version
-|-
gcc | 6.5.0 (with libstdc++ 6.0.22)
glibc | 2.27
binutils | 2.30

## notes
You may need a suitable toolchain to compile. (I successfully compiled on gcc-8.2.0, make-4.2.1, fails with the latest version of the toolchain.)  

## credits
https://archlinux.org/packages/extra/x86_64/aarch64-linux-gnu-gcc/  
https://archlinux.org/packages/extra/any/aarch64-linux-gnu-glibc/  
https://archlinux.org/packages/extra/x86_64/aarch64-linux-gnu-binutils/