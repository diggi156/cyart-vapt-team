# Privilege Escalation and Persistence

## 🎯 Objective

To understand techniques used to gain higher privileges on a system and maintain long-term access after exploitation.

---

## 🔍 Core Concepts

### 1. Privilege Escalation

Privilege escalation is the process of gaining elevated access (e.g., root or administrator) from a lower-privileged account.

**Types:**

* **Vertical Escalation:**
  Gaining higher privileges (user → root)

* **Horizontal Escalation:**
  Accessing another user's account with similar privileges

---

### 2. Common Techniques

#### 🔹 SUID Exploitation

* Files with SUID permission run with owner privileges (usually root)
* Misconfigured SUID binaries can be exploited

**Example:**
Using `/usr/bin/find` to execute a shell with root privileges

---

#### 🔹 Kernel Exploits

* Exploiting vulnerabilities in the operating system kernel
* Often leads to full system compromise

---

#### 🔹 Weak Permissions

* Writable system files
* Misconfigured services
* Incorrect file ownership

---

### 3. Persistence Mechanisms

Persistence ensures continued access even after system reboot.

**Techniques:**

* Creating cron jobs
* Adding malicious services
* Modifying startup scripts
* Adding backdoor users

---

### 4. Living-Off-the-Land (LotL)

Using built-in system tools to avoid detection.

**Examples:**

* PowerShell
* WMI (Windows Management Instrumentation)
* Bash scripting

---

## 🛠️ Tools Used

* LinPEAS
* LinEnum
* PowerSploit
* Metasploit

---

## 📚 Learning Resources

* HackTricks (Privilege Escalation Guide)
* Offensive Security PWK Notes
* TryHackMe Privilege Escalation Labs

---

## 🔐 Key Takeaways

* Misconfigurations are a major cause of privilege escalation
* SUID binaries can be dangerous if not secured
* Persistence techniques allow attackers to maintain access
* Enumeration is the most critical step

---

## ✅ Conclusion

Privilege escalation is a crucial phase in penetration testing. By identifying misconfigurations and exploiting vulnerabilities, attackers can gain full control of a system. Proper system hardening and monitoring are essential to prevent such attacks.
