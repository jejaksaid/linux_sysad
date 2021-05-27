---
### File System Basics
---

1. what is the purpose of the file system
2. how much space does the disk really have
3. how do i know what disks i have

### Partitions

1. what is partition table
2. what is MBR, GPT
3. how do i edit the partition table
4. how does the kernel know about partitions
5. what partition types are good

commands:
fdisk -l =>
fdisk /dev/sdb =>
portprobe =>
mkfs =>

### Available File Systems

1. what file systems are available on linux
2. what is the difference between different file systems
3. which file systems are supported
4. what do i do if i want a file system not listed as supported

### Formatting

1. why do file systems need to be formatted
2. how do i format a file system
3. can i change how a file system is formatted
4. how do i know if a file system has been formatted

commands:
mkfs.ext3 /dev/sdb1 =>
mkfs.ext2 /dev/sdb1 =>
mkfs.xfs /dev/sdb1 =>
mkfs.xfs /dev/sdb1 -f =>
tune2fs -j /dev/sdb1 -L storage

### Mounting

1. what is mounting
2. where are file systems located when mounted
3. how do i know which file systems are currently mounted
4. what are mounting options
5. can i mount uncommon things like DVDs

commands:
mkdir /newstorage
mount /dev/sdb1 /newstorage/

### File System Table

1. what is the file system table
2. how do i edit the file system table
3. how do i know if the file system table is working
4. what happens if i mess up when editing the file system table

commands:
nano /etc/fstab

### File System Features

1. what features are available with a file system
2. how do permissions work
3. how does SELinux work on file systems
4. how do disk quotas work
5. what happens when a file system is read only
