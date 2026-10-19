# 🛡️ OWASP ASVS Enterprise Security Scanner (v2.0)

A modular Python-based security scanner designed to audit web applications against **OWASP ASVS** standards (V3: Cookies and V14: Security Headers), featuring multi-format reporting and SOC integration capabilities.

---

## 🚀 Key Features

* **Modular Architecture:** Easily extensible structure allowing new security check modules to be added independently without modifying core logic.
* **Security Headers Analysis (V14):** Inspects essential web security headers (such as `HSTS`, `CSP`, and `X-Frame-Options`) to protect against common web vectors like XSS and Clickjacking.
* **Cookie Security Controls (V3):** Analyzes session cookies for security attributes (`Secure`, `HttpOnly`, `SameSite`) to prevent Session Hijacking and CSRF.
* **Multi-Format Reporting:** Automatically generates scan results in three distinct formats:
  * **HTML:** Interactive, human-readable visual dashboard for security engineers and stakeholders.
  * **JSON:** Machine-readable format optimized for SIEM and SOC automation.
  * **TXT:** Lightweight text logs for rapid penetration testing analysis.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Standards:** OWASP Application Security Verification Standard (ASVS)

---

## 📊Sample Report Preview
The scanner generates clean and actionable security reports:
