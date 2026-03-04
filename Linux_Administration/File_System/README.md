# File System
It is used by linux to manage the directory, files and drivers present in the storage.

## EXT:
- It is the first file system created for linux.
- It supports partition up to 2 gb.
- It uses unix like file permissions.
- It has fragmentation issue.

## EXT2:
- It support partition up to 4 tb.
- It support naming up to 250 characters.
- It lacks performance and frequent crashes on large partitions.
- It won't support journaling.

## EXT3:
- It allows upgrading from EXT2 to EXT3 without formating the partition.
- It support journaling.
- Journaling leads to performance issue.
- It has scalability issue.

## EXT4:
- It support partition up to 16 tb.
- It increase performance by reducing the fragmentation issue.
- It supports scalability and journaling.
- It allows downgrading from EXT4 to EXT3 without formattting partition.
