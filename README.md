# build-tools

Build tools for Loongson (Binary).

- CLFS for LoongArch64 7.3 cross toolchain: [loongarch64-clfs-7.3-cross-tools-gcc-glibc.tar.xz](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongarch64-clfs-7.3-cross-tools-gcc-glibc.tar.xz).

    source code:
    
        binutils: https://github.com/loongson/build-tools/releases/download/2022.09.06/binutils-2.39_git.tar.gz
    
        glibc: https://github.com/loongson/build-tools/releases/download/2022.09.06/glibc-2.37_git.tar.gz
                 
        gcc: git://sourceware.org/git/gcc.git  commit:e73fe9e162af7b875a54cd78ddbb6bf26d8b06c2
                 
        linux: https://www.kernel.org/pub/linux/kernel/v6.x/linux-6.0.tar.xz
                 
- CLFS for LoongArch64 6.3: [loongarch64-clfs-system-6.3.tar.bz2](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongarch64-clfs-system-6.3.tar.bz2).  
lightdm: [loongarch64-clfs-system-6.0-lightdm.tar.bz2](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongarch64-clfs-system-6.0-lightdm.tar.bz2).  
WM-LXDE: [loongarch64-clfs-system-6.1-WM-LXDE.tar.bz2](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongarch64-clfs-system-6.1-WM-LXDE.tar.bz2).  
WM-KDE: [loongarch64-clfs-system-6.0-WM-LXDE.tar.bz2](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongarch64-clfs-system-6.0-WM-KDE.tar.bz2).  
Cross toolchain: [loongarch64-clfs-6.3-cross-tools-gcc-glibc.tar.xz](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongarch64-clfs-6.3-cross-tools-gcc-glibc.tar.xz).  
Documentation: [CLFS for LoongArch64](https://github.com/sunhaiyong1978/CLFS-for-LoongArch/blob/main/CLFS_For_LoongArch64.md).
- QEMU linux-user static binary: [qemu-loongarch64](https://github.com/loongson/build-tools/releases/download/2022.09.06/qemu-loongarch64).
- JDK8: [loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz)([md5](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz.md5)).
- Fedora Remix: [Mate Desktop](https://github.com/loongson/build-tools/releases/download/2022.09.06/livecd-fedora-mate-1.loongarch64.iso)([md5](https://github.com/loongson/build-tools/releases/download/2022.09.06/livecd-fedora-mate-1.loongarch64.iso.md5sum))

**Warning: The cross toolchain will only work properly on the latest systems, such as CLFS above.**
