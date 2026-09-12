# 🌐 Networking-LAB

> Computer Networking Lab — Hands-on projects and practical exercises using **Cisco Packet Tracer**, **Wireshark**, **Nmap**, and **Windows/Linux networking tools**.

[![GitHub repo](https://img.shields.io/badge/GitHub-Networking--LAB-blue?logo=github)](https://github.com/Muhammad-Musharraf/Netwoking-LAB)
![Topics](https://img.shields.io/badge/Topics-Networking%20%7C%20Packet%20Tracer%20%7C%20Wireshark%20%7C%20Nmap-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

This repository contains lab exercises and practical assignments covering core computer networking concepts. Each lab is designed to build hands-on experience with industry-standard tools used in network configuration, analysis, and troubleshooting.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Cisco Packet Tracer** | Network topology design, simulation, and configuration |
| **Wireshark** | Packet capture and deep protocol analysis |
| **Nmap** | Network scanning, host discovery, and port enumeration |
| **Windows Networking Tools** | `ipconfig`, `ping`, `tracert`, `netstat`, `nslookup`, `arp` |
| **Linux Networking Tools** | `ifconfig`, `ip`, `ping`, `traceroute`, `netstat`, `dig`, `ss` |

---

## 📚 Topics Covered

- **IP Addressing & Subnetting** — IPv4/IPv6 addressing, CIDR notation, subnet masks, and subnetting exercises
- **Network Configuration** — Configuring routers, switches, and end devices in Cisco Packet Tracer
- **Routing Protocols** — Static routing, RIP, OSPF, and EIGRP configuration
- **Switching & VLANs** — VLAN setup, trunking (802.1Q), and inter-VLAN routing
- **Packet Analysis** — Capturing and dissecting packets with Wireshark (TCP, UDP, HTTP, DNS, ARP, ICMP)
- **Network Scanning** — Host discovery, open port detection, and OS fingerprinting using Nmap
- **Network Troubleshooting** — Diagnosing connectivity issues using CLI tools on Windows and Linux
- **Protocols** — Deep-dive into TCP/IP, UDP, ARP, DNS, DHCP, HTTP/HTTPS, ICMP, and more

---

## 🗂️ Repository Structure

```
Netwoking-LAB/
│
├── Cisco-Packet-Tracer/        # .pkt topology files and configuration labs
│   ├── Lab1-Basic-Topology/
│   ├── Lab2-Subnetting/
│   ├── Lab3-Routing/
│   └── ...
│
├── Wireshark/                  # Packet capture files and analysis reports
│   ├── TCP-Analysis/
│   ├── DNS-Analysis/
│   └── ...
│
├── Nmap/                       # Nmap scan scripts and results
│   ├── host-discovery/
│   ├── port-scanning/
│   └── ...
│
├── Windows-Tools/              # Exercises using Windows CLI networking commands
│
├── Linux-Tools/                # Exercises using Linux networking commands
│
└── README.md
```

> **Note:** The directory structure above reflects the general organization of the lab. Refer to individual folders for specific lab instructions and files.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed before running the labs:

- [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (v8.x or later) — Free with a Cisco NetAcad account
- [Wireshark](https://www.wireshark.org/download.html) — Free and open-source
- [Nmap](https://nmap.org/download.html) — Free and cross-platform
- A Windows or Linux environment for CLI-based exercises

### Clone the Repository

```bash
git clone https://github.com/Muhammad-Musharraf/Netwoking-LAB.git
cd Netwoking-LAB
```

---

## 🔬 Lab Highlights

### 🖧 Cisco Packet Tracer Labs
Build and simulate real network topologies. Labs include:
- Basic LAN/WAN setup
- Router and switch configuration via CLI
- VLAN and trunk configuration
- OSPF and RIP routing protocol setup

### 📦 Wireshark Packet Analysis
Capture live traffic or analyze pre-recorded `.pcap` files to understand:
- TCP 3-way handshake
- DNS query/response cycle
- ARP and ICMP behaviour
- HTTP vs HTTPS traffic patterns

### 🔍 Nmap Scanning Exercises
Practice ethical network reconnaissance:
- Ping sweeps (`-sn`) for host discovery
- TCP SYN scans (`-sS`) for port detection
- OS and service version detection (`-O -sV`)
- Script scanning with NSE (`--script`)

### 🖥️ CLI Networking (Windows & Linux)
Hands-on use of native OS tools:
- Diagnosing IP configuration issues
- Tracing packet routes across networks
- Resolving DNS names manually
- Viewing active connections and ARP tables

---

## 📖 Learning Objectives

By working through these labs, you will be able to:

- [ ] Design and simulate multi-device network topologies
- [ ] Configure routers and switches using Cisco IOS CLI
- [ ] Perform subnetting and IP addressing calculations
- [ ] Capture and analyse network traffic at the packet level
- [ ] Conduct network scans to identify hosts and services
- [ ] Troubleshoot connectivity issues using built-in OS tools
- [ ] Understand key networking protocols (TCP/IP, DNS, DHCP, ARP, etc.)

---

## 🤝 Contributing

Contributions, improvements, and additional lab exercises are welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b feature/new-lab`
3. Commit your changes: `git commit -m "Add Lab: [Topic]"`
4. Push to your branch: `git push origin feature/new-lab`
5. Open a Pull Request

---

## 👤 Author

**Muhammad Musharraf**

[![GitHub](https://img.shields.io/badge/GitHub-Muhammad--Musharraf-black?logo=github)](https://github.com/Muhammad-Musharraf)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> 💡 *"Networking is not just about connecting devices — it's about connecting people, ideas, and the future."*
