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


<img width="1922" height="1047" alt="1 mr robot" src="https://github.com/user-attachments/assets/ae17a958-61c0-4b25-8b52-c23a0ecce13c" />
<img width="1718" height="903" alt="2 Metasplot wordpress" src="https://github.com/user-attachments/assets/02b54bb4-1e2b-45a4-a691-e2716040f4b9" />
<img width="1720" height="905" alt="3 API " src="https://github.com/user-attachments/assets/7c0dc85d-b425-433c-86ec-8830e012603a" />
<img width="1600" height="900" alt="4 Burpsuite" src="https://github.com/user-attachments/assets/db940013-a627-49df-be39-c217c3ad04b8" />
<img width="875" height="734" alt="5 burp modified request" src="https://github.com/user-attachments/assets/f686f5eb-026a-45f0-b21a-f992c20fbd46" />
<img width="1922" height="1047" alt="6 burp modified response" src="https://github.com/user-attachments/assets/a42fae74-7e20-4c01-8f22-790daa4a0cc4" />
<img width="1920" height="1045" alt="7 privilage esclation 1" src="https://github.com/user-attachments/assets/f211e14e-5285-4e38-9cd8-de1b5decfb23" />
<img width="650" height="516" alt="10 responder" src="https://github.com/user-attachments/assets/2ee75565-8294-4ad4-a029-67129b3cfec5" />
<img width="1922" height="1047" alt="11 mobile app" src="https://github.com/user-attachments/assets/f51d13bb-c0ec-40a9-951d-7daa8b2b8e15" />


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
