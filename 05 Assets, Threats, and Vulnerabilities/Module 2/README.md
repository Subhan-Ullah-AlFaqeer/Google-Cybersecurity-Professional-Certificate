# 🛡️ Course 5, Module 2: Protect Organizational Assets

Welcome to **Module 2** of **Assets, Threats, and Vulnerabilities** (Course 5 of the Google Cybersecurity Professional Certificate)! This module delivers an operational dive into data protection controls, compliance, cryptography, and Identity and Access Management (IAM). You will examine the principle of least privilege, compliance regulations governing Personally Identifiable Information (PII), symmetric/asymmetric encryption, Public Key Infrastructure (PKI), non-repudiation via cryptographic hashing, and AAA (Authentication, Authorization, Accounting) frameworks including MFA and Single Sign-On (SSO).

---

## 📝 Core Technical Objectives
- **Data Lifecycle & Privacy Compliance:** Implementing proper data handling practices across the data lifecycle, enforcing the Principle of Least Privilege, and understanding privacy regulations (GDPR, HIPAA, CCPA) governing PII protection.
- **Cryptography & Public Key Infrastructure (PKI):** Differentiating between symmetric encryption (AES) and asymmetric encryption (RSA, ECC), understanding certificate authorities in PKI, and practicing message decryption in hands-on labs.
- **Hashing & Non-Repudiation:** Generating and verifying cryptographic hashes (SHA-256, MD5) to ensure data integrity, detect tampering, and uphold non-repudiation.
- **Access Controls & IAM Architecture:** Designing robust Identity and Access Management (IAM) systems incorporating Multi-Factor Authentication (MFA), Single Sign-On (SSO), Role-Based Access Control (RBAC), and auditing user activities via accounting logs.

---

## 🧪 Module Learning Assets & Assessment Matrix

This module's core video lectures, readings, practical labs, portfolio assignments, and knowledge checks are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Data Safeguards & Privacy Compliance** | Overview of least privilege, PII security, regulatory compliance, and data lifecycle management. |
| **[Activity: Determine Data Handling Practices](#-)** | Practical exercise establishing policy guidelines and security controls for sensitive enterprise data (Grade: 100%). |
| **[Test Your Knowledge: Safeguard Information](#-)** | Practice assignment evaluating privacy regulations, data classification, and least privilege enforcement (Grade: 93.75%). |
| **Cryptography, PKI & Encryption Labs** | Deep dive into symmetric vs. asymmetric encryption algorithms, digital certificates, and PKI dynamics. |
| **[Activity: Decrypt an Encrypted Message](#-)** | Hands-on lab using cryptographic tools to decrypt secure payloads and verify message secrecy (Completed). |
| **[Activity: Create Hash Values](#-)** | Applied terminal lab generating cryptographic hashes to verify file integrity and detect modifications (Completed). |
| **[Test Your Knowledge: Encryption Methods](#-)** | Practice assignment assessing hashing algorithms, PKI mechanisms, and encryption applications (Grade: 100%). |
| **Access Controls, IAM & Authentication** | Exploration of AAA framework controls, MFA factors, SSO protocols, authorization mechanisms, and audit logging. |
| **[Activity: Improve AAA for a Small Business](#-)** | Practical assignment optimizing authentication, authorization, and accounting controls for a business environment (Grade: 100%). |
| **[Test Your Knowledge: AAA Controls](#-)** | Practice assignment evaluating MFA, SSO, RBAC, and user activity auditing (Grade: 100%). |
| **[Module 2 Challenge Graded Assessment](#-)** | Comprehensive end-of-module evaluation covering privacy compliance, PKI, encryption, hashing, and IAM architecture (Grade: 85%). |

---

## 💡 Visual Pipeline Reference

The cryptography and identity access control lifecycle governing Module 2:

- **Asymmetric Encryption & PKI Flow**:

$$\text{Plaintext} \xrightarrow{\text{Recipient Public Key}} \text{Ciphertext (Transmitted)} \xrightarrow{\text{Recipient Private Key}} \text{Plaintext}$$

- **AAA Security Framework Taxonomy**:

| AAA Component | Core Security Function | Practical Implementation Example |
| :--- | :--- | :--- |
| **Authentication** | Verifying user identity claims | Multi-Factor Authentication (MFA), SSO (SAML 2.0 / OAuth 2.0) |
| **Authorization** | Enforcing permission boundaries | Role-Based Access Control (RBAC), Attribute-Based Access Control (ABAC) |
| **Accounting** | Logging user activity for audit trails | SIEM log generation, user behavior auditing, access review logs |

---

## 🎯 Technical Skills Architecture

### 📊 Cryptography & Data Protection
- **Encryption Implementation:** Selecting appropriate encryption models (symmetric for fast bulk storage, asymmetric for key exchange).
- **Integrity Verification:** Computing cryptographic hashes (SHA-256) to validate data authenticity and prevent unauthorized modifications.
- **Compliance Alignment:** Enforcing regulatory mandates (GDPR, HIPAA) by identifying and isolating sensitive PII assets.

### 🤖 Applied Practice & Professional Readiness
- **IAM Policy Design:** Configuring authentication and access rules based on least privilege and separation of duties.
- **Credential & Session Security:** Deploying MFA and SSO mechanisms to reduce password fatigue and mitigate credential stuffing.
- **Audit Logging:** Reviewing accounting telemetry to verify non-repudiation and detect unauthorized permission escalation.

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Cryptography & Hashing Tools | IAM & Compliance Standards | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Google Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=flat&logo=google&logoColor=white) | ![Cryptography](https://img.shields.io/badge/Crypto-AES_%7C_RSA_%7C_SHA--256-orange?style=flat) | ![IAM & Privacy](https://img.shields.io/badge/IAM-MFA_%7C_SSO_%7C_GDPR_%7C_PII-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
