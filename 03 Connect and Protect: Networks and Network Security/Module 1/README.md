# 🛡️ Course 3, Module 1: Network Architecture and Communication Models

Welcome to **Module 1** of **Connect and Protect: Networks and Network Security** (Course 3 of the Google Cybersecurity Professional Certificate)! This module provides an operational foundation in network architecture, network hardware components, cloud computing infrastructure, and network communication protocols. You will examine Local Area Networks (LANs), Wide Area Networks (WANs), Software-Defined Networking (SDN), and compare the four-layer TCP/IP model with the seven-layer OSI reference model to understand how data travels across interconnected systems.

---

## 📝 Core Technical Objectives
- **Network Topology & Components:** Differentiating between physical and logical network components (routers, switches, hubs, modems, access points) and designing secure Local Area Networks (LANs).
- **Cloud Infrastructure & SDN:** Exploring cloud networks, virtual private clouds (VPCs), and Software-Defined Networking (SDN) architectures that decouple the control plane from the data plane.
- **TCP/IP Protocol Suite:** Mastering the four layers of the TCP/IP model (**Network Interface, Internet, Transport, Application**) and tracing packet encapsulation/decapsulation across networks.
- **OSI Reference Model & IP Addressing:** Comparing TCP/IP with the seven layers of the OSI model, understanding IPv4/IPv6 addressing schemes, and mapping network layer communication protocols.

---

## 🧪 Module Learning Assets & Assessment Matrix

This module's core video lectures, readings, practice exercises, interactive tools, and knowledge checks are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Course 3 Orientation & Resources** | Program overview, network security fundamentals, and essential study materials. |
| **Network Tools & Device Anatomy** | Video and reading series covering physical/virtual network hardware, switches, routers, and topology diagrams. |
| **[Practice: Design a Local Area Network](#-)** | Interactive plugin exercise modeling and configuring network topologies for LAN environments. |
| **Cloud Computing & SDN Infrastructure** | Reading on cloud service models (IaaS, PaaS, SaaS) and virtualized Software-Defined Networks. |
| **[Test Your Knowledge: Intro to Networks](#-)** | Practice assessment evaluating network devices, topologies, and cloud concepts (Grade: 100%). |
| **TCP/IP & OSI Reference Models** | Comprehensive breakdown comparing the 4-layer TCP/IP suite against the 7-layer OSI model. |
| **[Test Your Knowledge: Network Communication](#-)** | Practice assignment assessing protocol layers, encapsulation, and packet routing mechanics (Grade: 80%). |
| **IP Addressing & Network Protocols** | Reading on network-layer addressing (IPv4 vs. IPv6), subnetting concepts, and packet headers. |
| **[Module Challenge 1 Graded Assessment](#-)** | Comprehensive evaluation covering network hardware, TCP/IP vs. OSI models, IP addressing, and SDN architectures (Grade: 80%). |

---

## 💡 Visual Pipeline Reference

The network protocol stacking and data encapsulation flow governing Module 1:

- **Protocol Encapsulation Pipeline**:

  $$\text{Application Data} \xrightarrow{\text{Transport (TCP/UDP Header)}} \text{Segment} \xrightarrow{\text{Internet (IP Header)}} \text{Packet} \xrightarrow{\text{Network Interface (MAC Frame)}} \text{Bits on Wire}$$

- **TCP/IP vs. OSI Layer Mapping Matrix**:

| TCP/IP Layer (4-Layer Model) | Corresponding OSI Layer (7-Layer Model) | Key Protocols / Telemetry |
| :--- | :--- | :--- |
| **4. Application** | **7. Application, 6. Presentation, 5. Session** | HTTP, HTTPS, DNS, SSH, FTP, DHCP |
| **3. Transport** | **4. Transport** | TCP (Connection-oriented), UDP (Connectionless) |
| **2. Internet** | **3. Network** | IPv4, IPv6, ICMP, ARP, IPsec |
| **1. Network Access / Interface** | **2. Data Link, 1. Physical** | Ethernet, Wi-Fi (802.11), MAC Addresses, Cables |

---

## 🎯 Technical Skills Architecture

### 📊 Network Architecture & Protocol Analysis
- **Protocol Layering:** Mapping data transmission steps across the TCP/IP and OSI stack to troubleshoot connectivity issues.
- **Network Hardware Identification:** Selecting appropriate physical and virtual appliances (switches, routers, firewalls) for secure network segmentation.
- **Cloud & SDN Management:** Understanding virtualization, cloud VPC configurations, and centralized SDN controller architectures.

### 🤖 Applied Practice & Professional Readiness
- **Network Topology Design:** Diagramming local area network layouts while accounting for gateway routers and internal switches.
- **Addressing & Subnet Analysis:** Identifying public vs. private IP ranges, MAC addressing schemas, and packet routing paths.
- **Tool Selection:** Utilizing command-line network diagnostic tools (`ping`, `traceroute`, `ipconfig`/`ifconfig`) to verify connectivity.

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Core Protocols & Architecture | Network Diagnostics & Virtualization | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Google Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=flat&logo=google&logoColor=white) | ![TCP/IP & OSI](https://img.shields.io/badge/Protocols-TCP%2FIP_%7C_OSI_Model-orange?style=flat) | ![Networking Tools](https://img.shields.io/badge/Stack-SDN_%7C_IPv4%2FIPv6_%7C_Cloud-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
