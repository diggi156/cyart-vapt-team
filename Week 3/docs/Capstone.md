Capstone Project – Full VAPT Cycle

📌 Overview

This capstone project demonstrates a complete Vulnerability Assessment and Penetration Testing (VAPT) cycle performed on a vulnerable machine in a controlled lab environment.

---

🎯 Objective

To simulate a real-world penetration test by identifying, exploiting, and documenting vulnerabilities.

---

🧭 Methodology Followed

1. Reconnaissance
2. Scanning & Enumeration
3. Exploitation
4. Post-Exploitation
5. Reporting

---

⚙️ Activities Performed

🔹 1. Scanning

- Performed network scan using Nmap
- Identified open ports and services

🔹 2. Exploitation

- Used Metasploit Framework
- Exploited vulnerable service (vsftpd 2.3.4)
- Gained shell access

🔹 3. Post-Exploitation

- Verified access using system commands
- Attempted privilege escalation

🔹 4. Web Testing

- Tested DVWA for:
  - XSS
  - SQL Injection

🔹 5. Evidence Collection

- Captured screenshots (Figure 1–7)
- Recorded logs
- Captured network traffic

---

📊 Findings Summary

ID| Vulnerability| Severity| Status
F001| XSS| Medium| Exploited
F002| SQL Injection| High| Identified
F003| FTP Backdoor| Critical| Exploited

---

🛡️ Remediation

- Sanitize user inputs
- Use prepared statements for SQL queries
- Update vulnerable services
- Enforce strong authentication

---

🎯 Outcome

Successfully completed a full VAPT cycle including scanning, exploitation, post-exploitation, and reporting.

---

⚠️ Disclaimer

This project was performed in a controlled lab environment for educational purposes only.
