## File Content Viewing

Used to read file contents safely without modifying them.

### cat
Displays entire file content.

Example:
cat config.yaml

---

### less
Views file content page by page.
Preferred for large files.

Example:
less /var/log/syslog

---

### head
Shows first few lines of a file.

Example:
head config.yaml

---

### tail
Shows last few lines of a file.
Used frequently for logs.

Example:
tail app.log
tail -f app.log

---

### DevOps Usage
- Reading configuration files
- Debugging logs
- Monitoring running applications
