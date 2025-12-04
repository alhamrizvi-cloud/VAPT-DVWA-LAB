# 🔐 DVWA Vulnerability Assessment & Penetration Testing Lab

This repository contains my hands-on **Vulnerability Assessment & Penetration Testing (VAPT)** project performed on **Damn Vulnerable Web Application (DVWA)** deployed in a secure Podman-based lab environment.  
The goal of this lab is to practice real-world web application testing techniques, identify common vulnerabilities, and demonstrate exploitation with proper documentation.

---

## 📌 Overview

- **Application:** DVWA (Damn Vulnerable Web Application)  
- **Environment:** Podman container lab  
- **Focus Areas:** SQL Injection, XSS, Command Injection, File Upload  
- **Tools Used:** Burp Suite, Python scripts, browser dev tools  
- **Purpose:** Build practical offensive security skills following OWASP & PTES methodology

---

## ⚙️ Lab Setup

DVWA was deployed using Podman in an isolated testing environment.

```bash
podman pull vulnerables/web-dvwa
podman run -d -p 8080:80 vulnerables/web-dvwa
