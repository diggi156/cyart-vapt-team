Capstone Project: Full VAPT Assessment on Metasploitable

Objective

The objective of this project is to perform a complete Vulnerability Assessment and Penetration Testing (VAPT) on a target system to identify and exploit security vulnerabilities.

Environment Setup

- Attacker Machine: Kali Linux
- Target Machine: Metasploitable
- Network: 192.168.1.0/24

Methodology

1. Exploitation

Metasploit Framework was used to exploit the VSFTPD service vulnerability, resulting in initial shell access to the target system.

2. Web Application Testing

Burp Suite was used to test DVWA, where vulnerabilities such as Cross-Site Scripting (XSS) and Broken Object Level Authorization (BOLA) were identified.

3. Privilege Escalation

LinPEAS was executed to enumerate the system, and a vulnerable SUID binary was exploited to gain root access.

4. Network Attacks

Responder was used to capture NTLM hashes, and Ettercap was used to perform ARP spoofing. Wireshark was used to analyze captured network traffic.

Findings

- Remote Code Execution vulnerability
- Improper access control (BOLA)
- Privilege escalation via SUID binaries
- Network-level vulnerabilities

Remediation

- Patch vulnerable services
- Implement strong authentication
- Restrict SUID permissions
- Secure network configurations

Conclusion

The VAPT assessment successfully demonstrated multiple critical vulnerabilities, highlighting the need for proper security measures and continuous monitoring.
