# build-tools

Build tools for Loongson (Binary).

- LoongArch64 cross toolchain(Linux): [x86_64-cross-tools-loongarch64-binutils_2.43.1-gcc_14.2.0-glibc_2.40.tar.xz](https://github.com/loongson/build-tools/releases/download/2024.11.01/x86_64-cross-tools-loongarch64-binutils_2.43.1-gcc_14.2.0-glibc_2.40.tar.xz).

    source code:
    
        binutils: https://ftp.gnu.org/gnu/binutils/binutils-2.43.1.tar.xz
    
        glibc: https://ftp.gnu.org/gnu/glibc/glibc-2.40.tar.xz
                 
        gcc: https://ftp.gnu.org/gnu/gcc/gcc-14.2.0/gcc-14.2.0.tar.xz
                 
        linux-header: https://mirrors.edge.kernel.org/pub/linux/kernel/v6.x/linux-6.10.tar.xz
                 
Documentation: [CLFS for LoongArch64](https://github.com/sunhaiyong1978/CLFS-for-LoongArch/blob/main/CLFS_For_LoongArch64.md).
- QEMU linux-user static binary: qemu-loongarch64.

    source code:  https://download.qemu.org/qemu-9.1.1.tar.xz

- JDK8: [loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz)([md5](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz.md5)).
- Fedora Remix: [Mate Desktop](http://mirrors.wsyu.edu.cn/fedora/linux/development/rawhide/Everything/loongarch64/iso/livecd-fedora-mate-5.loongarch64.iso)([md5](https://mirrors.wsyu.edu.cn/fedora/linux/development/rawhide/Everything/loongarch64/iso/livecd-fedora-mate-5.loongarch64.iso.md5sum))

**Warning: The cross toolchain will only work properly on the latest systems, such as CLFS above.**
