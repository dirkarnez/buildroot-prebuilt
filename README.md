buildroot-prebuilt
============================
`sudo dd if=sdcard.img of=/dev/sd{?} bs=4M conv=sync status=progress`

### Overlay
- [hugh712/mp3_player](https://github.com/hugh712/mp3_player)
- [**如何添加APP到Buildroot里(以瑞芯微rv1126为例)_专栏_易百纳技术社区**](https://www.ebaina.com/articles/140000016828)
- [k3s-io/k3s-root: K3s agent user space binaries](https://github.com/k3s-io/k3s-root)

### Tutorials
- [Buildroot and compiler on target | LupLab @ UC Davis](https://luplab.cs.ucdavis.edu/2022/01/06/buildroot-and-compiler-on-target.html)
- [Introduction · Buildroot架構解析](https://hugh712.gitbooks.io/buildroot/content/)
- [使用 buildroot 建立 Mips Cross-Compiler 的環境 | by MH Chen | Medium](https://pipi9baby.medium.com/%E4%BD%BF%E7%94%A8-buildroot-%E5%BB%BA%E7%AB%8B-mips-cross-compiler-%E7%9A%84%E7%92%B0%E5%A2%83-e63a665b87f2)
- [builtroot make menuconfig流程 - suonikeyinsu - 博客园](https://www.cnblogs.com/black-mamba/p/8888539.html)
- [digiampietro/buildroot-armv7: A set of scripts, configuration files and Buildroot external tree to setup a Qemu emulation environment to run and reverse engineer the *Netgear DVA 5592* executables. This environment uses Docker, Buildroot and Qemu to emulate a board with an ARMv7 Cortex A9 processor, Linux kernel 3.4.11-rt19, uClibc 0.9.33.2, and old versions of other libraries.](https://github.com/digiampietro/buildroot-armv7)

### x86_64
- [buildroot编译运行QEMU X86_64](https://jgsun.github.io/2020/05/28/qemu-x86-64/)
  - ```bash
    sudo qemu-system-x86_64 -M pc -kernel output/images/bzImage \
      -drive file=output/images/rootfs.ext2,if=virtio,format=raw \
      -append "rootwait root=/dev/vda console=tty1 \
      console=ttyS0" \
      -net nic,model=virtio \
      -net user -nographic \
      -enable-kvm
    ```
### aarch64


### arm
- [mxOBS/imagebuilder](https://github.com/mxOBS/imagebuilder)
