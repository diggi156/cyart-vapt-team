# 🔐 Security Assessment & VAPT Capstone Project

## 📌 Project Overview
This project demonstrates a complete **Security Assessment and VAPT (Vulnerability Assessment & Penetration Testing)** process using open-source tools in a controlled lab environment.

The goal is to identify, analyze, and report vulnerabilities without using paid tools.

---

## 🎯 Objectives
- Understand Security Assessment concepts
- Perform Vulnerability Assessment & Penetration Testing
- Apply Risk Assessment techniques (CVSS, Risk Matrix)
- Follow standard VAPT methodology
- Create a professional security report

---

## 🧠 Theoretical Concepts

### 1. Security Assessment
- Identifying system vulnerabilities using frameworks

**Types:**
- Vulnerability Assessment → OpenVAS  
- Penetration Testing → Metasploit, Nmap  
- Compliance Testing → CIS Benchmarks  

---

### 2. VAPT Methodology

#### Phases:
1. Planning → Define scope (Dradis CE)  
2. Discovery → Nmap, OWASP ZAP  
3. Attack → Metasploit  
4. Reporting → Documentation  

---

### 3. Security Standards
- GDPR  
- HIPAA  
- ISO 27001  
- OWASP Top 10  

---

### 4. Risk Assessment
- CVSS Scoring System  
- Risk Matrix (High / Medium / Low)  

---

### 5. Common Vulnerabilities
- Network → Open ports, misconfiguration  
- Web → SQL Injection, XSS  

**Practice Labs:**
- Metasploitable  
- VulnHub  
- OWASP Juice Shop  

---

### 6. Documentation Tools
- Dradis CE  
- CherryTree  
- Excel / Google Sheets  

---

## ⚙️ Practical Implementation

### 🖥️ 1. Setup Lab Environment
- Install Kali Linux  
- Install VirtualBox  
- Download Metasploitable 3  

---

### 🔍 2. Vulnerability Scanning

**Tools:**
- OpenVAS  
- Nikto  

**Command:**
```bash
sudo openvas-start
