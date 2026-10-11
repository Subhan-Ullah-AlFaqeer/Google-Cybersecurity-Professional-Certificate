# 🛡️ Course 3, Module 2: Network Operations and Security Controls

Welcome to **Module 2** of **Connect and Protect: Networks and Network Security** (Course 3 of the Google Cybersecurity Professional Certificate)! This module delivers an operational dive into the network protocols, perimeter defenses, and privacy mechanisms that govern safe network communications. You will examine essential network protocols (DNS, DHCP, HTTP/HTTPS), wireless security standards (WEP through WPA3), firewalls, Virtual Private Networks (VPNs, including IPSec and WireGuard), network security zones, subnetting with CIDR notation, and proxy server architectures.

---

## 📝 Core Technical Objectives
- **Network & Application Protocols:** Mastering fundamental network protocols that regulate communications, including DNS (domain resolution), DHCP (dynamic IP allocation), HTTP/HTTPS (secure web browsing), and SSH/TLS.
- **Wireless Security Evolution:** Tracing the security developments in wireless standards from legacy WEP and WPA/WPA2 to modern WPA3, highlighting encryption mechanisms and vulnerability mitigations.
- **Perimeter Defense & Security Zones:** Implementing firewalls (stateless vs. stateful, packet-filtering, next-gen), proxy servers (forward vs. reverse proxies), and establishing DMZs (Demilitarized Zones) to segregate internal and external network traffic.
- **Subnetting, CIDR & Virtual Networks:** Calculating subnets using Classless Inter-Domain Routing (CIDR) notation, configuring Virtual Private Networks (VPNs with WireGuard and IPSec), and isolating virtual environments to enforce network privacy.

---

## 🧪 Module Learning Assets & Assessment Matrix

This module's core video lectures, readings, practice assignments, and knowledge checks are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Welcome & Network Protocols Intro** | Video and reading series exploring common application- and network-layer protocols (DNS, DHCP, HTTP/HTTPS, SSH). |
| **Wireless Security Protocol Evolution** | Reading and video walkthrough tracing wireless encryption standards (WEP, WPA, WPA2, WPA3). |
| **[Test Your Knowledge: Network Protocols](#-)** | Practice assignment evaluating protocol ports, wireless standards, and communication mechanisms (Grade: 100%). |
| **Firewalls, VPNs & Network Defense** | In-depth breakdown of firewall filtering rules, VPN tunneling protocols (WireGuard, IPSec), and security zones (DMZ). |
| **Subnetting, CIDR & Proxy Architectures** | Reading and video covering subnets, CIDR block calculations, forward/reverse proxy servers, and network boundary privacy. |
| **[Test Your Knowledge: System Identification](#-)** | Practice assignment assessing firewall placement, VPN protocol selection, and network segmentation (Grade: 100%). |
| **[Module Challenge 2 Graded Assessment](#-)** | Comprehensive end-of-module evaluation covering network protocols, firewalls, VPNs, CIDR subnetting, and DMZ design (Grade: 100%). |

---

## 💡 Visual Pipeline Reference

The perimeter defense architecture and protocol encapsulation workflow governing Module 2:

- **Perimeter Security Traffic Flow**:

  $$\text{External Traffic} \xrightarrow{\text{Boundary Firewall}} \text{DMZ (Public Services / Reverse Proxy)} \xrightarrow{\text{Internal Firewall}} \text{Internal Subnet (CIDR / LAN)}$$

- **Core Protocol & Security Mechanism Taxonomy**:

| Technology / Protocol | Operational Layer & Port | Primary Security Function |
| :--- | :--- | :--- |
| **HTTPS / TLS** | Application (Port 443) | Encrypted web communication preventing eavesdropping |
| **WPA3** | Data Link / Wireless | SAE (Simultaneous Authentication of Equals) mitigating dictionary attacks |
| **IPSec / WireGuard** | Network / Transport | Encrypted IP tunneling for secure remote-access VPNs |
| **Firewall / DMZ** | Network / Transport | Stateful packet filtering and perimeter segregation |

---

## 🎯 Technical Skills Architecture

### 📊 Network Protocol Analysis & Defense
- **Protocol Port Mapping:** Recognizing core protocol functions and default ports (e.g., DNS: 53, HTTP: 80, HTTPS: 443, SSH: 22).
- **Perimeter Security Engineering:** Position firewalls, proxies, and security zones (DMZs) to protect critical internal infrastructure.
- **Wireless Defense Assessment:** Identifying insecure legacy wireless protocols (WEP, WPA) and enforcing modern WPA3 standards.

### 🤖 Applied Practice & Professional Readiness
- **Subnetting & CIDR Calculation:** Interpreting CIDR notation (e.g., `/24`) to define network boundaries and IP address pools.
- **VPN Protocol Evaluation:** Differentiating between IPSec and WireGuard for secure site-to-site and remote-access VPN configurations.
- **Traffic Isolation:** Implementing proxy servers and DMZs to hide internal IP topologies and filter malicious payloads.

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Core Protocols & Encryption | Perimeter & VPN Tools | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Google Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=flat&logo=google&logoColor=white) | ![TLS & WPA3](https://img.shields.io/badge/Security-TLS_%7C_WPA3_%7C_DNS-orange?style=flat) | ![Firewalls & VPNs](https://img.shields.io/badge/Perimeter-Firewalls_%7C_WireGuard_%7C_IPSec-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
