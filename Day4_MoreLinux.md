# Linux File Hierarchy
> File system is a directory structure that the OS uses.

- Windows: System files appear under the local disk C:
- Linux: System files appear under the root directory ( / )

# File structure in detail
## / ( root )
 - Every single file and directory starts from the root directory
 - The only root user has the right to write under this directory
 - /root is the root user’s home directory, which is not the same as /

 ## bin - Binary executables
 - Essential command binaries that need to be available in single-user mode; for all users
     - cat
     - ls
     - cp
     - pwd

 ## /boot - Boot loader files
- Kernel initrd, vmlinux, grub files are located under /boot
- Example:
 - initrd.img-2.6.32-24-generic,
 - vmlinuz-2.6.32-24-generic

 ## /dev - Essential Device files
 - These include terminal devices, usb, or any device attached to the system.
 - Example: /dev/tty1,
 - /dev/usbmon0

 ## /etc - et cetera
  - Contains configuration files required by all programs.
  - This also contains startup and shutdown shell scripts used to start/stop individual programs.
  - Example: /etc/resolv.conf,
  - /etc/logrotate.conf.

  ## /home - Home directory
  -  Home directories for all users to store their personal files.
  - example: /home/nathan,
  - /home/rexder