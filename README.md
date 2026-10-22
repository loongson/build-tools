# build-tools

Build tools for Loongson (Binary).

- LoongArch64 cross toolchain(Linux): [x86_64-cross-tools-loongarch64-binutils_2.47-gcc_16.2.0-glibc_2.44.tar.xz](https://github.com/loongson/build-tools/releases/download/2026.10.13/x86_64-cross-tools-loongarch64-binutils_2.47-gcc_16.2.0-glibc_2.44.tar.xz).
- LoongArch64 cross toolchain(Windows64): [Windows64-cross-tools-loongarch64-binutils_2.47-gcc_16.2.0-glibc_2.44.tar.xz](https://github.com/loongson/build-tools/releases/download/2026.10.13/Windows64-cross-tools-loongarch64-binutils_2.47-gcc_16.2.0-glibc_2.44.tar.xz).

    source code:
    
        binutils: https://ftp.gnu.org/gnu/binutils/binutils-2.47.tar.xz
    
        glibc: https://ftp.gnu.org/gnu/glibc/glibc-2.44.tar.xz
                 
        gcc: https://ftp.gnu.org/gnu/gcc/gcc-16.2.0/gcc-16.2.0.tar.xz
                 
        linux-header: https://mirrors.edge.kernel.org/pub/linux/kernel/v7.x/linux-7.2.10.tar.xz
                 
Documentation: [CLFS for LoongArch64](https://github.com/sunhaiyong1978/CLFS-for-LoongArch/blob/main/CLFS_For_LoongArch64.md).
- QEMU linux-user static binary: [qemu-loongarch64](https://github.com/loongson/build-tools/releases/download/2025.06.06/qemu-loongarch64).

    source code:  https://download.qemu.org/qemu-10.0.2.tar.xz

- Fedora Remix: [Mate Desktop](https://mirrors.wsyu.edu.cn/fedora/linux/F43/rawhide/Everything/loongarch64/iso/livecd-fedora-live-mate_compiz-202608011729.iso)([md5](https://mirrors.wsyu.edu.cn/fedora/linux/F43/rawhide/Everything/loongarch64/iso/livecd-fedora-live-mate_compiz-202608011729.iso.md5sum))

**Warning: The cross toolchain will only work properly on the latest systems, such as CLFS above.**
