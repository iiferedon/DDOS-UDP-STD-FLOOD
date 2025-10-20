# Hex Railing DDOS

---

## Description

This is a C-based network stress testing and denial-of-service (DoS) tool designed to flood a target IP address and port using two primary methods: a standard UDP flood and a custom 'STD' flood with pre-defined payloads.

This is a very small script capable of 1 Gbps per thread. You will need to multi thread this.

**Disclaimer:** This software is intended for educational purposes only. Unauthorized network stress testing or DoS attacks are illegal.

---

## How to Use

### 1. Build from Source in Linux Distros

To compile the `Rail.c` file, use the GNU Compiler Collection (GCC):

```bash
gcc Rail.c -o Rail
./Rail STD <IPADDRESS> <PORT> <SECONDS>
./Rail UDP <IPADDRESS> <PORT> <SECONDS>
