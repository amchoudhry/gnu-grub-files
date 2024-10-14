# gnu-grub-files
GNU Grub files to use for your system.

I used the command below for my grub installation
```
grub-install --target=x86_64-efi --efi-directory=/boot --bootloader-id='GRUB UEFI' --boot-directory=/efi --debug
```
I have two partitions. First partition is mounted on `/efi`. Second is mounted on `/boot`. `/boot` is where my Windows 10 boot and Linux kernels are. The `40_custom` is where I have manually put my menu entries. The config is also included. This repo will continue to be updated.
