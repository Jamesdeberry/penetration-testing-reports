🛡️ Penetration Testing Reports

A collection of penetration testing reports demonstrating real-world attack paths from initial access to full system compromise across multiple environments.

🔥 Penetration Testing Portfolio – James DeBerry

This repository showcases hands-on penetration testing assessments across Linux systems, web applications, Windows environments, and Active Directory infrastructure.

Each engagement follows a structured methodology:

-Enumeration
-Vulnerability Identification
-Exploitation
-Privilege Escalation
-Post-Exploitation
-Remediation

These reports demonstrate the ability to identify vulnerabilities, chain exploits, and achieve full system compromise in realistic scenarios.

📂 Reports

🔵 Blue (Windows Exploitation)
-Exploited MS17-010 (EternalBlue)
-Achieved SYSTEM-level access

🟣 Relevant (Windows Exploitation)
-SMB credential discovery → writable share → remote code execution
-Privilege escalation via PrintSpoofer
-SYSTEM-level compromise

🔴 Steel Mountain (Windows Exploitation)
-Exploited Rejetto HFS web server
-Initial access → privilege escalation → full system compromise

🟦 Kenobi (Linux Exploitation)
-SMB & NFS enumeration
-SSH key extraction and abuse
-Root-level compromise

🟩 Simple CTF (Web Exploitation)
-SQL Injection (CVE-2019-9053)
-Authentication bypass → credential extraction
-Privilege escalation to root

🧠 Active Directory (Domain Exploitation) 🔥
-AS-REP Roasting → extracted Kerberos hash
-Cracked credentials → initial domain access (svc-admin)
-SMB enumeration → discovered backup share
-Retrieved and decoded credentials → lateral movement via RDP
-Performed DCSync attack (DRSUAPI) → dumped NTDS.DIT
-Pass-the-Hash → authenticated as Domain Administrator
-Achieved full domain compromise

🧠 Skills Demonstrated
-Network Enumeration (Nmap, SMB, RPC, LDAP, Kerberos)
-Active Directory Attacks (AS-REP Roasting, DCSync, Pass-the-Hash)
-Web Application Testing (SQL Injection, File Upload Exploitation)
-Exploitation Techniques (Metasploit, Manual Exploitation)
-Windows Privilege Escalation (PrintSpoofer, Service Explits)
-Linux Privilege Escalation
-Credential Discovery & Abuse
-Lateral Movement Techniques
-Post-Exploitation & Persistence Concepts
-Technical Documentation & Reporting

👨‍💻 About Me

Aspiring Cybersecurity Engineer with hands-on experience in penetration testing, vulnerability assessment, and system exploitation.

Focused on:

-Real-world attack simulation
-Offensive security techniques
-Continuous skill development through hands-on labs and practice
