<h1 align="center">Kam'ron Washington</h1>
<h3 align="center">Aspiring SOC Analyst · Digital Forensics · Blue Team</h3>

<p align="center">
  <img alt="CompTIA Security+" src="https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge" />
  <img alt="CompTIA Network+" src="https://img.shields.io/badge/CompTIA-Network%2B-C8202F?style=for-the-badge" />
  <img alt="Python Essentials" src="https://img.shields.io/badge/Python-Essentials-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="Grand Rapids, MI" src="https://img.shields.io/badge/Location-Grand%20Rapids%2C%20MI-1f6feb?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kam-ron-washington-2003a93a0/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/kamronw23?tab=repositories"><img alt="GitHub: All Repos" src="https://img.shields.io/badge/GitHub-All%20Repos-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

## 🛡️ About Me

I'm an **Information Security & Intelligence** student at **Ferris State University** with **two years of hands-on IT experience** in enterprise healthcare and education, and I'm working toward a career as a **SOC Analyst**. I hold CompTIA **Security+** and **Network+**, and I build my skills hands-on: Hack The Box challenges, a virtual sandbox lab, full Windows disk forensic examinations, and security tools I write in Python, PowerShell, Bash, and SQL.

**Currently focused on:** alert triage and log analysis · detection engineering · digital forensics · endpoint and network security

---

## 💼 Experience

| Role | Organization | Dates |
|---|---|---|
| **Device Deployment Technician** | MCPc, supporting Corewell Health (enterprise healthcare) | Aug 2026 – Present |
| **Tech Assistant / Help Desk Technician** | Godfrey-Lee Public Schools | Aug 2024 – Jul 2025 |

