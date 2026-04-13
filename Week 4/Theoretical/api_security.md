# API Security Testing

## 🎯 Objective

To understand and identify vulnerabilities in APIs by testing authentication, authorization, input validation, and rate limiting mechanisms.

---

## 🔍 Core Concepts

### 1. API Vulnerabilities

APIs are widely used in modern applications and are often targeted by attackers.

**Common Vulnerabilities (OWASP API Top 10):**

* **Broken Object Level Authorization (BOLA):**
  Accessing unauthorized data by modifying object IDs.

* **Broken Authentication:**
  Weak token handling or improper session management.

* **Excessive Data Exposure:**
  APIs returning more data than necessary.

* **Lack of Rate Limiting:**
  Allows brute force or DoS attacks.

---

### 2. Testing Techniques

#### 🔹 Manual Testing

* Intercept requests using Burp Suite
* Modify parameters (IDs, tokens)
* Replay and analyze responses

#### 🔹 Automated Testing

* Use Postman for API testing
* Use tools like sqlmap for injection testing
* Perform fuzzing on API endpoints

---

### 3. Injection Attacks

* **SQL Injection:**
  Inject malicious SQL queries into API parameters

* **GraphQL Injection:**
  Manipulate GraphQL queries to extract sensitive data

---

### 4. Rate Limiting & Authentication Bypass

* Test APIs for lack of request limits
* Attempt brute force attacks
* Bypass authentication using manipulated tokens

---

## 🛠️ Tools Used

* Burp Suite
* Postman
* sqlmap
* OWASP ZAP

---

## 📚 Learning Resources

* OWASP API Security Top 10
* PortSwigger API Testing Labs
* SANS API Security Case Studies

---

## 🔐 Key Takeaways

* APIs are a critical attack surface
* Proper authentication and authorization are essential
* Input validation must be enforced
* Rate limiting helps prevent abuse

---

## ✅ Conclusion

API security testing is crucial for modern applications. Identifying vulnerabilities such as BOLA, injection attacks, and weak authentication mechanisms helps prevent unauthorized access and data breaches.
