# NETWORKWALKS-RISHU-B084H-WK1-PM1-CYBERSECURITY-LAB-SETUP
# 🛡️ Cybersecurity Lab Setup: VirtualBox & Kali Linux

This repository documents the setup of a virtual cybersecurity lab using Oracle VirtualBox and Kali Linux for Week 1 of the Networkwalks cybersecurity program.

> **Disclaimer:** This environment is intended for authorized educational and cybersecurity practice only.

---

## 📌 Project Overview

- **Task ID:** WK1-PM1
- **Intern Name:** Rishu Satish Singh
- **Batch Code:** B084H
- **Mentor:** Waqas Karim, CCIE
- **Organization:** Networkwalks
- **Project Week:** Week 1

The objective of this project is to configure a Kali Linux virtual machine in Oracle VirtualBox and connect it to a dedicated NAT Network for cybersecurity learning and future lab exercises.

---

## ⚙️ Lab Specifications

| Component | Configuration |
|---|---|
| Virtualization Platform | Oracle VirtualBox |
| Guest Operating System | Kali Linux 2026.3 |
| System Type | Debian (64-bit) |
| Allocated RAM | 2048 MB (2 GB) |
| Processor Count | 2 |
| Video Memory | 128 MB |
| Virtual Disk Format | VDI |
| Virtual Disk Capacity | Approximately 80 GB |
| Network Type | NAT Network |
| Network Name | `NatNetwork` |
| Network Adapter | Intel PRO/1000 MT Desktop (82540EM) |
| Promiscuous Mode | Allow All |

---

## 🌐 Network Configuration

The Kali Linux virtual machine is connected to the custom NAT Network named `NatNetwork`.

| Setting | Configuration |
|---|---|
| Network Name | `NatNetwork` |
| Network Range | `10.0.0.0/24` |
| IPv4 Connection | `Wired connection 1` |
| IPv4 Method | Automatic (DHCP) |
| Additional IPv4 Address | `10.0.0.2/24` |
| Gateway | `10.0.0.1` |
| Additional DNS Servers | Not specified |

The IPv4 configuration displays Automatic (DHCP) mode, with `10.0.0.2/24` listed as an additional address and `10.0.0.1` as the gateway.

---

## 🚀 Implementation Procedure

### 1. Virtual Machine Configuration

The Kali Linux virtual machine was configured in Oracle VirtualBox with 2 GB of RAM, two processors, 128 MB of video memory, and a VDI virtual disk with approximately 80 GB capacity.

### 2. NAT Network Configuration

A NAT Network named `NatNetwork` was selected for the Kali Linux virtual machine. The network uses the `10.0.0.0/24` address range.

This configuration provides a foundation for connecting additional virtual machines to the same lab network for future cybersecurity exercises.

### 3. Network Adapter Configuration

The virtual machine's network adapter was configured with the following settings:

- **Attached To:** NAT Network
- **Network:** `NatNetwork`
- **Adapter Type:** Intel PRO/1000 MT Desktop (82540EM)
- **Promiscuous Mode:** Allow All

### 4. IPv4 Configuration

The Kali Linux network connection is named `Wired connection 1`. The displayed IPv4 settings use Automatic (DHCP) mode and include an additional address of `10.0.0.2/24`, with the gateway set to `10.0.0.1`.

---

## 🧠 Learning Outcomes

Through this project, I gained practical exposure to:

- Configuring a Kali Linux virtual machine.
- Allocating system resources in VirtualBox.
- Understanding NAT Network configuration.
- Working with IPv4 addresses and gateway settings.
- Understanding virtual network adapters.
- Preparing a virtual environment for cybersecurity practice.

---

## 🔐 Security and Ethical Use

This lab is intended for educational purposes and authorized security testing. All penetration-testing activities should be performed only on systems owned by me or for which explicit permission has been granted.

---

## 🔗 Tools and Resources

- **Oracle VirtualBox:** https://www.virtualbox.org/wiki/Downloads
- **Kali Linux:** https://www.kali.org/get-kali/
- **7-Zip:** https://www.7-zip.org/

---

## 👤 Author

**Rishu Satish Singh**

Cybersecurity Intern — Networkwalks

**Batch:** B084H

---

## 📂 Project Information

- **Program:** Cybersecurity at Networkwalks
- **Week:** 01
- **Task:** WK1-PM1
- **Project:** Cybersecurity Lab Setup — VirtualBox & Kali Linux
- **Repository:** [GitHub Repository](https://github.com/rishuByte/NETWORKWALKS-RISHU-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP)
