# cybersecurity-lab-setup
Personal Cybersecurity Lab Setup using Windows 11, VirtualBox and Kali Linux
# 🔐 Cybersecurity Lab Setup

## 📌 Project Overview

This project documents my personal cybersecurity lab setup using Windows 11, Oracle VirtualBox, and Kali Linux.

The purpose of this project is to understand virtualization, Linux environments, network configuration, IP addressing, and basic cybersecurity lab practices through hands-on learning.

## 💻 System Specifications

| Component | Details |
|---|---|
| Host Operating System | Windows 11 |
| Processor | Intel Core i7 |
| RAM | 32 GB or more |
| Storage | 1 TB |
| Virtualization Software | Oracle VirtualBox |
| Virtual Machine | Kali Linux 2025.4 |
| Network Connection | Wi-Fi |

## ⚙️ Virtual Machine Configuration

| Configuration | Details |
|---|---|
| VM Name | kali-linux-2025.4-virtualbox-amd64 |
| Allocated Memory | 12,838 MB |
| Virtual Processors | 8 |
| Virtual Disk | 80.09 GB |
| Network Adapter | NAT / NAT Network (settings documented separately) |

## 🌐 Network Configuration

The VirtualBox NAT Network configuration was inspected with the following settings:

- Network Name: NatNetwork
- IPv4 Prefix: 10.0.2.0/24
- DHCP: Enabled

Manual IPv4 settings were also explored in Kali Linux:

- IP Address: 10.0.0.2
- Netmask: /24
- Gateway: 10.0.0.1
- DNS: 8.8.8.8 / 10.0.0.1

Note: The screenshots document different configuration states. The active network configuration and connectivity are still being verified.

## 🛠️ Work Performed

1. Set up Kali Linux in Oracle VirtualBox.
2. Inspected virtual machine resource allocation.
3. Explored VirtualBox network adapter settings.
4. Configured and inspected NAT Network settings.
5. Explored manual IPv4 and DNS configuration.
6. Documented the lab environment with screenshots.

## 🎯 Learning Outcomes

- Understanding virtualization and VM resource allocation.
- Exploring NAT Network configuration.
- Understanding IPv4 addressing and subnet masks.
- Learning gateway and DNS configuration.
- Practicing technical documentation and network troubleshooting.

## 🔒 Security Scope

All practical activities are intended for my own virtual lab environment and systems for which I have authorization.