Imaging and deploying endpoints across clinical environments, supporting medical technology (Altus carts, Zebra printers, iPhones), resolving account lockouts and password resets, and troubleshooting Wi-Fi and network connectivity. My [endpoint-admin-toolkit](https://github.com/kamronw23/endpoint-admin-toolkit) and [network-asset-discovery](https://github.com/kamronw23/network-asset-discovery) repos come straight from that work.

---

## 🧰 Skills

| Area | Tools & Concepts |
|---|---|
| **Security Operations** | Log analysis, alert triage, incident response (NIST 800-61), IOC investigation, MITRE ATT&CK, Sigma, Splunk SPL |
| **Digital Forensics** | Magnet AXIOM, Forensic Explorer, FTK Imager, E01 imaging and hash verification, Windows registry analysis (SAM, SYSTEM, SOFTWARE, NTUSER.DAT), USB device attribution, web history and timeline reconstruction, file carving |
| **Networking** | TCP/IP, subnetting, DNS/DHCP, Wi-Fi troubleshooting, network device discovery, firewalls, Wireshark, Nmap |
| **Systems & Endpoints** | Windows (Event Viewer, PowerShell, BitLocker, Defender), Linux (CLI, auth logs, hardening), device imaging, hardware lifecycle refresh |
| **Programming** | Python, SQL, PowerShell, Bash |
| **Labs & Practice** | Hack The Box, virtual sandbox / hacklab (VirtualBox, Kali Linux) |

---

## 🔬 Digital Forensics

| Repo | What's inside |
|---|---|
| [**forensic-case-study-mantooth**](https://github.com/kamronw23/forensic-case-study-mantooth) | Full Windows disk examination of an E01 image: hash verification, SAM/SYSTEM/SOFTWARE/NTUSER.DAT analysis, 15 USB devices attributed, web activity timeline, media and document review, evidence-based conclusion |
| [**dfir-toolkit**](https://github.com/kamronw23/dfir-toolkit) | Python tools for evidence hashing with chain of custody, file signature analysis, USBSTOR parsing, and super-timeline building |
| [**dfir-cheatsheets**](https://github.com/kamronw23/dfir-cheatsheets) | Quick references: Windows registry artifacts, Windows Event IDs, forensic process and evidence handling, Linux logs and live triage |

---

## 🚨 Security Operations & Detection

| Repo | What's inside |
|---|---|
| [**security-scripts**](https://github.com/kamronw23/security-scripts) | 7 defensive tools: SSH and Windows brute-force detection, phishing email triage, IOC extraction, file integrity monitoring, password audit, lab port scanner |
| [**siem-detection-rules**](https://github.com/kamronw23/siem-detection-rules) | 7 detections in Sigma + Splunk SPL, mapped to MITRE ATT&CK and validated in CI |
| [**sql-threat-hunting**](https://github.com/kamronw23/sql-threat-hunting) | Parses SSH and web logs into SQLite, then 8 SQL hunts for brute force, spraying, SQL injection, web shells, and post-compromise activity |
| [**soc-playbooks**](https://github.com/kamronw23/soc-playbooks) | Incident response playbooks (phishing, brute force, malware), an alert triage checklist, and an incident report template |

---

## 🖥️ Endpoint & Network Security

| Repo | What's inside |
|---|---|
| [**endpoint-admin-toolkit**](https://github.com/kamronw23/endpoint-admin-toolkit) | PowerShell: device inventory (serial, BitLocker, TPM), endpoint security baseline, layered network troubleshooter, account lockout investigator |
| [**network-asset-discovery**](https://github.com/kamronw23/network-asset-discovery) | Python: ping/ARP discovery, MAC vendor lookup, device fingerprinting, and baseline diffing to catch rogue devices and ARP spoofing |
| [**linux-hardening-audit**](https://github.com/kamronw23/linux-hardening-audit) | Read-only Bash audit of SSH, users, firewall, exposed services, permissions, logging, and updates, with a fix for every finding |

**How it all connects:** a detection fires (*siem-detection-rules*, *sql-threat-hunting*) → I triage it with a playbook (*soc-playbooks*) → I investigate with my tools (*security-scripts*, *dfir-toolkit*) → I harden and verify endpoints (*endpoint-admin-toolkit*, *linux-hardening-audit*).

---

## 🔐 Labs & Projects

| Project | What I did | Security relevance |
|---|---|---|
| [**Personal Virtual Hacklab**](https://drive.google.com/file/d/1t9wqnAAK8_sGBh1gKonmNQfGmrKsQgfX/view?usp=share_link) | Built an isolated lab of virtual machines to practice attacks and defenses safely | A sandbox for testing exploits, detections, and hardening without touching production |
| [**Configuring a Virtual Network**](https://drive.google.com/file/d/1d69dLMCSbIqIiaOmHCsFnIQIIQ1tTwG5/view?usp=share_link) | Designed and configured a virtual network: addressing, connectivity, and segmentation | Network segmentation is a core control for limiting lateral movement |
| [**Windows BASH Shell**](https://drive.google.com/file/d/1lbeNrROTt86JBd6-acOb3TKM25IaNs20/view?usp=share_link) | Set up and used a Bash environment on Windows | Lets one analyst workstation run Linux security tooling and parse logs |
| [**Binary Date & Time Conversion**](https://drive.google.com/file/d/1EvYfgT1iWJ2s6PHZoeXV4lxcytzh6Nc1/view?usp=share_link) | Converted raw binary and hex timestamps into readable date/time values | Decoding timestamps is a basic forensics and log-timeline skill |

---

## 🎖️ Certifications & Education

| Credential | Issuer | Year |
|---|---|---|
| [CompTIA Security+](https://www.comptia.org/en-us/certifications/security/) | CompTIA | 2026 |
| [CompTIA Network+](https://www.comptia.org/en-us/certifications/network/) | CompTIA | 2026 |
| Python Essentials | Edube.org (OpenEDG Python Institute) | 2026 |
| **B.S., Information Security & Intelligence** | Ferris State University | Expected May 2028 |
| **Associate Degree, Information Security & Intelligence** | Ferris State University | May 2026 |

---

## 🗄️ Data & Database Work

Data integrity and availability are two thirds of the CIA triad, so these projects connect to security too.

- [**Database Backup & Recovery: Step-by-Step**](https://drive.google.com/file/d/1GpPLHatlSpdE6lbwUgKtZAP3DDpA-C_P/view?usp=share_link): backup strategy and restore procedures (availability and disaster recovery)
- [**Database Standards & Procedures**](https://drive.google.com/file/d/1PqE_ID2_bTQ0JTCrIBuU0gYO5ljRVs8C/view?usp=share_link): documented standards, access, and change procedures
- [**Database Design**](https://drive.google.com/file/d/1FEEAS7UCGMAX8GYtg-inRmbrBrtyob6z/view?usp=share_link): normalized schema design
- [**Tableau Data Analysis Project**](https://www.youtube.com/watch?v=ZrGaCQyevcw): video walkthrough of a data analysis dashboard

---

## 🎯 What I'm Working Toward

- [ ] Build a home SIEM lab (Splunk Free / Elastic / Microsoft Sentinel) and replay attacks against my detection rules
- [ ] Complete SOC-focused hands-on paths (Hack The Box, TryHackMe SOC Level 1, Blue Team Labs Online)
- [ ] Next certification: CompTIA CySA+

---

<p align="center"><i>Open to SOC Analyst, Security Analyst, and Digital Forensics roles. Let's connect on <a href="https://www.linkedin.com/in/kam-ron-washington-2003a93a0/">LinkedIn</a>.</i></p>

---
