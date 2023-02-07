
# Management Commands

Here are some helpful commands for managing Linux. They also have brief descriptions with examples. 

# File System Management

ls - List the contents of a directory.

```
ls
```
cd - Change the current working directory.
```
cd path/to/directory
```

mkdir - Create a new directory.
```
mkdir directory_name
```
rmdir - Remove an empty directory.
```
rmdir directory_name
```

rm - Remove a file.

```
rm file_name
```
touch - Create an empty file.
```
touch file_name
```
cp - Copy a file or directory.
```
cp source destination
```
mv - Move or rename a file or directory.

```
mv source destination
```

# Disk Management

df - Display the amount of disk space used and available on file systems.

```
df
```
du - Display the amount of disk space used by a file or directory.

```
du file_or_directory
```
fsck - Check and repair a file system.
```
fsck file_system
```
mount - Mount a file system.
```
mount file_system mount_point
```
umount - Unmount a file system.
```
umount file_system
```
# Backup and Restore

tar - Create an archive file.
```
tar -cvf archive_file.tar file_or_directory
```
untar - Extract the contents of an archive file.
```
tar -xvf archive_file.tar
```
rsync - Synchronize files and directories between two locations.

```
rsync -av source destination
```
