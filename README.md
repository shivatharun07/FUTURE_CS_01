# 🚨 Task 1 - Web Application Security Testing

This repository contains my submission for **Task 1** of the FutureInterns Cybersecurity Internship program.

## 🔍 Task Overview

- **Objective**: Conduct security testing on a sample web application to identify vulnerabilities such as SQL Injection, XSS, and broken authentication.
- **Target**: [Altoro Mutual Demo Banking Website](http://testfire.net)
- **Tool Used**: [Burp Suite Community Edition](https://portswigger.net/burp)

## 🧪 Key Activities

- Intercepted and analyzed HTTP requests and responses using Burp Suite.
- Performed manual testing to detect:
  - Insecure Direct Object Reference (IDOR)
  - Lack of access control on account numbers
  - Information disclosure via unprotected responses

## ⚠️ Vulnerabilities Identified

- Sensitive data exposure
- Authorization bypass (IDOR)
- Missing security headers (CSP, X-Frame-Options)
- Unrestricted access to financial records

## ✅ Deliverable

A PDF report detailing the vulnerabilities discovered and recommendations for mitigation.
