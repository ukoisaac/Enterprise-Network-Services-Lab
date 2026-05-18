# Enterprise Network Services Lab

## Overview
This project demonstrates the configuration of core enterprise network services using Cisco Packet Tracer.

Configured services include:

- DHCP
- DNS
- WEB Server
- EMAIL Server
- FTP Server

---

# Network Topology

<img width="1335" height="559" alt="config, dns, dhcp, web, email and ftp server" src="https://github.com/user-attachments/assets/a87bf7b9-6cfb-4ded-b8f6-33f69218c3da" />

---

# Network Information

| Device/Service | IP Address |
|---|---|
| Router Gateway | 192.168.1.1 |
| Web Server | 192.168.1.2 |
| DHCP Server | 192.168.1.3 |
| DNS Server | 192.168.1.4 |
| Email Server | 192.168.1.5 |
| FTP Server | 192.168.1.6 |

Network: `192.168.1.0/24`

---

# Services Configured

## DHCP Server
- Dynamically assigned IP addresses to clients
- Configured default gateway and DNS information

## DNS Server
- Resolved domain names to IP addresses
- Configured records for internal services

## WEB Server
- Hosted internal company webpage

## EMAIL Server
Configured:
- User accounts
- Mail domain
- Client email access

### User Accounts
| User | Email |
|---|---|
| Joy | joy@isaac.com |
| Ada | ada@isaac.com |
| Adam | adam@isaac.com |

## FTP Server
- Enabled file transfer services
- Configured FTP access

---

# Technologies Used

- Cisco Packet Tracer
- TCP/IP
- DHCP
- DNS
- FTP
- SMTP/POP3
- HTTP/HTTPS

---

# Verification

## Connectivity Tests
```bash
ping 192.168.1.1
ping 192.168.1.2
