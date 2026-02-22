# Logical Volume Manager
- It is a storage management system used in linux.
- It helps to create a flexible storage system by creating abstraction layer between **physical layer and logical layer**.
- Th layer lies between physical and logical layer is called **volume group**.
- It helps to create dynamic storage system by combining multiple storage devices into a single storage thrpugh abstraction.
- It allows taking of snapshot without unmounting the filesystem.

## Physical Layer:
- It composed physical devices like SSD, Hard disk, RAID volumes etc.

## Volume Group:
- It is created by abstracting and combining the physical layer.

## Logical Volumes:
- It is the final partition created from volume group.
- It can be formatted with file system like ext4.

## LVM Architecture Diagram:

<img width="1536" height="1024" alt="LVM" src="https://github.com/user-attachments/assets/18936108-e7c0-4a88-83a6-a6cfceafc35d" />

