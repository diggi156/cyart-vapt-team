# 🔐 CYART VAPT TEAM - Week 2 Capstone Project

## 📌 Project Overview
This repository contains **Week 2 activities** of the VAPT (Vulnerability Assessment & Penetration Testing) program.

The project demonstrates a **complete VAPT lifecycle**, including:
- Vulnerability Scanning
- Reconnaissance (OSINT)
- Exploitation
- Post-Exploitation
- Reporting

All tasks are performed in a **controlled lab environment using open-source tools**.

---

## 🎯 Objectives
- Learn advanced vulnerability scanning techniques
- Perform structured penetration testing
- Understand exploit development basics
- Execute full VAPT cycle
- Document findings professionally

---

## 🧠 Theoretical Knowledge

### 1. Vulnerability Scanning Techniques
**Core Concepts:**
- Scan Types:
  - Network Scanning → Nmap
  - Web Application Scanning → Nikto
  - Authenticated vs Unauthenticated Scans  
- Vulnerability Scoring:
  - CVSS v4.0 (e.g., CVSS 8.8 = High Risk)
- False Positives:
  - Manual validation required  

**Example:**
- Apache Struts (CVE-2017-5638) → Critical  

---

### 2. Penetration Testing Techniques

**Phases:**
1. Reconnaissance (OSINT using Shodan)
2. Scanning (Nmap, Nessus)
3. Exploitation (Metasploit)
4. Post-Exploitation (Privilege Escalation)
5. Reporting  

**Methodologies:**
- PTES  
- OWASP WSTG  

**Ethics:**
- Always perform testing with proper authorization  

---

### 3. Exploit Development Basics

**Concepts:**
- Exploit Types:
  - Buffer Overflow  
  - SQL Injection  
  - Cross-Site Scripting (XSS)  

- Mitigations:
  - ASLR  
  - WAF  
  - Patch Management  

---

## ⚙️ Practical Implementation

---

### 🔍 1. Vulnerability Scanning Lab

**Tools Used:**
- Nmap  
- OpenVAS  
- Nikto  

**Example Scan Command:**
```bash
nmap -sV 192.168.1.100
