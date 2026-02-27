# Linux Boot Process
Linux Boot Process is a multi-stage sequence starts from hardware initialization.

## BIOS / UEFI Initialization:
- At the time of power on the BIOS will perform postcheck which send request to all the hardware components present in the system.
- It also helps to detect the bootable devices and pass the control to boot loader.

## Boot loader stage:
- It is reponsible for loading the kernel into the memory.
- GRUB is the default bootloader in linux.
- It pass the control to kernel with parameters.

## Kernel Initialization:
- Kernel decompress itself into the memory to initialize the hardware components.
- It creates a temporary root file system called as initramfs to mount the drivers and modules to mount root file system.
- After mounting the root file system, it passes the control to kernel which starts the init process

## Systemd Stage:
- It came as a replacement for SysvInit in Rhel 7
- It initialize the root file system, drivers, services and daemons.

## Login Prompt:
- It display the login screen to the users.

