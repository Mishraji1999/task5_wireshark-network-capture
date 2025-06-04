# Wireshark Network Traffic Capture and Analysis

## Overview

This repository contains network packet capture files and a detailed analysis report demonstrating the capture and examination of five fundamental network protocols using Wireshark:

- ARP (Address Resolution Protocol)
- DNS (Domain Name System)
- ICMP (Internet Control Message Protocol)
- TCP (Transmission Control Protocol)
- TLS (Transport Layer Security)

The objective is to provide hands-on experience in capturing live network traffic and identifying basic protocols and traffic types.

## Tools Used

- [Wireshark](https://www.wireshark.org/) (free, open-source network protocol analyzer)
- Operating systems: Windows / Linux / WSL (instructions applicable to all)

## Files Included

| File Name  | Description                           |
|------------|-------------------------------------|
| arp.pcap   | ARP protocol packet capture          |
| dns.pcap   | DNS query and response capture       |
| icmp.pcap  | ICMP echo request and reply capture  |
| tcp.pcap   | TCP connection handshake capture     |
| tls.pcap   | TLS handshake and encrypted traffic  |
| report.md  | Summary and analysis of captured packets |

## How to Use

1. Open any `.pcap` file using Wireshark.
2. Explore the captured packets, filter by protocol (e.g., `arp`, `dns`, `icmp`, `tcp`, `tls`).
3. Review packet details and protocol fields in the middle and bottom panes.
4. Refer to `report.md` for a summary and interpretation of the captures.

## Summary of Findings

- **ARP**: Demonstrated how MAC addresses are resolved from IP addresses via request and reply packets.
- **DNS**: Showed domain name resolution queries and responses.
- **ICMP**: Captured ping requests and replies to verify connectivity.
- **TCP**: Illustrated the three-way handshake establishing a connection.
- **TLS**: Captured the handshake process securing communication.

## Additional Notes

- All captures were taken on an active network interface during normal browsing and ping operations.
- This repository is intended for educational purposes to build foundational skills in network traffic analysis.

---

Feel free to explore the captures and extend the analysis!

