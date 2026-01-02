## Disk and Storage Management

Disk issues are a common cause of production outages.

### df -h
Shows disk usage of mounted filesystems.

Example:
df -h

---

### du -sh
Displays disk usage of files or directories.

Example:
du -sh /var/log

---

### lsblk
Lists block devices and disks.

Example:
lsblk

---

### mount
Mounts a filesystem.

Example:
mount /dev/xvdf /data

---

### umount
Unmounts a filesystem.

Example:
umount /data

---

### DevOps Usage
- Troubleshooting disk full issues
- Managing cloud volumes
- Monitoring storage usage
