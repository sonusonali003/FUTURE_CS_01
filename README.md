# FUTURE_CS_01 – Vulnerability Assessment Report

## Project Overview

This repository contains the deliverables for **Task 1 – Vulnerability Assessment Report**, completed as part of the **Future Interns Cyber Security Internship**. The objective of this project was to perform a safe and ethical vulnerability assessment of the intentionally vulnerable web application **Altoro Mutual (http://testfire.net)**. The assessment focused on identifying publicly visible security weaknesses through website reconnaissance, network scanning, and passive web application analysis without exploiting the target system.

---

## Objectives

- Perform manual website reconnaissance.
- Identify publicly accessible pages and application features.
- Conduct network reconnaissance using Nmap.
- Perform passive web application security assessment using OWASP ZAP.
- Analyze HTTP headers, cookies, and security configurations.
- Classify identified risks based on severity.
- Provide practical remediation recommendations following security best practices.

---

## Tools Used

- **Operating System:** Kali Linux
- **Web Browser:** Mozilla Firefox
- **Network Scanner:** Nmap
- **Web Application Security Scanner:** OWASP ZAP
- **Browser Developer Tools**
- **Canva** (Report Design)
- **GitHub** (Documentation & Version Control)

---

## Assessment Methodology

The vulnerability assessment was performed using the following workflow:

1. Project Setup
2. Target Website Selection
3. Manual Website Reconnaissance
4. Network Reconnaissance using Nmap
5. Passive Vulnerability Assessment using OWASP ZAP
6. Security Finding Analysis
7. Risk Classification
8. Business Impact Assessment
9. Remediation Recommendations
10. Final Report Preparation

---

## Repository Structure

```text
FUTURE_CS_01
│
├── README.md
├── Vulnerability Assessment Report.pdf
│
└── Evidence
    ├── Website_Reconnaissance
    ├── Nmap
    └── OWASP_ZAP
```

---

## Key Findings

The assessment identified several common web application security issues, including:

- Missing security headers
- Cookie security configuration issues
- Information disclosure through HTTP response headers
- Missing Content Security Policy (CSP)
- Missing Anti-Clickjacking protection
- Potential SQL Injection indicators
- Potential Cross-Site Scripting (XSS) indicators

---

## Disclaimer

This assessment was conducted **strictly for educational and learning purposes** as part of the **Future Interns Cyber Security Internship**. The target website (**Altoro Mutual – testfire.net**) is an intentionally vulnerable application designed for security testing and training. No unauthorized access, exploitation, or malicious activity was performed during this assessment. All findings and recommendations are intended solely to demonstrate ethical security assessment methodologies and cybersecurity best practices.
