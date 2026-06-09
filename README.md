# Assessing the Network with Common Security Tools - Lab 1

## Overview

This project documents a network security lab using common tools to assess network devices, capture traffic, and analyze scan results in a virtual lab environment.

## Tools Used

* Zenmap
* Nmap
* Wireshark
* tcpdump
* hping3
* ARP
* ICMP
* DNS

## Lab Objectives

* Identify IP address, subnet mask, gateway, and MAC address information
* Review ARP cache entries
* Capture and analyze network traffic
* Compare regular scans, ping scans, and intense scans
* Identify open ports and services on the firewall
* Analyze LAN, WAN, and DMZ network activity

## Key Findings

The firewall at `172.30.0.1` was detected as online during the scan. The regular Zenmap/Nmap scan found the following open TCP ports:

| Port | Service |
| ---- | ------- |
| 22   | SSH     |
| 53   | DNS     |
| 80   | HTTP    |

The ping scan confirmed that the host was online but did not list open ports. Wireshark showed ARP and ICMP traffic during the scan analysis, while DNS traffic was reviewed separately.

## Repository Structure

```text
network-security-tools-lab1/
├── README.md
├── docs/
├── commands/
└── screenshots/
```

## Skills Demonstrated

- Network scanning and reconnaissance
- Host discovery using Zenmap and Nmap
- Port scanning and service identification
- Packet capture analysis using Wireshark
- Command-line packet capture using tcpdump
- Packet testing using hping3
- ARP cache analysis
- IP address, subnet mask, gateway, and MAC address identification
- ICMP, ARP, and DNS traffic analysis
- Firewall traffic analysis
- LAN, WAN, and DMZ network assessment
- Comparing regular, ping, and intense scan results
- Basic network troubleshooting
- Technical documentation
