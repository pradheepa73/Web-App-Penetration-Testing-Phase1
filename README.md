
# Web Application Penetration Testing - Phase 1

![Organization](https://img.shields.io/badge/Organization-IqraSec%20Academy-blue)
![Domain](https://img.shields.io/badge/Domain-Web%20App%20Security-red)
![OS](https://img.shields.io/badge/OS-Kali%20Linux-557C94?logo=kalilinux)
![Tools](https://img.shields.io/badge/Tools-Burp%20Suite%20%7C%20Nmap-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)

> A comprehensive practical assessment documenting the foundational phase of a Web Application Penetration Testing (WAPT) internship.

---

## Overview

This repository contains my practical work, screenshots, and final reports for **Phase 1** of my Web Application Penetration Testing internship at **IqraSec Academy**. 

The focus of this phase was building a strong foundation in web security, mastering industry-standard tools, and safely exploiting common web vulnerabilities in an isolated environment. Testing was conducted against intentionally vulnerable targets to simulate real-world attack scenarios.

---

## Environment and Tools

| Component | Details |
|:---|:---|
| **Operating System** | Kali Linux |
| **Target Environments** | Metasploitable 2, PortSwigger Web Security Academy, DVWA |
| **Core Tools** | Burp Suite (Community Edition), Nmap, Firefox (with FoxyProxy) |
| **Documentation** | Markdown, Screenshots, PDF Reporting |

---

## Tasks Completed

### Task 1: Web Fundamentals & Interception
- Analyzed HTTP/HTTPS requests and response structures.
- Intercepted and manipulated headers (User-Agent, Cookie, Host) using Burp Suite.
- Studied session management mechanisms and authentication flows.
- Completed theoretical modules on TryHackMe regarding web fundamentals.

### Task 2: Network & Service Reconnaissance
- Performed aggressive network scans on Metasploitable 2 using `nmap -sV -sC -p-`.
- Mapped the attack surface by identifying critical open ports (FTP, SSH, HTTP, MySQL).
- Conducted manual and automated content discovery to find hidden directories.

### Task 3: Authentication & Access Control
- Studied and tested for Insecure Direct Object References (IDOR).
- Practiced manipulating object parameters to test for horizontal and vertical privilege escalations.
- Analyzed broken access control mechanisms.

### Task 4: Vulnerability Exploitation (XSS & SQLi)
- **Cross-Site Scripting (XSS):** Solved 4 Apprentice to Practitioner level labs on PortSwigger Web Security Academy (covering Reflected, Stored, and DOM-based XSS).
- **SQL Injection:** Successfully bypassed authentication and dumped database records on DVWA using the payload: `' OR 1=1--`.

---

## Repository Structure

```text
IqraSec-WAPT-Phase-1/
|-- README.md
|-- Reports/
|   \-- Phase1_Penetration_Test_Report.pdf
|-- Screenshots/
       |-- Task1_Web_Basics/
       |-- Task2_Recon/
       |-- Task3_IDOR/
       \-- Task4_XSS_SQLi/
 ```

---

## Disclaimer

> **IMPORTANT:** All testing was conducted strictly within authorized, legal, and isolated lab environments (Metasploitable 2, PortSwigger Academy, and DVWA). No live, production, or unauthorized systems were targeted. The techniques demonstrated in this repository are for educational purposes only.

---

## Author

**Pradheepa M**  
B.Sc. Computer Science with Cybersecurity  
WAPT/VAPT Intern - IqraSec Academy  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pradheepa-m-051728372)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pradheepa73)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:pradheepa378@gmail.com)

---

<div align="center">

**"Empowering The Digital Defenders"**

*IqraSec Academy - WAPT Internship*

</div>
```

---
