VAPT Methodology

📌 Overview

This document outlines the methodology followed during the Vulnerability Assessment and Penetration Testing (VAPT) process for Week 3. The approach is aligned with standard industry practices such as PTES and OWASP Testing Guide.

---

🧭 Phases of VAPT

1. Reconnaissance

- Identified target environment (DVWA, Metasploitable2)
- Gathered basic information such as IP address and services

---

2. Scanning & Enumeration

- Scanned target for open ports and services
- Identified potential vulnerabilities
- Tools used: Nmap (basic), manual observation

---

3. Exploitation

- Used Metasploit Framework to exploit vulnerabilities
- Configured exploit modules and payloads
- Successfully executed exploit to gain access

---

4. Post-Exploitation

- Established Meterpreter session
- Collected system information ("sysinfo", "getuid")
- Attempted privilege escalation

---

5. Web Application Testing

- Tested DVWA for vulnerabilities:
  - Cross-Site Scripting (XSS)
  - SQL Injection
- Used manual testing and tools like Burp Suite

---

6. Evidence Collection

- Captured screenshots of all attack stages
- Collected logs of exploitation
- Captured network traffic using Wireshark

---

7. Reporting

- Documented findings in structured format
- Included screenshots and logs as proof
- Suggested basic remediation steps

---

🎯 Conclusion

The VAPT process was successfully executed following a structured methodology, covering all major phases from reconnaissance to reporting.
