# Linux Lab

This repository documents my Linux, networking, and infrastructure learning lab.

The goal of this lab is to build strong fundamentals in:
- Linux administration
- Networking
- SSH
- Virtualization
- Infrastructure setup
- Troubleshooting

---

# 🖥️ Lab Environment

## Virtual Machines

| Machine | Purpose |
|---|---|
| Kali Linux | Security testing and Linux practice |
| Ubuntu Server | Server administration and SSH practice |

---

# ⚙️ Technologies Used

- VirtualBox
- Kali Linux
- Ubuntu Server
- OpenSSH
- Linux Terminal
- Internal VM Networking

---

# 🌐 Networking Setup

## Network Configuration

| Adapter | Mode |
|---|---|
| Adapter 1 | NAT |
| Adapter 2 | Internal Network (`labnet`) |

This setup allows:
- Internet access through NAT
- Communication between VMs through internal networking

---

# 🔐 SSH Configuration

Configured:
- OpenSSH Server on Ubuntu
- SSH access from Kali to Ubuntu
- SSH key authentication
- Passwordless login

Example command:

```bash
ssh username@ubuntu-ip
