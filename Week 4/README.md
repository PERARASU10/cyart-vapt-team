# Week 4 – Advanced Vulnerability Assessment & Penetration Testing (VAPT)

## Overview
This repository documents the **Week 4 activities of my Cyber Security / VAPT internship**, focusing on **advanced penetration testing techniques**, **exploit chaining**, **API security testing**, **network protocol attacks**, **mobile application security**, and a **capstone full VAPT cycle**.

All testing activities were performed in **authorized vulnerable lab and simulated environments** strictly for educational and ethical purposes.

---

## Internship Details
- **Intern Name:** Perarasu M  
- **Domain:** Cyber Security / VAPT  
- **Organization:** Cyart Tech  
- **Week:** 4 (Advanced VAPT)  
- **Assessment Date:** 22 January 2026  

---

## Objectives
- Learn advanced exploitation and exploit chaining techniques  
- Perform API security testing  
- Understand privilege escalation and persistence  
- Analyze network protocol attacks  
- Explore mobile application security testing  
- Execute a complete VAPT cycle using PTES  
- Improve professional security reporting skills  

---

## Scope of Testing
- **Vulnerable Machine:** VulnHub – Mr. Robot  
- **Web Application:** WordPress CMS  
- **API:** REST-based User Management API  
- **Network:** Internal lab network  
- **Mobile Application:** Test APK  
- **Authorization:** Approved vulnerable labs only  

---

## Methodology
The assessment followed the **Penetration Testing Execution Standard (PTES)**:
1. Planning & Scoping  
2. Reconnaissance  
3. Vulnerability Analysis  
4. Exploitation (Simulated)  
5. Post-Exploitation  
6. Reporting  

---

## Key Activities Performed

### Advanced Exploitation
- Studied exploit chaining techniques  
- Analyzed public Proof-of-Concept exploits  
- Understood defense bypass concepts such as ASLR and ROP (theoretical)

### API Security Testing
- Tested a RESTful API endpoint (`/users`)
- Identified **Broken Object Level Authorization (BOLA)**
- Demonstrated unauthorized data access by modifying object IDs

### Privilege Escalation & Persistence
- Studied SUID-based privilege escalation
- Simulated persistence using cron job techniques

### Network Protocol Attacks
- Simulated SMB relay attack
- Studied Man-in-the-Middle (MitM) attack concepts and risks

### Mobile Application Security
- Identified insecure data storage
- Studied dynamic testing using Frida
- Demonstrated runtime manipulation concepts

---

## Capstone Project – Full VAPT Cycle

### Vulnerability Identified
- **VSFTPD 2.3.4 – Remote Code Execution (RCE)**

### Target Details
- **IP Address:** 192.168.43.131  
- **Service:** FTP (Port 21)

### PTES Mapping
- Reconnaissance: FTP service discovery using Nmap  
- Vulnerability Analysis: Outdated VSFTPD version identified  
- Exploitation: RCE simulated  
- Post-Exploitation: Privilege escalation and persistence analysis  
- Reporting: Technical and non-technical documentation  

---

## Tools Used
- Nmap  
- Burp Suite  
- Postman  
- Metasploit (conceptual usage)  
- Frida  
- MobSF  
- Kali Linux  

---

## Reporting Deliverables
- Technical PTES Report  
- Non-Technical Management Summary  
- Vulnerability and attack logs  
- Remediation recommendations  

---

## Key Learnings
- Advanced exploitation techniques  
- API, network, and mobile security risks  
- Importance of structured penetration testing methodologies  
- Ethical hacking and professional reporting practices  

---

## Challenges Faced
- Tool limitations in lab environments  
- Complexity of advanced exploits  
- Time and simulation constraints  

---

## Conclusion
Week 4 provided hands-on exposure to **advanced VAPT concepts** and reinforced the importance of **methodology-driven penetration testing** and **clear security reporting**. The capstone project successfully demonstrated an end-to-end VAPT workflow.
