# Network Protocol Attacks

## 🎯 Objective

To understand and exploit vulnerabilities in network protocols to intercept, manipulate, or gain unauthorized access to data.

---

## 🔍 Core Concepts

### 1. Protocol Exploitation

Network protocols such as SMB, DNS, and SNMP can be exploited if improperly configured.

**Examples:**

* **SMB Relay Attack:**
  Capturing and relaying authentication requests to gain access

* **DNS Exploitation:**
  Manipulating DNS responses to redirect users

---

### 2. Man-in-the-Middle (MitM) Attacks

MitM attacks allow attackers to intercept communication between two systems.

**Techniques:**

* **ARP Spoofing:**
  Redirecting traffic by poisoning ARP tables

* **DNS Spoofing:**
  Redirecting users to malicious websites

* **SSL Stripping:**
  Downgrading HTTPS to HTTP

---

### 3. Protocol Misconfigurations

Improper configurations can expose sensitive data.

**Examples:**

* Use of unencrypted protocols like Telnet
* Outdated protocols such as SMBv1
* Weak SNMP community strings

---

### 4. Credential Harvesting

Attackers can capture authentication data using network attacks.

**Examples:**

* Capturing NTLM hashes
* Sniffing plaintext credentials

---

## 🛠️ Tools Used

* Responder
* Ettercap
* Wireshark
* tcpdump

---

## 📚 Learning Resources

* PacketLife Networking Guides
* TCM Security Network Pentesting Course
* HackTheBox Network Labs

---

## 🔐 Key Takeaways

* Network protocols are a common attack vector
* Misconfigurations can lead to serious vulnerabilities
* MitM attacks allow interception of sensitive data
* Encryption and secure protocols are essential

---

## ✅ Conclusion

Network protocol attacks demonstrate how attackers can exploit communication channels to intercept data and gain unauthorized access. Securing protocols and using encryption are critical to protecting network infrastructure.
