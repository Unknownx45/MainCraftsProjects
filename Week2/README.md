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

### 🧰 Research Sources
- [IBM Cost of Data Breach Report 2024](https://www.ibm.com/security/data-breach)
- [CISA Known Exploited Vulnerabilities](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- [Verizon DBIR 2024](https://www.verizon.com/business/resources/reports/dbir/)
- [ENISA Threat Landscape 2024](https://www.enisa.europa.eu/publications/enisa-threat-landscape-2024)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)

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

### ⚙️ Lab Components

| Component | Details |
|-----------|---------|
| **Host OS** | Windows 10 x64 |
| **Hypervisor** | VMware Workstation |
| **Attacker VM** | Kali Linux (64-bit, 4GB RAM, 8 vCPUs) |
| **Target App** | OWASP Juice Shop via Docker |
| **Target URL** | http://localhost:3000 |
| **Network 1** | VMnet8 — NAT (internet access) |
| **Network 2** | VMnet1 — Host-Only (isolated lab traffic) |

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

### 🛠️ Tools Validated

- **Nmap v7.95** — Network discovery and host scanning
- **Burp Suite Community v2025.10.6** — HTTP interception and proxy
- **Wireshark** — Live packet capture and analysis
- **Docker** — Container deployment and management

### 📂 File
```
📄 Cybersecurity_Lab_Build_Report_Task2_VivekRaj.pdf
```

---

## 🗂️ Repository Structure

```
📂 MainCraftsProjects/
 ├── 📄 README.md
 ├── 📄 Cybersecurity_Threat_Report_Task1_VivekRaj.pdf
 └── 📄 Cybersecurity_Lab_Build_Report_Task2_VivekRaj.pdf
```

---

## 🔗 Connect

- 🌐 **Organization:** [Maincrafts Technology](https://maincrafts.com)
- 💼 **LinkedIn:** [Vivek Raj](https://www.linkedin.com/in/unknownx45/)

---

> *All tasks completed as part of the Maincrafts Cybersecurity & Ethical Hacking Internship Program. Lab work was performed in a fully isolated virtual environment with no impact on real-world systems.*