Buildroot currently builds a rootfs file and a kernel file. If you want to start this in a QEMU session, you have to give a separate flag where QEMU can find the kernel.

This script takes the output of Buildroot and converts it to a single disk image file that contains a master boot record, GRUB2 and the kernel in /boot.

It currently only supports x86 builds.
