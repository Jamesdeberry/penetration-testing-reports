🛡️ Penetration-testing-reports

A collection of penetration testing reports demonstrating real-world attack paths from initial access to full system compromise across multiple environments.

🔥 Penetration Testing Portfolio – James DeBerry
Overview

This repository contains penetration testing reports demonstrating real-world attack paths across multiple environments, including Linux systems, web applications, and Windows infrastructure.

Each assessment follows a structured penetration testing methodology:

- Enumeration  
- Vulnerability Identification  
- Exploitation  
- Privilege Escalation  
- Post-Exploitation  
- Remediation  

These reports showcase the ability to identify vulnerabilities, chain exploits, and achieve full system compromise.

📂 Reports

🔵 [Blue (Windows Exploitation)](./Blue-Pentest-Report.pdf)
- Exploited MS17-010 (EternalBlue)
- Achieved SYSTEM-level access

🟣 [Relevant (Windows Exploitation)](./Relevant-Pentest-Report.pdf)
- SMB credential discovery → writable share → RCE
- Privilege escalation via PrintSpoofer
- SYSTEM-level compromise

🔴 [Steel Mountain (Windows Exploitation)](./Steel-Mountain-Pentest-Report.pdf)
- Exploited Rejetto HFS
- Gained initial access → privesc → full compromise

🟦 [Kenobi (Linux Exploitation)](./Kenobi-Pentest-Report.pdf)
- SMB/NFS enumeration → SSH key abuse → root

🟩 [Simple CTF (Web Exploitation)](./Ctf-Pentest-Report.pdf)
- SQL injection → auth bypass → system access

🧠 Skills Demonstrated
Network Enumeration (Nmap, SMB, RPC, NFS)
Web Application Testing (SQL Injection, File Upload Exploitation)
Exploitation Techniques (Metasploit, Manual Exploitation)
Windows Privilege Escalation (PrintSpoofer, Service Exploits)
Linux Privilege Escalation
Credential Discovery & Abuse
Post-Exploitation Techniques
Technical Documentation & Reporting

👨‍💻 About Me

Aspiring Cybersecurity Engineer with hands-on experience in penetration testing, vulnerability assessment, and system exploitation.

Focused on:

Real-world attack simulation
Offensive security techniques
Continuous skill development through labs and hands-on practice
