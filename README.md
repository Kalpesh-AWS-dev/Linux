# Linux
This  is Linux  repository , in this all Linux Commands and Their Uses.

# Linux Commands and Their Uses

## **1. File and Directory Management**

- **`ls`**: Lists files and directories.
  - Example: `ls -l` (detailed list)
- **`cd`**: Changes the current directory.
  - Example: `cd /home` (change to /home directory)
- **`pwd`**: Displays the current working directory.
- **`mkdir`**: Creates a new directory.
  - Example: `mkdir new_folder`
- **`rmdir`**: Removes an empty directory.
  - Example: `rmdir old_folder`
- **`rm`**: Removes files or directories.
  - Example: `rm file.txt` or `rm -r folder` (remove recursively)

---

## **2. File Operations**

- **`touch`**: Creates a new empty file.
  - Example: `touch file.txt`
- **`cp`**: Copies files or directories.
  - Example: `cp source.txt destination.txt`
- **`mv`**: Moves or renames files or directories.
  - Example: `mv old.txt new.txt`
- **`cat`**: Displays the content of a file.
  - Example: `cat file.txt`
- **`more`**: Views file content one screen at a time.
  - Example: `more file.txt`
- **`less`**: Similar to more but with backward navigation.
  - Example: `less file.txt`
- **`head`**: Displays the first few lines of a file.
  - Example: `head -n 10 file.txt`
- **`tail`**: Displays the last few lines of a file.
  - Example: `tail -n 10 file.txt`
- **`nano`**: Opens a file in the Nano text editor.
  - Example: `nano file.txt`
- **`vi` or `vim`**: Opens a file in the Vi text editor.
  - Example: `vim file.txt`

---

## **3. Permissions and Ownership**

- **`chmod`**: Changes file permissions.
  - Example: `chmod 755 file.txt`
- **`chown`**: Changes file ownership.
  - Example: `chown user:group file.txt`
- **`chgrp`**: Changes group ownership of a file.
  - Example: `chgrp group file.txt`

---

## **4. Process Management**

- **`ps`**: Displays running processes.
  - Example: `ps aux`
- **`top`**: Displays real-time system performance and processes.
- **`htop`**: Interactive process viewer (if installed).
- **`kill`**: Terminates a process by PID.
  - Example: `kill 1234`
- **`killall`**: Terminates processes by name.
  - Example: `killall firefox`
- **`jobs`**: Lists background jobs.
  - Example: `jobs`
- **`bg`**: Resumes a background job.
  - Example: `bg %1`
- **`fg`**: Brings a background job to the foreground.
  - Example: `fg %1`

---

## **5. Networking**

- **`ping`**: Checks connectivity to a host.
  - Example: `ping google.com`
- **`ifconfig`**: Displays or configures network interfaces (deprecated, use `ip`).
  - Example: `ifconfig eth0`
- **`ip`**: Configures network interfaces.
  - Example: `ip addr show`
- **`netstat`**: Displays network connections (deprecated, use `ss`).
  - Example: `netstat -tuln`
- **`ss`**: Displays network statistics.
  - Example: `ss -tuln`
- **`curl`**: Transfers data from or to a server.
  - Example: `curl http://example.com`
- **`wget`**: Downloads files from the internet.
  - Example: `wget http://example.com/file.txt`

---

## **6. System Monitoring**

- **`df`**: Displays disk space usage.
  - Example: `df -h`
- **`du`**: Displays directory space usage.
  - Example: `du -sh folder`
- **`free`**: Displays memory usage.
  - Example: `free -h`
- **`uptime`**: Displays system uptime.
- **`who`**: Displays logged-in users.
  - Example: `who`
- **`w`**: Displays detailed information about logged-in users.
  - Example: `w`

---

## **7. Archiving and Compression**

- **`tar`**: Archives files.
  - Example: `tar -cvf archive.tar folder`
- **`gzip`**: Compresses files using gzip.
  - Example: `gzip file.txt`
- **`gunzip`**: Decompresses gzip files.
  - Example: `gunzip file.txt.gz`
- **`zip`**: Compresses files into a zip archive.
  - Example: `zip archive.zip file.txt`
- **`unzip`**: Extracts files from a zip archive.
  - Example: `unzip archive.zip`

---

## **8. User Management**

- **`whoami`**: Displays the current user.
- **`id`**: Displays user ID and group ID.
- **`adduser`**: Adds a new user.
  - Example: `adduser username`
- **`passwd`**: Changes the password of a user.
  - Example: `passwd username`
- **`deluser`**: Deletes a user.
  - Example: `deluser username`
- **`usermod`**: Modifies user accounts.
  - Example: `usermod -aG group username`

---

## **9. Package Management**

- **`apt-get`**: Installs, upgrades, or removes packages.
  - Example: `apt-get install package`
- **`apt`**: Modern package manager for Debian-based systems.
  - Example: `apt update`
- **`dpkg`**: Low-level package manager.
  - Example: `dpkg -i package.deb`

---

## **10. Search and Filters**

- **`find`**: Searches for files and directories.
  - Example: `find / -name file.txt`
- **`grep`**: Searches for patterns in text.
  - Example: `grep 'error' log.txt`
- **`locate`**: Finds files quickly using an indexed database.
  - Example: `locate file.txt`
- **`awk`**: Processes and analyzes text.
  - Example: `awk '{print $1}' file.txt`
- **`sed`**: Edits text in a stream.
  - Example: `sed 's/old/new/g' file.txt`

---

## **11. Disk Management**

- **`mount`**: Mounts a filesystem.
  - Example: `mount /dev/sdb1 /mnt`
- **`umount`**: Unmounts a filesystem.
  - Example: `umount /mnt`
- **`fdisk`**: Manages disk partitions.
  - Example: `fdisk /dev/sdb`
- **`mkfs`**: Formats a partition.
  - Example: `mkfs.ext4 /dev/sdb1`
- **`fsck`**: Checks and repairs a filesystem.
  - Example: `fsck /dev/sdb1`
