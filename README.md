# build-tools

Build tools for Loongson (Binary).

- LoongArch64 cross toolchain (x86_64 Linux): [x86_64-cross-tools-loongarch64-binutils_2.42-gcc_14.1.0-glibc_2.39.tar.xz](https://github.com/loongson/build-tools/releases/download/2024.06.01/x86_64-cross-tools-loongarch64-binutils_2.42-gcc_14.1.0-glibc_2.39.tar.xz).

    source code:
    
        binutils	: https://ftp.gnu.org/gnu/binutils/binutils-2.42.tar.xz
	    gcc 		: https://ftp.gnu.org/gnu/gcc/gcc-14.1.0/gcc-14.1.0.tar.xz
        linux-header	: https://mirrors.edge.kernel.org/pub/linux/kernel/v6.x/linux-6.8.9.tar.xz
        glibc		: https://ftp.gnu.org/gnu/glibc/glibc-2.39.tar.xz
	    gdb		: https://ftp.gnu.org/gnu/gdb/gdb-14.2.tar.xz
	    pkg-config	: https://pkg-config.freedesktop.org/releases/pkg-config-0.29.2.tar.gz
                 
- CLFS for LoongArch64 8.1 sysroot: [clfs-loongarch64-system-8.1-sysroot.squashfs](https://github.com/loongson/build-tools/releases/download/2023.08.08/clfs-loongarch64-system-8.1-sysroot.squashfs).  

- QEMU linux-user static binary: [qemu-loongarch64](https://github.com/loongson/build-tools/releases/download/2023.08.08/qemu-loongarch64).

    source code: https://download.qemu.org/qemu-8.0.3.tar.xz

- JDK8: [loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz)([md5](https://github.com/loongson/build-tools/releases/download/2022.09.06/loongson8.1.11-jdk8u332b09-linux-loongarch64-clfs-6.3-0.tar.gz.md5)).
- Fedora Remix: [Mate Desktop](https://github.com/loongson/build-tools/releases/download/2022.09.06/livecd-fedora-mate-1.loongarch64.iso)([md5](https://github.com/loongson/build-tools/releases/download/2022.09.06/livecd-fedora-mate-1.loongarch64.iso.md5sum))

**Warning: The cross toolchain will only work properly on the latest systems, such as CLFS above.**
