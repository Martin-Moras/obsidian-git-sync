- yum package manager
- [[Kernal]]: A birdge between hardware (CPU, Memory, Devices) and software
- Bootloader: boots the operating system e.g. Grub, ISOLinux
- Service: Program that runs as a background process e.g. httpd, nfsd, ntpd, named
- Filesystem: Method for storing and organizing files e.g. ect3, ext4, FAT, XFS, NTFS, Btrfs
- X Window System: GUI for allmoast all Linux systems.
- Desktop Environment: Basicly the desctop e.g. Gnome, KDE, Xfce, Fluxbox.
- Command line: Interface for typing commands on top of the operating system.
- Shell: Command line interpreter that tells the OS what to do e.g. bash, tcshell (tcsh), zshell (zshell).

### Distro
- has a Kernal
- programs for: file management, user management, package management.  

### Boot process

#### Power ON
#### BIOS (Basic Input Output System)
- Initializes the screen and keyboard and tests the main memory. This process is caled POST (Power On Selth Test)
- BIOS is on a ROM chip on the motherboard stored
#### MBR
- is stored on a hard disk. Either in the boot sector [[MBR]] or EFI partition 
#### Boot Loader
- e.g. GRUP (Grand unified bootloader), ISO Linux for booting from removable media, dos u-boot for booting on embedded devices appliancess
- Moast boot loaders can give you multible options for booting Linux and other installed OS's.
- it boots the kernal image and initial Ram disk or file system into memory
- Boot loader has 2 stages:
	For [[MBR]]:
1. the [[MBR]] gets loaded. It searches a bootable partion. 
2. MBR loads second stage boot loader and loads it into RAM e.g. GRUB.
	For EFI / UEFI...

### SystemD targets
SystemD targets are a way to manage all .target files you have. .target files can depend on each other and SystemD puts them during boot in the right order.


### GNU
1. GCC compiler
2. C runtime compiler
3. bash shell 

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
###