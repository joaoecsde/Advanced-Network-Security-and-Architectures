# Overview

This repository contains the lab reports for the SAAR (Security and Advanced Network Architectures) course. The reports cover various network security attacks, countermeasures, and advanced networking concepts implemented using GNS3 and Cisco networking equipment.

## Module 1: Network Security Attacks & Countermeasures

The first module focuses on Layer 2/3 network attacks and defensive mechanisms:

### Topics Covered

- **MAC Table Overflow** - Attack simulation using MAC address flooding and Port Security countermeasures
- **DHCP Spoofing** - Rogue DHCP server attacks and DHCP Snooping protection
- **ARP Poisoning (MitM)** - Man-in-the-Middle attacks via ARP cache poisoning and Dynamic ARP Inspection (DAI)
- **DNS Spoofing** - DNS response manipulation attacks
- **RIP Poisoning** - Routing protocol attacks on RIP networks
- **Zone-Based Policy Firewall (ZBPF)** - Campus network protection using firewall zones
- **DoS Attack Defense** - Denial of Service attack mitigation strategies
- **AAA with TACACS+** - Authentication, Authorization, and Accounting implementation
- **802.1X Authentication** - Port-based network access control with EAP-PEAP

## Module 2: VPNs and Advanced Network Architectures

The second module covers VPN technologies and advanced networking:

### Topics Covered

- **IPSec with ESP in Tunnel Mode** - Site-to-site VPN using IKE Phase 1 & 2, Pre-Shared Keys, AES-256 encryption
- **IPSec with Digital Certificates** - Certificate-based authentication using SCEP and Certificate Authority
- **GRE over IPSec** - Generic Routing Encapsulation tunnels protected by IPSec
- **IPSec with IKEv2** - Modern IKE implementation with rekeying mechanisms
- **DMVPN Phase 3** - Dynamic Multipoint VPN for hub-and-spoke and spoke-to-spoke communication
- **VRFs and BGP-MPLS L3VPNs** - Virtual Routing and Forwarding with MPLS Layer 3 VPNs
- **Linux Network Namespaces** - Connecting namespaces to external networks
- **Macvlan Networks with VLANs** - Container networking with VLAN tagging
- **Linux VXLAN with Multicast** - Virtual Extensible LAN implementation
- **Docker Swarm Services** - Container orchestration and overlay networking

## Tools & Technologies

- GNS3 Network Simulator
- Cisco IOSvL2 Switches
- Cisco IOS Routers
- Python (Scapy library for packet crafting)
- Linux (network namespaces, VXLAN, Docker)
- Wireshark (packet analysis)
