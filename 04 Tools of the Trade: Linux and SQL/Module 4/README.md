# 🛡️ Course 4, Module 4: Databases and SQL

Welcome to **Module 4** (the final module) of **Tools of the Trade: Linux and SQL** (Course 4 of the Google Cybersecurity Professional Certificate)! This module provides an operational deep dive into Structured Query Language (SQL) and relational databases. You will learn how security analysts query databases, filter security logs using conditions and logical operators (`AND`, `OR`, `NOT`), analyze numerical and date-based telemetry, combine data across tables using SQL Joins (`INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL OUTER JOIN`), and execute a high-impact portfolio activity filtering security event logs to detect threat indicators.

---

## 📝 Core Technical Objectives
- **Relational Databases & SQL Syntax:** Understanding database structures, schema relationships, tables, records, fields, and executing basic queries (`SELECT`, `FROM`).
- **SQL Data Filtering & Logical Operators:** Applying the `WHERE` clause alongside comparison operators (`=`, `>`, `<`, `>=`, `<=`, `<>`), string wildcards (`LIKE`, `%`, `_`), and logical operators (`AND`, `OR`, `NOT`) to isolate relevant security events.
- **Filtering Dates & Numerical Ranges:** Querying timestamps, log ranges, IP subsets, and event severity numbers to investigate incident windows.
- **Table Joins & Cross-Table Forensics:** Combining multiple database tables using relational joins (`INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`) to correlate user identities, host machines, and login records.
- **SQL Portfolio Project Execution:** Practicing hands-on database log triage to investigate security incidents and document query findings for leadership.

---

## 🧪 Module Learning Assets & Assessment Matrix

This module's core video lectures, readings, practical SQL labs, portfolio activities, and knowledge checks are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Intro to Databases & Basic Queries** | Video and reading series introducing database concepts, tables, fields, `SELECT`, and `FROM` syntax. |
| **[Test Your Knowledge: SQL & Databases](#-)** | Practice assignment evaluating relational database mechanics and fundamental query structures (Grade: 100%). |
| **Basic SQL Filtering (`WHERE` Clause)** | Deep dive into filtering queries using basic comparison operators and wildcards (`LIKE`). |
| **[Activity: Perform & Filter a SQL Query](#-)** | Practical lab constructing SQL queries with specific column outputs and basic conditional filters (Completed). |
| **[Test Your Knowledge: SQL Queries](#-)** | Practice assignment assessing query syntax, basic filters, and SQL vs. Linux filtering mechanisms (Grade: 100%). |
| **Filtering Dates, Numbers & Logical Operators** | Video and reading series on filtering timestamp ranges and combining conditions with `AND`, `OR`, `NOT`. |
| **[Portfolio Activity: Apply Filters to SQL Queries](#-)** | High-impact portfolio project crafting complex filtered queries to extract suspicious security logs (Grade: 100%). |
| **[Test Your Knowledge: More SQL Filters](#-)** | Practice assignment evaluating date ranges, logical operator precedence, and numerical comparisons (Grade: 100%). |
| **SQL Table Joins (`INNER`, `LEFT`, `RIGHT`, `FULL`)** | Exploration of relational joins (`ON` clause) to combine logs across user, asset, and network databases. |
| **[Activity: Complete a SQL Join](#-)** | Hands-on lab writing `INNER JOIN` and `LEFT JOIN` queries to correlate security telemetry (Completed). |
| **[Test Your Knowledge: SQL Joins](#-)** | Practice assignment assessing join selection logic and multi-table query structures (Grade: 75%). |
| **Coach Dialogue & Module Challenge** | Interactive scenario dialogue and end-of-module assessment evaluating SQL log analysis capabilities (Grade: 100%). |

---

## 💡 Visual Pipeline Reference

The relational database query processing and multi-table join pipeline governing Module 4:

- **Relational SQL Telemetry Pipeline**:

$$\text{Raw Security Logs} \xrightarrow{\text{\texttt{SELECT ... FROM}}} \text{Database Tables} \xrightarrow{\text{\texttt{JOIN ... ON}}} \text{Correlated Records} \xrightarrow{\text{\texttt{WHERE AND/OR/NOT}}} \text{Threat Indicators}$$

- **Core SQL Join Types Taxonomy**:

| Join Type | Operational Function | Security Analyst Application |
| :--- | :--- | :--- |
| **`INNER JOIN`** | Returns records with matching values in both tables | Correlating user account IDs with confirmed alert logs |
| **`LEFT JOIN`** | Returns all records from left table, and matched from right | Listing all assets regardless of whether an alert was triggered |
| **`RIGHT JOIN`** | Returns all records from right table, and matched from left | Listing all security alerts regardless of asset record status |
| **`FULL OUTER JOIN`** | Returns all records when there is a match in either table | Auditing complete system records and unlinked log entries |

---

## 🎯 Technical Skills Architecture

### 📊 SQL Database Querying & Log Triage
- **Query Construction:** Drafting well-structured SQL statements using `SELECT`, `FROM`, `WHERE`, `LIKE`, and `ORDER BY`.
- **Conditional Filtering:** Combining multiple logical conditions (`AND`, `OR`, `NOT`) to narrow down thousands of log rows to precise incident indicators.
- **Data Correlation:** Writing relational `JOIN` queries to merge user profiles, access logs, and network events across enterprise databases.

### 🤖 Applied Practice & Professional Readiness
- **Database Log Investigation:** Identifying unauthorized login attempts, out-of-hours file access, and suspicious IP ranges in database tables.
- **Portfolio Demonstration:** Documenting custom SQL queries and analysis outcomes as part of a job-ready cybersecurity portfolio.
- **Cross-Platform Competency:** Leveraging both Linux CLI text processing (`grep`, `awk`) and SQL queries depending on raw file vs. relational log storage.

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Relational Database Systems | Query & Filter Stack | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Google Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=flat&logo=google&logoColor=white) | ![SQL Relational](https://img.shields.io/badge/Databases-MariaDB_%7C_PostgreSQL_%7C_SQLite-orange?style=flat&logo=sqlite&logoColor=white) | ![SQL Syntax](https://img.shields.io/badge/Syntax-SELECT_%7C_WHERE_%7C_JOINS-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
