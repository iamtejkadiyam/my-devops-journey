## Linux Users and Groups

### User Management
- adduser <username>
- deluser --remove-home <username>

### Group Management
- usermod -aG <group> <username>
- getent group <groupname>

### Sudo Access
- usermod -aG sudo <username>
- sudo -i
- su -i

### Important Files
- /etc/passwd
- /etc/group
