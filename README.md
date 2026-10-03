# Snort3_IDS
Snort 3 Intrusion Detection System project featuring custom rules for ICMP, TCP port scans, SSH, HTTP, FTP and Telnet detection, with tcpdump and Wireshark traffic analysis.


## Project Overview

This project demonstrates the implementation of a Network Intrusion Detection System (IDS) using **Snort3** and **Wireshark** in a virtual Cyberscurity lab.

This project focuses on detecting suspicious network activities using custom rules and analyzing the corresponding network packets using Wireshark.

---

## Objectives

- Install and configure Snort3
- Configure HOME_NET
- Create ICMP/Ping traffic
- Detect TCP port scanning
- Detect SSH brute-force attempts
- Detect HTTP, FTP and Telnet connections
- Capture network traffic using tcpdump
- Analyze packets using Wireshark
- Correlate Snort alerts with captured network traffic

  ---

  ## Lab Environment

  | Component | Details |
|-----------|---------|
| Attacker | Kali Linux |
| IDS | Ubuntu Linux + Snort 3 |
| Network Analysis | Wireshark |
| Scanning Tool | Nmap |
| Packet Capture | tcpdump |
| Virtualization | Oracle VirtualBox |

---

## 🔧 Tools Used

- Snort 3
- Wireshark
- tcpdump
- Nmap
- Kali Linux
- Ubuntu Linux
- Oracle VirtualBox

---

# ⚙️ Project Implementation

## 1. Snort 3 Installation

Snort 3 was built and installed from source along with its required dependencies and LibDAQ.

Configuration was validated using:

```bash
snort -c /usr/local/etc/snort/snort.lua -T
