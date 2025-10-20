# 🚂 Hex Railing DDOS

---

## 📝 Description

This is a C-based network stress testing and denial-of-service (DoS) tool designed to flood a target IP address and port using two primary methods: a standard UDP flood and a custom 'STD' flood with pre-defined payloads.

**Disclaimer:** This software is intended for educational purposes only. Unauthorized network stress testing or DoS attacks are illegal.

---

## 🚀 How to Use

### 1. Build from Source

To compile the `Rail.c` file, use the GNU Compiler Collection (GCC):

```bash
gcc Rail.c -o Rail
./Rail STD <IPADDRESS> <PORT> <SECONDS>
./Rail UDP <IPADDRESS> <PORT> <SECONDS>
