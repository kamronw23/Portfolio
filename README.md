<h1 align="center">Kam'ron Washington</h1>
<h3 align="center">Aspiring SOC Analyst · Blue Team · Network & Linux Security</h3>

<p align="center">
  <img alt="CompTIA Security+" src="https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge" />
  <img alt="CompTIA Network+" src="https://img.shields.io/badge/CompTIA-Network%2B-C8202F?style=for-the-badge" />
  <img alt="CompTIA Linux+" src="https://img.shields.io/badge/CompTIA-Linux%2B-C8202F?style=for-the-badge" />
  <img alt="Grand Rapids, MI" src="https://img.shields.io/badge/Location-Grand%20Rapids%2C%20MI-1f6feb?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kam%E2%80%99ron-washington-2003a93a0/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/kamronw23/security-scripts"><img alt="GitHub: Security Scripts" src="https://img.shields.io/badge/GitHub-Security%20Scripts-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

## 🛡️ About Me

I'm a recent graduate looking to start my career as a **SOC Analyst**. I hold CompTIA **Security+**, **Network+**, and **Linux+**, and I learn best hands-on: I build virtual labs, break things on purpose, and write scripts that automate the tasks a Tier 1 analyst does every day, like triaging logs, checking file integrity, and spotting brute-force attempts.

**Currently focused on:** log analysis and alert triage · SIEM fundamentals · Linux and Windows hardening · Python and PowerShell for security automation

---

## 🧰 Skills

| Area | Tools & Concepts |
|---|---|
| **Security Operations** | Log analysis, alert triage, incident response basics, IOC investigation, MITRE ATT&CK |
| **Networking** | TCP/IP, subnetting, VLANs, firewalls, DNS/DHCP, packet analysis (Wireshark), Nmap |
| **Systems** | Linux (CLI, permissions, services, auth logs), Windows (Event Viewer, PowerShell, WSL/Bash) |
| **Virtualization / Labs** | VirtualBox / VMware, Kali Linux, isolated virtual networks |
| **Scripting** | Python, Bash, PowerShell |
| **Data** | SQL, database design and backup/recovery, Tableau |

---

## 🔐 Cybersecurity & Networking Projects

| Project | What I did | Security relevance |
|---|---|---|
| [**Personal Virtual Hacklab**](https://drive.google.com/file/d/1t9wqnAAK8_sGBh1gKonmNQfGmrKsQgfX/view?usp=share_link) | Built an isolated lab of virtual machines to practice attacks and defenses safely | A sandbox for testing exploits, detections, and hardening without touching production |
| [**Configuring a Virtual Network**](https://drive.google.com/file/d/1d69dLMCSbIqIiaOmHCsFnIQIIQ1tTwG5/view?usp=share_link) | Designed and configured a virtual network: addressing, connectivity, and segmentation | Network segmentation is a core control for limiting lateral movement |
| [**Windows BASH Shell**](https://drive.google.com/file/d/1lbeNrROTt86JBd6-acOb3TKM25IaNs20/view?usp=share_link) | Set up and used a Bash environment on Windows | Lets one analyst workstation run Linux security tooling and parse logs |
| [**Binary Date & Time Conversion**](https://drive.google.com/file/d/1EvYfgT1iWJ2s6PHZoeXV4lxcytzh6Nc1/view?usp=share_link) | Converted raw binary and hex timestamps into readable date/time values | Decoding timestamps is a basic forensics and log-timeline skill |

---

## ⚙️ Security Scripts → [`security-scripts`](https://github.com/kamronw23/security-scripts)

Small, well-documented defensive tools I wrote to automate SOC tasks. Each one comes with sample data so you can run it in seconds.

| Script | Purpose |
|---|---|
| `ssh_bruteforce_detector.py` | Parses Linux `auth.log` and flags IPs with repeated failed SSH logins |
| `Get-FailedLogons.ps1` | Pulls Windows Event ID 4625 (failed logon) and summarizes by account and source IP |
| `file_integrity_monitor.py` | Builds a SHA-256 baseline of a folder and reports added, removed, or modified files |
| `ioc_extractor.py` | Extracts IPs, domains, URLs, emails, and hashes from text, logs, or phishing emails |
| `email_header_analyzer.py` | Reviews email headers for SPF/DKIM/DMARC results and spoofing red flags |
| `password_audit.py` | Scores password strength and checks Have I Been Pwned via k-anonymity (never sends the password) |
| `port_scanner.py` | Lightweight TCP connect scanner for auditing **my own** lab hosts |

---

## 🎖️ Certifications & Education

| Credential | Issuer |
|---|---|
| [CompTIA Security+](https://www.comptia.org/en-us/certifications/security/) | CompTIA |
| [CompTIA Network+](https://www.comptia.org/en-us/certifications/network/) | CompTIA |
| [CompTIA Linux+](https://www.comptia.org/en-us/certifications/linux/) | CompTIA |
| Associate's Degree, *<!-- TODO: field of study -->* | *<!-- TODO: school name -->* |

---

## 🗄️ Data & Database Work

Data integrity and availability are two thirds of the CIA triad, so these projects connect to security too.

- [**Database Backup & Recovery: Step-by-Step**](https://drive.google.com/file/d/1GpPLHatlSpdE6lbwUgKtZAP3DDpA-C_P/view?usp=share_link): backup strategy and restore procedures (availability and disaster recovery)
- [**Database Standards & Procedures**](https://drive.google.com/file/d/1PqE_ID2_bTQ0JTCrIBuU0gYO5ljRVs8C/view?usp=share_link): documented standards, access, and change procedures
- [**Database Design**](https://drive.google.com/file/d/1FEEAS7UCGMAX8GYtg-inRmbrBrtyob6z/view?usp=share_link): normalized schema design
- [**Tableau Data Analysis Project**](https://www.youtube.com/watch?v=ZrGaCQyevcw): video walkthrough of a data analysis dashboard

---

## 🎯 What I'm Working Toward

- [ ] Build a home SIEM lab (Splunk Free / Elastic / Microsoft Sentinel) and write detection rules
- [ ] Complete SOC-focused hands-on platforms (TryHackMe SOC Level 1, Blue Team Labs Online, LetsDefend)
- [ ] Map each script in `security-scripts` to MITRE ATT&CK techniques
- [ ] Next certification: CompTIA CySA+

---

<p align="center"><i>Open to SOC Analyst, Security Analyst, and IT/Network roles. Let's connect on <a href="https://www.linkedin.com/in/kam%E2%80%99ron-washington-2003a93a0/">LinkedIn</a>.</i></p>
