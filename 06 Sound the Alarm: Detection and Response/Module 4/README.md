# 🛡️ Course 6, Module 4: Network Traffic and Logs Using IDS and SIEM Tools

Welcome to **Module 4** (the final module) of **Sound the Alarm: Detection and Response** (Course 6 of the Google Cybersecurity Professional Certificate)! This module provides an operational exploration of intrusion detection systems (IDS), log ingestion, signature creation, and enterprise SIEM platforms. You will examine the mechanics of signature-based and anomaly-based detection, write and inspect Suricata IDS rules, analyze alert logs (`eve.json`, `fast.log`), and master search queries across major enterprise SIEM tools, including Splunk (using Search Processing Language, SPL) and Google SecOps (Chronicle).

---

## 📝 Core Technical Objectives
- **Intrusion Detection Mechanics & Signature Components:** Understanding the operational differences between Network Intrusion Detection Systems (NIDS) and Host Intrusion Detection Systems (HIDS), signature-based vs. behavior-based detection, and decomposing signature rules into headers and options.
- **Suricata IDS Rule Construction & Log Analysis:** Inspecting Suricata rule syntax (action, protocol, source/destination IP & ports, direction, msg, sid, rev), modifying rule sets, and parsing generated logs (`eve.json`, `fast.log`) during suspicious traffic events.
- **SIEM Search & Querying with Splunk (SPL):** Executing basic search commands in Splunk using Search Processing Language (SPL), leveraging wildcards, boolean operators (`AND`, `OR`, `NOT`), field-value pairs, and transforming commands (`stats count by`) to triage security events.
- **Google SecOps (Chronicle) Log Analysis:** Navigating Chronicle SIEM dashboards, searching unified data models (UDM), tracing log timelines, and querying security telemetry across cloud and enterprise network environments.

---

## 🧪 Module Learning Assets & Assessment Matrix

This module's core video lectures, readings, practical terminal labs, interactive exercises, and knowledge checks are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Security Monitoring & Detection Tools** | Overview of intrusion detection architectures, threat signatures, and continuous monitoring practices. |
| **Suricata Rule Syntax & Signature Analysis** | Deep dive into Suricata header structure, rule options, SID identifiers, and log formatting (`eve.json`, `fast.log`). |
| **[Activity: Explore Signatures & Logs with Suricata](#-)** | Practical terminal lab examining Suricata rule files, generating alert logs, and filtering rule signatures (Completed). |
| **[Test Your Knowledge: Overview of IDS](#-)** | Practice assignment evaluating IDS types, detection engines, signature components, and Suricata workflows (Grade: 100%). |
| **Splunk Enterprise & SPL Querying** | Video and reading series covering Splunk architecture, index structures, field extraction, and SPL query construction. |
| **[Activity: Use Splunk to Search Logs](#-)** | Practical lab crafting SPL queries to isolate suspicious IP connections, failed login attempts, and abnormal port activity. |
| **[Test Your Knowledge: SIEM Platforms & Splunk](#-)** | Practice assignment assessing Splunk SPL syntax, wildcards, boolean filtering, and log correlation logic. |
| **Google SecOps (Chronicle) Telemetry Analysis** | Exploration of Google SecOps (Chronicle), Unified Data Models (UDM), search interfaces, and threat timeline tracking. |
| **[Activity: Search Telemetry in Google SecOps](#-)** | Hands-on lab searching enterprise security events and domain resolutions within Chronicle SIEM. |
| **[Test Your Knowledge: Google SecOps (Chronicle)](#-)** | Practice assignment evaluating UDM fields, Chronicle search filters, and cloud telemetry investigations. |
| **[Module 4 Challenge Graded Assessment](#-)** | Comprehensive end-of-module evaluation covering Suricata IDS rules, Splunk SPL, and Google SecOps log analysis. |

---

## 💡 Visual Pipeline Reference

The IDS alert generation and SIEM log ingestion pipeline governing Module 4:

- **IDS Alert to SIEM Analysis Pipeline**:

$$\text{Raw Packet Stream} \xrightarrow{\text{Suricata Rule Engine}} \text{Signature Match} \xrightarrow{\text{Log Output (\texttt{eve.json})}} \text{SIEM Ingestion (Splunk / Chronicle)} \xrightarrow{\text{SPL / UDM Query}} \text{Analyst Triage}$$

- **Suricata Rule Structure & SIEM Tool Taxonomy**:

| Environment / Tool | Key Syntax / Components | Practical Security Application |
| :--- | :--- | :--- |
| **Suricata Rule Header** | `alert http $HOME_NET any -> $EXTERNAL_NET any` | Defining action, protocol, IP range, and port directions |
| **Suricata Rule Options** | `(msg:"GET Request to Suspicious Domain"; sid:1000001; rev:1;)` | Custom alert messaging, unique Signature ID tracking, and revisioning |
| **Splunk (SPL Queries)** | `index=main sourcetype=access_* status=404 \| stats count by clientip` | Filtering web log errors and aggregating attempt counts by client IP |
| **Google SecOps (Chronicle)** | `metadata.event_type = "NETWORK_CONNECTION" target.ip = "192.168.1.1"` | Querying normalized Unified Data Model (UDM) events across enterprise assets |

---

## 🎯 Technical Skills Architecture

### 📊 IDS Rule Engineering & SIEM Log Triage
- **Suricata Signature Authoring:** Writing and tuning IDS signatures to detect malicious traffic patterns while minimizing false positives.
- **SPL Log Querying:** Utilizing Splunk Search Processing Language (SPL) to filter large volume log indexes during incident investigations.
- **Unified Data Model (UDM) Triage:** Navigating Chronicle SIEM to analyze normalized security logs across cloud and endpoint ecosystems.

### 🤖 Applied Practice & Professional Readiness
- **Log Format Parsing:** Deciphering structured logs (`JSON`, key-value pairs) generated by security appliances.
- **Alert Investigation:** Validating IDS rule alerts against SIEM aggregated events to confirm active network intrusion attempts.
- **Multi-SIEM Fluency:** Demonstrating adaptability across industry-standard SIEM tools (Splunk Enterprise and Google SecOps Chronicle).

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Intrusion Detection Systems | SIEM Platforms & Analytics | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Google Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=flat&logo=google&logoColor=white) | ![Suricata](https://img.shields.io/badge/IDS-Suricata_%7C_NIDS_%7C_Rules-orange?style=flat) | ![Splunk & Chronicle](https://img.shields.io/badge/SIEM-Splunk_SPL_%7C_Google_SecOps-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
