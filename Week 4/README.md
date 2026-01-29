🔐 Week 4 – Advanced Vulnerability Assessment & Penetration Testing (VAPT)
📌 Overview

This repository/documentation represents the Week 4 work of my Cyber Security / VAPT internship, focused on advanced penetration testing concepts, exploit chaining, API security, network protocol attacks, mobile application security, and a capstone full VAPT cycle.

All activities were performed ethically in authorized vulnerable lab and simulated environments for learning and educational purposes.

🏢 Internship Details

Intern Name: Perarasu M

Domain: Cyber Security / VAPT

Organization: Cyart Tech

Assessment Period: 22 January 2026

Week: 4 (Advanced Level)

🎯 Objectives of Week 4

Understand advanced exploitation techniques

Learn exploit chaining and defense bypass concepts

Perform API security testing

Study privilege escalation & persistence

Analyze network protocol attacks

Explore mobile application security testing

Execute and document a full VAPT cycle (Capstone Project)

Improve professional security reporting skills

🧪 Scope of Testing

Vulnerable Machine: VulnHub – Mr. Robot (Simulated)

Web Application: WordPress CMS

API: REST-based User Management API

Network Environment: Internal lab network

Mobile Application: Test APK

Authorization: Approved vulnerable labs and test environments only

🧭 Methodology Followed

The assessment followed the Penetration Testing Execution Standard (PTES):

Planning & Scoping

Reconnaissance

Vulnerability Analysis

Exploitation (Simulated)

Post-Exploitation

Reporting

This ensured a structured and industry-standard approach.

🧠 Key Concepts Covered
🔹 Advanced Exploitation

Exploit chaining (XSS → Session Hijacking → Admin → RCE)

Public PoC analysis and customization

Defense bypass concepts (ASLR, ROP – theoretical)

🔹 API Security Testing

Tested a RESTful User Management API

Identified Broken Object Level Authorization (BOLA)

Demonstrated unauthorized data access by object ID manipulation

Tools used: Burp Suite, Postman

🔹 Privilege Escalation & Persistence

Studied SUID-based privilege escalation

Simulated cron job–based persistence

Understood attacker behavior after initial access

🔹 Network Protocol Attacks

SMB Relay attack (NTLM hash interception – simulated)

Man-in-the-Middle (MitM) attack concepts

Emphasized risks of legacy protocols and misconfigurations

🔹 Mobile Application Security

Identified Insecure Data Storage

Studied dynamic testing using Frida

Demonstrated runtime manipulation and authentication bypass concepts

🧩 Capstone Project – Full VAPT Cycle
🔥 Vulnerability Identified

VSFTPD 2.3.4 – Remote Code Execution (RCE)

🖥️ Target

IP Address: 192.168.43.131

Service: FTP (Port 21)

📍 PTES Phase Mapping

Reconnaissance: FTP service discovery via Nmap

Vulnerability Analysis: Outdated VSFTPD version identified

Exploitation: RCE simulated

Post-Exploitation: Privilege escalation & persistence analysis

Reporting: Technical and non-technical documentation

✅ Outcome

This capstone demonstrated a complete penetration testing workflow, from discovery to remediation.

📄 Reporting Deliverables

Technical PTES Report (300 words)

Non-Technical Management Summary (150 words)

Vulnerability logs and attack summaries

Remediation recommendations

Key learnings and challenges

🛠 Tools & Technologies Used

Nmap

Burp Suite

Postman

Metasploit (conceptual usage)

Frida

MobSF

Linux (Kali)

🛡 Remediation Recommendations

Patch and remove vulnerable services

Enforce least privilege access

Implement proper API authorization

Disable insecure network protocols

Secure mobile app storage and logic

Conduct regular security testing

📚 Key Learnings

Advanced exploit chaining techniques

API and network attack vectors

Importance of structured methodologies

Ethical penetration testing practices

Professional security reporting

⚠️ Challenges Faced

Tool limitations in lab environment

Complexity of advanced exploits

Time management

Simulation constraints

✅ Conclusion

Week 4 strengthened my understanding of real-world penetration testing workflows, advanced attack techniques, and professional VAPT reporting. The capstone project helped consolidate all concepts into a single, end-to-end security assessment.
