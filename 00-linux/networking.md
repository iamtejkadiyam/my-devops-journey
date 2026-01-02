## Linux Networking

Networking is critical for DevOps because cloud services, containers,
Kubernetes, and CI/CD all rely on network communication.

### ip a
Displays network interfaces and IP addresses.

Example:
ip a

---

### ip route
Shows routing table.

Example:
ip route

---

### ss
Displays active network connections and listening ports.

Example:
ss -tuln

---

### netstat
Older tool to inspect network connections.

Example:
netstat -tuln

---

### ping
Checks network connectivity between systems.

Example:
ping google.com

---

### curl
Transfers data from or to a server.
Commonly used to test APIs and services.

Example:
curl http://localhost:8080

---

### wget
Downloads files from the internet.

Example:
wget https://example.com/file.tar.gz

---

### nslookup
Queries DNS records.

Example:
nslookup google.com

---

### dig
Advanced DNS lookup tool.

Example:
dig google.com

---

### DevOps Usage
- Debugging service connectivity
- Verifying ports and listeners
- Testing APIs and endpoints
- Understanding DNS resolution
