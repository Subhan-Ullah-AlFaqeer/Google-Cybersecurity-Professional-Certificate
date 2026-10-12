# 🛡️ Course 6, Module 1: Introduction to Detection and Incident Response

Welcome to **Module 1** of **Sound the Alarm: Detection and Response** (Course 6 of the Google Cybersecurity Professional Certificate)! This module launches your journey into security operations, threat detection, and incident handling. You will explore the NIST Incident Response (IR) lifecycle, examine the structure and roles within a Computer Security Incident Response Team (CSIRT), master the utility of incident handler journals for forensic documentation, and evaluate core SOC technologies including Intrusion Detection Systems (IDS), Security Information and Event Management (SIEM), and Security Orchestration, Automation, and Response (SOAR).

---

## 📝 Core Technical Objectives
- **NIST Incident Response Lifecycle:** Applying the four core phases of the NIST SP 800-61 Rev. 2 lifecycle:
  1. **Preparation:** Establishing tools, training, plans, and defensive controls.
  2. **Detection & Analysis:** Monitoring telemetry, triaging alerts, and verifying security incidents.
  3. **Containment, Eradication & Recovery:** Isolating affected systems, eliminating threat persistence, and restoring business operations.
  4. **Post-Incident Activity:** Conducting lessons-learned reviews and updating documentation.
- **CSIRT Roles & Response Plans:** Understanding team structures (Incident Commander, Lead Investigator, Scribe, PR Liaison) and executing predefined Incident Response Plans (IRPs) during crisis scenarios.
- **Incident Documentation & Journaling:** Authoring structured entries in an Incident Handler's Journal to capture precise timestamps, evidence hashes, containment steps, and escalation chains for legal and audit compliance.
- **Detection & Management Tech Stack:** Differentiating between network/host intrusion detection tools (IDS), centralized log ingestion via SIEM, and automated playbook orchestration via SOAR.

---

## 🧪 Module Learning Assets & Assessment Matrix

This module's core video lectures, readings, practice assignments, interactive scenarios, and portfolio deliverables are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Course 6 Orientation & Mentorship** | Program introduction, career growth insights with mentors, and course objectives overview. |
| **Incident Response Lifecycle & Vishing Scenario** | Video and interactive plugin mapping NIST IR phases to a real-world social engineering (vishing) attack. |
| **[Portfolio Activity: Incident Handler's Journal](#-)** | High-impact capstone portfolio project establishing a standardized incident handler journal to log active threats (Grade: 100%). |
| **[Test Your Knowledge: Incident Response Lifecycle](#-)** | Practice assignment evaluating NIST SP 800-61 stages and containment workflows (Grade: 75%). |
| **CSIRT Roles & Communication Protocols** | In-depth review of incident response team structures, cross-functional communication, and IRP execution. |
| **[Test Your Knowledge: Incident Response Operations](#-)** | Practice assessment evaluating incident command chains, operational roles, and IRP invocation criteria (Grade: 75%). |
| **Detection Tools, IDS & Documentation** | Video and reading series on Intrusion Detection Systems (NIDS/HIDS), evidence tracking, and log aggregation. |
| **[Test Your Knowledge: Detection & Documentation Tools](#-)** | Practice assignment assessing IDS placement, evidence chain of custody, and documentation hygiene (Grade: 87.50%). |
| **SIEM & SOAR Orchestration** | Deep dive into SIEM log correlation engines, event management, and automated SOAR playbooks. |
| **[Test Your Knowledge: Management Tools](#-)** | Practice assignment evaluating SIEM dashboard alerting, log normalization, and SOAR automation (Grade: 100%). |
| **[Module 1 Challenge Graded Assessment](#-)** | Comprehensive end-of-module evaluation covering the NIST IR framework, CSIRT operations, journals, and SIEM/SOAR platforms (Grade: 80%). |

---

## 💡 Visual Pipeline Reference

The NIST SP 800-61 Rev. 2 Incident Response Lifecycle and SIEM/SOAR processing workflow governing Module 1:

- **NIST Incident Response Lifecycle Pipeline**:

$$\text{1. Preparation} \longrightarrow \text{2. Detection \ Analysis} \rightleftarrows \text{3. Containment, Eradication \ Recovery} \longrightarrow \text{4. Post-Incident Activity}$$

- **Detection & Event Orchestration Taxonomy**:

| Technology / Tool | Operational Primary Function | Practical SOC Application |
| :--- | :--- | :--- |
| **IDS (NIDS / HIDS)** | Passively monitors network/host traffic against signature bases | Generating alerts on anomalous packet payloads or unauthorized file changes |
| **SIEM (Splunk, Chronicle)** | Centralizes, normalizes, and correlates logs across disparate assets | Providing single-pane visibility, threat queries, and real-time alert triggers |
| **SOAR (Cortex XSOAR)** | Automates incident enrichment and containment workflows | Executing automated playbooks (e.g., auto-isolating an infected host IP) |

---

## 🎯 Technical Skills Architecture

### 📊 Incident Handling & Documentation
- **Lifecycle Application:** Structuring threat response steps around the four NIST SP 800-61 phases.
- **Incident Journaling:** Authoring clean, chronological incident logs that capture attack vectors, indicators of compromise (IoCs), and remediation steps.
- **CSIRT Coordination:** Navigating command structures and communication channels during active network security incidents.

### 🤖 Applied Practice & Professional Readiness
- **SIEM Telemetry Analysis:** Navigating SIEM dashboards to interpret aggregated log events and correlate security triggers.
- **Automation Evaluation:** Identifying repetitive SOC workflows suitable for SOAR playbook automation.
- **Portfolio Demonstration:** Publishing a professional Incident Handler's Journal entry demonstrating readiness for Tier 1 SOC Analyst roles.

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Frameworks & Protocols | SOC Detection & Management Stack | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Google Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=flat&logo=google&logoColor=white) | ![NIST SP 800-61](https://img.shields.io/badge/Framework-NIST_SP_800--61_Rev._2-orange?style=flat) | ![SIEM & SOAR](https://img.shields.io/badge/Stack-IDS_%7C_SIEM_%7C_SOAR_%7C_Journaling-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
