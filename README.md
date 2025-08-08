# build-tools

Build tools for Loongson (Binary).

- LoongArch64 cross toolchain(Linux): [x86_64-cross-tools-loongarch64-binutils_2.45-gcc_15.1.0-glibc_2.42.tar.xz](https://github.com/loongson/build-tools/releases/download/2025.08.08/x86_64-cross-tools-loongarch64-binutils_2.45-gcc_15.1.0-glibc_2.42.tar.xz).
- LoongArch64 cross toolchain(Windows64): [Windows64-cross-tools-loongarch64-binutils_2.45-gcc_15.1.0-glibc_2.42.tar.xz](https://github.com/loongson/build-tools/releases/download/2025.08.08/Windows64-cross-tools-loongarch64-binutils_2.45-gcc_15.1.0-glibc_2.42.tar.xz).

    source code:
    
        binutils: https://ftp.gnu.org/gnu/binutils/binutils-2.45.tar.xz
    
        glibc: https://ftp.gnu.org/gnu/glibc/glibc-2.42.tar.xz
                 
        gcc: https://ftp.gnu.org/gnu/gcc/gcc-15.1.0/gcc-15.1.0.tar.xz
                 
        linux-header: https://mirrors.edge.kernel.org/pub/linux/kernel/v6.x/linux-6.16.tar.xz
                 
Documentation: [CLFS for LoongArch64](https://github.com/sunhaiyong1978/CLFS-for-LoongArch/blob/main/CLFS_For_LoongArch64.md).
- QEMU linux-user static binary: [qemu-loongarch64](https://github.com/loongson/build-tools/releases/download/2025.06.06/qemu-loongarch64).

    source code:  https://download.qemu.org/qemu-10.0.2.tar.xz

- Fedora Remix: [Mate Desktop](http://mirrors.wsyu.edu.cn/fedora/linux/F42/rawhide/Everything/loongarch64/iso/livecd-fedora-live-mate_compiz-202504251611.iso)([md5](https://mirrors.wsyu.edu.cn/fedora/linux/F42/rawhide/Everything/loongarch64/iso/livecd-fedora-live-mate_compiz-202504251611.iso.md5sum))

**Warning: The cross toolchain will only work properly on the latest systems, such as CLFS above.**
