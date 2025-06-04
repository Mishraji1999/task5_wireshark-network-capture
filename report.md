# Network Traffic Capture Report

**Date of Capture:** 2025-06-04  
**Network Interface:** Wi-Fi (wlan0)  
**Capture Duration:** About 1 minute per protocol

---

## Protocols Captured

### ARP (Address Resolution Protocol)
ARP is used to find the MAC address of a device when only its IP address is known.  
**Observation:** I saw ARP requests asking "Who has IP X?" and replies providing the MAC address.

### DNS (Domain Name System)
DNS translates domain names like google.com into IP addresses.  
**Observation:** I captured DNS queries for domain names and the responses with IP addresses.

### ICMP (Internet Control Message Protocol)
ICMP is used for network diagnostics like ping.  
**Observation:** I saw ICMP echo requests and replies confirming connectivity.

### TCP (Transmission Control Protocol)
TCP establishes reliable connections between devices.  
**Observation:** I observed the TCP three-way handshake (SYN, SYN-ACK, ACK) during connection setup.

### TLS (Transport Layer Security)
TLS secures communication over the network by encrypting data.  
**Observation:** I captured TLS handshake packets starting a secure session.

---

## Conclusion

This task helped me understand how different network protocols work and how to identify them using Wireshark. Each protocol has a specific role in network communication, from resolving addresses to securing data.



## Conclusion

This capture exercise provided practical experience in identifying and analyzing key network protocols using Wireshark. The captures demonstrate typical network behaviors such as address resolution, domain name lookup, connectivity checks, connection establishment, and secure communication.

