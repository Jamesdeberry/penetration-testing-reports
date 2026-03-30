🛡️ penetration-testing-reports

A collection of penetration testing reports demonstrating exploitation of Linux, web, and Windows environments.

🔥 Penetration Testing Portfolio – James DeBerry
Overview

This repository contains penetration testing reports demonstrating real-world attack paths across multiple environments, including Linux systems, web applications, and Windows infrastructure.

Each assessment follows a structured penetration testing methodology:

Enumeration
Vulnerability Identification
Exploitation
Privilege Escalation
Post-Exploitation
Remediation

These reports showcase the ability to identify vulnerabilities, chain exploits, and achieve full system compromise.

📂 Reports
🔵 Blue (Windows Exploitation)
Exploited MS17-010 (EternalBlue)
Achieved SYSTEM-level access
Demonstrated unauthenticated remote code execution
Retrieved all system flags


🟣 Relevant (Windows Exploitation)
Enumerated SMB services and discovered valid credentials
Identified writable SMB share exposed via web server
Uploaded malicious ASPX payload for remote code execution
Escalated privileges using SeImpersonatePrivilege (PrintSpoofer)
Achieved SYSTEM-level access


🔴 Steel Mountain (Windows Exploitation)
Identified vulnerable web service (Rejetto HFS)
Exploited remote command execution vulnerability
Gained initial shell access
Escalated privileges via service misconfiguration
Achieved full system compromise


🟦 Kenobi (Linux Exploitation)
Enumerated SMB and NFS services
Exploited misconfigured file shares
Leveraged SSH key exposure for access
Escalated privileges to root


🟩 Simple CTF (Web Exploitation)
Identified SQL Injection vulnerability
Bypassed authentication mechanisms
Gained administrative access
Achieved system-level compromise


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
