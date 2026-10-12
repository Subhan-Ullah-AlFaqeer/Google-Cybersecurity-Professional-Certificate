# 🛡️ Course 6, Module 2: Network Monitoring and Analysis

Welcome to **Module 2** of **Sound the Alarm: Detection and Response** (Course 6 of the Google Cybersecurity Professional Certificate)! This module delivers a hands-on exploration of network traffic monitoring, packet sniffing, protocol analysis, and threat detection. You will examine network traffic flow baselines, investigate data exfiltration mechanics, dissect IP/TCP packet headers, and construct targeted filtering expressions using command-line (`tcpdump`) and graphical (Wireshark) network protocol analyzers to expose malicious communications.

---

## 📝 Core Technical Objectives
- **Network Traffic Flows & Exfiltration Detection:** Monitoring baseline network traffic patterns to identify anomalous volume spikes, unauthorized outbound connections, and covert data exfiltration attempts.
- **Packet Capture (PCAP) & Header Inspection:** Dissecting network packet structures, including Ethernet frames, IP headers (TTL, source/destination IPs), TCP headers (ports, sequence numbers, flags: SYN, ACK, FIN, RST), and protocol payloads.
- **Command-Line Packet Analysis with `tcpdump`:** Utilizing `tcpdump` flags (`-i`, `-n`, `-r`, `-w`, `-v`) and Boolean filtering expressions (host, net, port, proto) to capture and analyze raw network traffic streams directly from the terminal.
- **Protocol Analyzer Evaluation & Filtering:** Comparing command-line analyzers with graphical tools like Wireshark, applying display filters, and executing packet captures to investigate network protocol security breaches.

---

## 🧪 Module Learning Assets & Assessment Matrix

This module's core video lectures, readings, practical packet capture labs, research assignments, and knowledge checks are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Network Traffic Flows & Data Exfiltration** | Overview of continuous network monitoring, baseline traffic profiling, and detecting exfiltration techniques. |
| **[Test Your Knowledge: Network Traffic](#-)** | Practice assignment evaluating traffic flow monitoring, baselining, and exfiltration attack indicators (Grade: 75%). |
| **Packet Anatomy & Header Deep Dive** | Video and reading series analyzing Ethernet frames, IP packet header fields, TCP flags, and payload structures. |
| **[Activity: Analyze Your First Packet](#-)** | Practical lab inspecting PCAP files, examining header values, and decoding protocol fields (Completed). |
| **[Test Your Knowledge: Capture & View Traffic](#-)** | Practice assignment assessing PCAP file structures, header fields, and protocol inspection mechanics (Grade: 100%). |
| **Packet Captures with `tcpdump`** | Hands-on walkthrough of `tcpdump` command syntax, capture flags, output formatting, and PCAP file writing. |
| **[Activity: Capture Your First Packet](#-)** | Terminal lab executing `tcpdump` commands to capture active interface traffic and filter by port/IP (Completed). |
| **[Test Your Knowledge: Packet Inspection](#-)** | Practice assignment evaluating `tcpdump` syntax, capture filters, and packet flag interpretation (Grade: 100%). |
| **[Activity: Research Network Protocol Analyzers](#-)** | Research assignment comparing `tcpdump` and Wireshark functionalities, filter syntax, and use cases (Grade: 100%). |
| **[Module 2 Challenge Graded Assessment](#-)** | Comprehensive end-of-module evaluation covering traffic flows, exfiltration, header analysis, `tcpdump`, and Wireshark (Grade: 100%). |

---

## 💡 Visual Pipeline Reference

The network traffic packet analysis and command-line filtering workflow governing Module 2:

- **Packet Inspection & Analysis Pipeline**:

$$\text{Raw Interface Traffic} \xrightarrow{\text{\texttt{tcpdump} / Wireshark}} \text{Header Extraction (IP / TCP Flags)} \xrightarrow{\text{Filter Application (\texttt{port 80 / ip.src})}} \text{Payload Inspection / Anomaly Identification}$$

- **Core Packet Filtering & Inspection Taxonomy**:

| Tool / Utility | Syntax / Filter Examples | Operational Use Case |
| :--- | :--- | :--- |
| **`tcpdump` (Capture Flags)** | `tcpdump -i eth0 -nn -v -r capture.pcap` | Capturing or reading packets without DNS resolution or verbose logging |
| **`tcpdump` (Filter Expressions)** | `tcpdump 'tcp port 80 and src host 192.168.1.50'` | Isolating specific HTTP traffic streams from a target host IP |
| **Wireshark (Display Filters)** | `ip.addr == 10.0.0.1 && tcp.flags.syn == 1` | Visually tracing TCP handshakes and investigating multi-stage streams |

---

## 🎯 Technical Skills Architecture

### 📊 Packet Forensics & Traffic Inspection
- **Header Field Analysis:** Reading TTL values, IP addresses, TCP flags, and port numbers to reconstruct network communications.
- **`tcpdump` Command Construction:** Drafting precise terminal filtering commands to parse packet dumps efficiently during incident triage.
- **Traffic Anomaly Triage:** Identifying rogue connections, port scans, and unauthorized protocol tunneling within packet traces.

### 🤖 Applied Practice & Professional Readiness
- **Exfiltration Detection:** Spotting large, encrypted outbound payload streams originating from sensitive internal servers.
- **Protocol Analyzer Choice:** Knowing when to deploy lightweight command-line utilities (`tcpdump`) versus rich GUI tools (Wireshark).
- **Incident Response Evidence Capture:** Saving filtered network streams to `.pcap` files for forensic auditing and SOC reporting.

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Capture & Inspection Tools | Protocols & Packet Layers | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Google Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=flat&logo=google&logoColor=white) | ![tcpdump & Wireshark](https://img.shields.io/badge/Tools-tcpdump_%7C_Wireshark-orange?style=flat) | ![Packet Headers](https://img.shields.io/badge/Stack-Ethernet_%7C_IP_%7C_TCP_Flags_%7C_PCAP-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
