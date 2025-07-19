# Web Application Penetration Testing Report

This project presents a professional web application penetration testing assessment performed in a controlled environment. The report follows industry best practices and aligns with the OWASP Top 10 vulnerabilities framework.

The objective was to identify, exploit, and document common web application security flaws such as Broken Access Control, Injection, Security Misconfiguration, and Server-Side Request Forgery (SSRF), among others.

## 📂 Contents

- 📝 **Report:** Detailed penetration testing report in PDF format
- 📸 **Screenshots:** Visual evidence of exploits and observations
- 🧠 **Findings:** Technical writeups for each OWASP category

## 🔍 Summary of Findings

| OWASP Category | Title | Risk | CVE Reference |
|----------------|-------|------|----------------|
| A01 | Broken Access Control | High | CVE-2018-14773 |
| A02 | Cryptographic Failures | Medium | CVE-2014-3566 |
| A03 | SQL Injection | Critical | CVE-2017-8917 |
| A04 | Insecure Logging | Medium | N/A |
| A05 | Security Misconfiguration | High | CVE-2015-2080 |
| A06 | Outdated OpenSSL (Heartbleed) | Critical | CVE-2014-0160 |
| A07 | Authentication Bypass | High | CVE-2019-11510 |
| A08 | Insecure Deserialization | Critical | CVE-2019-18935 |
| A09 | Logging & Monitoring Failures | Medium | N/A |
| A10 | SSRF + LFI | High | CVE-2021-21985 |

## 🛠 Tools Used

- Burp Suite
- Nmap
- SQLMap
- Nikto
- OWASP ZAP
- Kali Linux

## ⚠️ Disclaimer

This project was conducted in a **simulated and isolated lab environment** using intentionally vulnerable applications. No real-world systems were harmed or tested.

## 📄 Report Preview

The full report is available here:  
📎 [`ITP-425-Web-App-PenTest-Report-PrashantGupta.pdf`](./ITP-425%20Web%20Application%20Penetration%20Testing%20Report%20-%20Prashant%20Gupta.pdf)
