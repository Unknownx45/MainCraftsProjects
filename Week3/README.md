# 🛡️ Maincrafts Cybersecurity & Ethical Hacking Internship
### Vivek Raj | Maincrafts Technology | 2026

---

## 👤 Intern Details

| Field | Details |
|-------|---------|
| **Name** | Vivek Raj |
| **Program** | Cybersecurity & Ethical Hacking Internship |
| **Organization** | Maincrafts Technology |
| **GitHub** | [Unknownx45](https://github.com/Unknownx45) |
| **LinkedIn** | [Vivek Raj](https://www.linkedin.com/in/unknownx45/) 

---

## 📁 Tasks Overview

| Task | Title | Status |
|------|-------|--------|
| Task 1 | Threat Intelligence Report | ✅ Completed |
| Task 2 | Build Your Personal Cybersecurity Lab | ✅ Completed |
| Task 3 | Vulnerability Scanning & Assessment | ✅ Completed |

---

## 📄 Task 1 — Threat Intelligence Report

**Objective:** Research and present a comprehensive Threat Intelligence Report covering the most critical cybersecurity threats of 2024–2025.

### 🔴 5 Cyber Threats Covered

| # | Threat | Severity |
|---|--------|----------|
| 1 | 🤖 AI-Powered Phishing Attacks | CRITICAL (9.2/10) |
| 2 | 💰 Ransomware-as-a-Service (RaaS) | CRITICAL (9.5/10) |
| 3 | ☁️ Cloud Security Misconfigurations | HIGH (8.4/10) |
| 4 | 📡 IoT Vulnerabilities | HIGH (8.1/10) |
| 5 | 🕳️ Zero-Day Exploits | CRITICAL (9.8/10) |

### 🔍 Real-World Case Studies

| Incident | Year | Impact |
|----------|------|--------|
| MGM Resorts (Scattered Spider) | 2023–2024 | $100M+ loss |
| Colonial Pipeline (DarkSide RaaS) | 2021 | $4.4M ransom, US fuel crisis |
| Capital One Cloud Breach | 2019 | 106M records exposed |
| Mirai Botnet (Dyn DDoS) | 2016 | US East Coast internet outage |
| SolarWinds Supply Chain | 2020 | 18,000+ organisations compromised |

### 📂 File
```
📄 Cybersecurity_Threat_Report_Task1_VivekRaj.pdf
```

---

## 🧪 Task 2 — Personal Cybersecurity Lab Build

**Objective:** Build a safe and fully isolated personal cybersecurity practice environment to serve as the foundation for all future hands-on tasks.

### 🖥️ Lab Architecture

```
+--------------------------------------------------+
|           Host System — Windows 10 x64           |
|                                                  |
|   └── VMware Workstation                         |
|         ├── Kali Linux VM (Attacker)             |
|         └── OWASP Juice Shop via Docker (Target) |
|                                                  |
|   Networks:                                      |
|     • VMnet8 NAT       → Internet / Updates      |
|     • VMnet1 Host-Only → Isolated Lab Traffic    |
+--------------------------------------------------+
```

### ✅ Evidence Collected

| # | Evidence Item | Status |
|---|--------------|--------|
| 1 | VMware Virtual Network Editor (NAT + Host-Only) | ✅ Verified |
| 2 | Kali Linux VM — apt update/upgrade + lab folders | ✅ Verified |
| 3 | Docker installation and service enabled | ✅ Verified |
| 4 | OWASP Juice Shop running at localhost:3000 | ✅ Verified |
| 5 | Dual IP configuration (NAT + Host-Only) | ✅ Verified |
| 6 | Nmap scan — 4 hosts discovered on Host-Only subnet | ✅ Verified |
| 7 | Burp Suite intercepting HTTP traffic from Juice Shop | ✅ Verified |
| 8 | Wireshark capturing live packets on eth0 | ✅ Verified |

### 📂 File
```
📄 Cybersecurity_Lab_Build_Report_Task2_VivekRaj.pdf
```

---

## 🔍 Task 3 — Vulnerability Scanning & Assessment

**Objective:** Perform a professional-grade vulnerability assessment on OWASP Juice Shop using industry-standard tools, and document findings in a formal Vulnerability Assessment Report (VAR).

### 🎯 Target System

| Field | Details |
|-------|---------|
| **Target** | OWASP Juice Shop |
| **URL** | http://localhost:3000 |
| **Environment** | Kali Linux VM — Isolated Lab |
| **Date** | April 2026 |

### 🛠️ Tools Used

| Tool | Version | Purpose |
|------|---------|---------|
| Nmap | v7.95 | Host discovery, port & service enumeration |
| Nikto | v2.5.0 | Web server misconfiguration detection |
| Dirsearch | v0.4.3 | Hidden endpoint & directory discovery |
| Burp Suite | v2025.10.6 | HTTP traffic interception & verification |

### 📊 Findings Summary

| Risk Level | Count | Finding IDs |
|-----------|-------|-------------|
| 🔴 CRITICAL | 3 | F-01, F-02, F-03 |
| 🟠 HIGH | 5 | F-04, F-05, F-06, F-07, F-08 |
| 🟡 MEDIUM | 5 | F-09, F-10, F-11, F-12, F-13 |
| 🟢 LOW / INFO | 4 | F-14, F-15, F-16, F-17 |
| **Total** | **17** | |

### 🔴 Critical Findings

| ID | Finding | Risk |
|----|---------|------|
| F-01 | Exposed API Documentation (Swagger/OpenAPI) — publicly accessible without auth | CRITICAL |
| F-02 | Publicly Accessible FTP Directory (/ftp) — returns HTTP 200 | CRITICAL |
| F-03 | Unauthenticated GraphQL Endpoint (/api/cask/graphql) | CRITICAL |

### 🟠 High Findings

| ID | Finding | Risk |
|----|---------|------|
| F-04 | Missing X-Content-Type-Options Header | HIGH |
| F-05 | Overly Permissive CORS Policy (Allow-Origin: *) | HIGH |
| F-06 | Exposed Configuration Endpoint (/api/config) | HIGH |
| F-07 | Error Log Endpoint Publicly Accessible (/api/error_log) | HIGH |
| F-08 | Sensitive Admin API Endpoints Exposed (/rest/admin/*) | HIGH |

### 📂 File
```
📄 Vulnerability_Assessment_Report_Task3_VivekRaj.pdf
```

---

## 🗂️ Repository Structure

```
📂 MainCraftsProjects/
 ├── 📄 README.md
 ├── 📄 Cybersecurity_Threat_Report_Task1_VivekRaj.pdf
 ├── 📄 Cybersecurity_Lab_Build_Report_Task2_VivekRaj.pdf
 └── 📄 Vulnerability_Assessment_Report_Task3_VivekRaj.pdf
```

---

## 🔗 Connect

- 🌐 **Organization:** [Maincrafts Technology](https://www.maincrafts.com)
- 📧 **Contact:** hr@maincrafts.com

---

> *All tasks completed as part of the Maincrafts Cybersecurity & Ethical Hacking Internship Program. All scanning and assessment activities were performed exclusively within an isolated lab environment with no impact on real-world systems.*
