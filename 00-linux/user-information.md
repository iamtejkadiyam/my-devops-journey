## User and Authentication Information

Used to inspect system users and authentication details.

### /etc/passwd
Stores user account information.

Example:
cat /etc/passwd

---

### getent passwd
Fetches user details from system databases.

Example:
getent passwd username

---

### whoami
Shows current logged-in user.

Example:
whoami

---

### id
Displays user ID and group memberships.

Example:
id username

---

### DevOps Usage
- Debugging permission issues
- Verifying service users
- Security audits
