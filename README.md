# build-tools

Build tools for Loongson (Binary).

- CLFS for LoongArch64 8.1 cross toolchain: [CLFS-loongarch64-8.1-x86_64-cross-tools-gcc-glibc.tar.xz](https://github.com/loongson/build-tools/releases/download/2023.08.08/CLFS-loongarch64-8.1-x86_64-cross-tools-gcc-glibc.tar.xz).

    source code:
    
        binutils: https://ftp.gnu.org/gnu/binutils/binutils-2.41.tar.xz
    
        glibc: https://ftp.gnu.org/gnu/glibc/glibc-2.38.tar.xz
                 
        gcc: https://ftp.gnu.org/gnu/gcc/gcc-13.2.0/gcc-13.2.0.tar.xz
                 
        linux: https://github.com/chenhuacai/linux.git
                 
- CLFS for LoongArch64 8.1 sysroot: [clfs-loongarch64-system-8.1-sysroot.squashfs](https://github.com/loongson/build-tools/releases/download/2023.08.08/clfs-loongarch64-system-8.1-sysroot.squashfs).  

Cross toolchain: [CLFS-loongarch64-8.1-x86_64-cross-tools-gcc-glibc.tar.xz](https://github.com/loongson/build-tools/releases/download/2023.08.08/CLFS-loongarch64-8.1-x86_64-cross-tools-gcc-glibc.tar.xz).  
Documentation: [CLFS for LoongArch64](https://github.com/sunhaiyong1978/CLFS-for-LoongArch/blob/main/CLFS_For_LoongArch64.md).
- QEMU linux-user static binary: [qemu-loongarch64](https://github.com/loongson/build-tools/releases/download/2023.08.08/qemu-loongarch64).

    source code: https://download.qemu.org/qemu-8.0.3.tar.xz

- JDK8: [loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz)([md5](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz.md5)).
- Fedora Remix: [Mate Desktop](https://github.com/loongson/build-tools/releases/download/2022.09.06/livecd-fedora-mate-1.loongarch64.iso)([md5](https://github.com/loongson/build-tools/releases/download/2022.09.06/livecd-fedora-mate-1.loongarch64.iso.md5sum))

**Warning: The cross toolchain will only work properly on the latest systems, such as CLFS above.**
