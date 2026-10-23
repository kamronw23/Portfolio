Kam'ron Washington
Aspiring SOC Analyst · Blue Team · Network & Linux Security
CompTIA Security+ CompTIA Network+ CompTIA Linux+ Grand Rapids, MI

LinkedIn GitHub: Security Scripts

🛡️ About Me
I'm a recent graduate looking to start my career as a SOC Analyst. I hold CompTIA Security+, Network+, and Linux+, and I learn best hands-on: I build virtual labs, break things on purpose, and write scripts that automate the tasks a Tier 1 analyst does every day, like triaging logs, checking file integrity, and spotting brute-force attempts.

Currently focused on: log analysis and alert triage · SIEM fundamentals · Linux and Windows hardening · Python and PowerShell for security automation

🧰 Skills
Area	Tools & Concepts
Security Operations	Log analysis, alert triage, incident response basics, IOC investigation, MITRE ATT&CK
Networking	TCP/IP, subnetting, VLANs, firewalls, DNS/DHCP, packet analysis (Wireshark), Nmap
Systems	Linux (CLI, permissions, services, auth logs), Windows (Event Viewer, PowerShell, WSL/Bash)
Virtualization / Labs	VirtualBox / VMware, Kali Linux, isolated virtual networks
Scripting	Python, Bash, PowerShell
Data	SQL, database design and backup/recovery, Tableau
🔐 Cybersecurity & Networking Projects
Project	What I did	Security relevance
Personal Virtual Hacklab	Built an isolated lab of virtual machines to practice attacks and defenses safely	A sandbox for testing exploits, detections, and hardening without touching production
Configuring a Virtual Network	Designed and configured a virtual network: addressing, connectivity, and segmentation	Network segmentation is a core control for limiting lateral movement
Windows BASH Shell	Set up and used a Bash environment on Windows	Lets one analyst workstation run Linux security tooling and parse logs
Binary Date & Time Conversion	Converted raw binary and hex timestamps into readable date/time values	Decoding timestamps is a basic forensics and log-timeline skill
⚙️ Security Scripts → security-scripts
Small, well-documented defensive tools I wrote to automate SOC tasks. Each one comes with sample data so you can run it in seconds.

Script	Purpose
ssh_bruteforce_detector.py	Parses Linux auth.log and flags IPs with repeated failed SSH logins
Get-FailedLogons.ps1	Pulls Windows Event ID 4625 (failed logon) and summarizes by account and source IP
file_integrity_monitor.py	Builds a SHA-256 baseline of a folder and reports added, removed, or modified files
ioc_extractor.py	Extracts IPs, domains, URLs, emails, and hashes from text, logs, or phishing emails
email_header_analyzer.py	Reviews email headers for SPF/DKIM/DMARC results and spoofing red flags
password_audit.py	Scores password strength and checks Have I Been Pwned via k-anonymity (never sends the password)
port_scanner.py	Lightweight TCP connect scanner for auditing my own lab hosts
🎖️ Certifications & Education
Credential	Issuer
CompTIA Security+	CompTIA
CompTIA Network+	CompTIA
CompTIA Linux+	CompTIA
Associate's Degree,	
🗄️ Data & Database Work
Data integrity and availability are two thirds of the CIA triad, so these projects connect to security too.

Database Backup & Recovery: Step-by-Step: backup strategy and restore procedures (availability and disaster recovery)
Database Standards & Procedures: documented standards, access, and change procedures
Database Design: normalized schema design
Tableau Data Analysis Project: video walkthrough of a data analysis dashboard
🎯 What I'm Working Toward
 Build a home SIEM lab (Splunk Free / Elastic / Microsoft Sentinel) and write detection rules
 Complete SOC-focused hands-on platforms (TryHackMe SOC Level 1, Blue Team Labs Online, LetsDefend)
 Map each script in security-scripts to MITRE ATT&CK techniques
 Next certification: CompTIA CySA+
Open to SOC Analyst, Security Analyst, and IT/Network roles. Let's connect on LinkedIn.
