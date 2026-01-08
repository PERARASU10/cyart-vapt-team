# 🛡️ Week 2 – Vulnerability Assessment & Penetration Testing (VAPT)

## 📖 Overview

This repository contains the Week 2 Vulnerability Assessment and Penetration Testing (VAPT) work carried out as part of a cybersecurity internship. The objective of this week was to understand and perform a complete VAPT lifecycle, including vulnerability scanning, reconnaissance, exploitation attempts, post-exploitation analysis, and professional reporting using open-source tools in a controlled lab environment.

All testing activities were performed on authorized vulnerable lab machines strictly for educational purposes.

---

## 🎯 Objectives

- Understand vulnerability scanning techniques and CVSS-based risk prioritization  
- Perform reconnaissance and asset enumeration  
- Simulate exploitation using industry-standard tools  
- Analyze post-exploitation feasibility  
- Document findings following PTES methodology  
- Produce a consolidated technical and non-technical report  

---

## 🧪 Lab Environment

| Component | Description |
|----------|-------------|
| Attacker Machine | Kali Linux |
| Target Machine | Metasploitable 2 |
| Network Type | VMware NAT Network |
| Methodology | PTES (Penetration Testing Execution Standard) |

---

## 🛠️ Tools Used

- Nmap – Network and service scanning  
- OpenVAS (GVM) – Automated vulnerability assessment  
- Nikto – Web server vulnerability scanning  
- Metasploit Framework – Exploitation and validation  
- sqlmap – SQL Injection testing (simulation / lab-based)  
- Maltego / OSINT – Reconnaissance (conceptual & lab-based)  
- Google Docs / MS Word – Documentation and reporting  

---

## 🔁 VAPT Workflow (Step-by-Step)

### 🔹 Step 1: Planning & Scope Definition
- Defined scope limited to Metasploitable lab VM  
- Confirmed authorization and avoided real-world targets  
- Selected tools based on assessment phases  

---

### 🔹 Step 2: Reconnaissance (PTES – Recon Phase)
- Identified exposed services and attack surface  
- Performed service enumeration in a lab environment  
- Documented reconnaissance findings  

**Outcome:**  
Initial understanding of exposed services and potential entry points.

---

### 🔹 Step 3: Vulnerability Scanning
- Performed network scanning using Nmap (`-sV`)  
- Conducted automated vulnerability scanning using OpenVAS  
- Identified informational, medium, high, and critical findings  
- Manually validated false positives where applicable  

---

### 🔹 Step 4: Web Vulnerability Assessment
- Used Nikto to identify outdated web components  
- Identified Apache-related vulnerabilities (CVE-based)  
- Mapped findings to OWASP Top 10 categories  

---

### 🔹 Step 5: Exploitation Attempt
- Performed exploitation attempts using Metasploit  
- Tested Tomcat Manager authentication misconfiguration  
- Observed missing access control enforcement  
- Validated exploit relevance using Exploit-DB references  

**Note:**  
Successful shell access was not mandatory; attempts and observations were documented professionally.

---

### 🔹 Step 6: Post-Exploitation Analysis
- Reviewed post-exploitation techniques  
- Identified limitations due to lack of active session and Linux target  
- Documented why privilege escalation was not applicable  
- Highlighted dependency on successful exploitation  

---

### 🔹 Step 7: Capstone – Full VAPT Cycle
- Simulated SQL Injection using sqlmap in a lab environment  
- Logged vulnerability detection aligned with PTES phases  
- Suggested remediation and re-scan strategy  
- Prepared technical and non-technical summaries  

---

### 🔹 Step 8: Reporting
- Created a single consolidated PDF report containing:
  - Theoretical background  
  - Practical findings  
  - Tables and logs  
  - Screenshots  
  - Remediation recommendations  
- Followed professional VAPT reporting standards  

---


---

## ⚠️ Ethical Disclaimer

All activities documented in this repository were performed on intentionally vulnerable lab environments with proper authorization. No real-world systems, networks, or applications were targeted. This work is strictly for educational and training purposes.

---

## ✅ Key Learnings

- Practical understanding of the VAPT lifecycle  
- Importance of structured methodology (PTES)  
- Realistic handling of failed or partial exploitation attempts  
- CVSS-based vulnerability prioritization  
- Professional security reporting and communication  

---

## 📌 Conclusion

This Week 2 VAPT exercise successfully demonstrated a full vulnerability assessment and penetration testing workflow. The project reinforced ethical hacking principles, hands-on tool usage, and professional documentation skills essential for real-world cybersecurity roles.

---
