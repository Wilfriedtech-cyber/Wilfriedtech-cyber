<h1 align="center">Wilfried Ogou</h1>
<h3 align="center">Cybersecurity Student | Application Control Technician </h3>

<p align="center">
  <a href="https://www.linkedin.com/in/wilfried-ogou/">LinkedIn</a> •
  Orlando, FL
</p>

---

### About Me

Junior at the **University of Central Florida** pursuing a B.S. in Information Technology with a Cybersecurity minor (expected 2028). Working full-time as an Application Technician at **ThreatLocker** enforcing zero-trust endpoint security, and serving as an SMP Cadet / Combat Medic in the **U.S. Army Reserve** — all at the same time.

I use my free time to build labs, break things, and document everything.

**Target role:** Security Analyst in the cleared defense space.

---

### Certifications

| Certification | Status |
|---|---|
| CompTIA A+ | ✅ |
| CompTIA Network+ | ✅ |
| CompTIA Security+ | ✅ |
| Security Blue Team BTL1 | ✅ |
| CompTIA CySA+ | ✅ |
| Splunk Core Certified User | ✅ |

---

### Projects

#### 🔴 Adversary Emulation & Detection Series — Homelab

Built a full SOC homelab from scratch on VMware ESXi:

**Infrastructure:** pfSense firewall + Suricata IDS, Windows Active Directory (DC + Win10 client), Splunk SIEM with Universal Forwarders + Sysmon, Cowrie SSH honeypot, DVWA vulnerable web app, MITRE Caldera C2 for adversary emulation.

Each scenario emulates a real attack chain using Caldera, then builds behavior-based Splunk detections mapped to MITRE ATT&CK — validated against live telemetry.

| Scenario | Techniques | Status |
|---|---|---|
| [Credential Dumping via LSASS (Mimikatz)](https://github.com/Wilfriedtech-cyber/Threat-emulation-and-Detection-Scenario/blob/main/Credential%20Dumping%20via%20LSASS(Mimikatz).md) | T1003.001 • T1550.002 • T1059.001 | ✅ Published |
| [SMB Lateral Movement & Data Exfiltration](https://github.com/Wilfriedtech-cyber/Threat-emulation-and-Detection-Scenario/blob/main/SMB%20Lateral%20Movement%20%26%20Data%20Exfiltration.md) | T1021.002 • T1074.001 • T1041 | ✅ Published |
| Honeypot Attacker Fingerprinting via Cowrie SSH | T1110 • T1059 • T1082 | ✅ Published |
| Persistence via Scheduled Task & Registry Run Key | T1053.005 • T1547.001 | 🔄 In Progress |

---

#### 🔵 SOC Investigation Lab — Blue Team Labs Online

Completed hands-on SOC investigations and incident analysis on Blue Team Labs Online, including the **Dominance** challenge. Work covers phishing analysis, threat intelligence enrichment, log correlation, and attack timeline reconstruction.

Writeups published on GitHub documenting methodology, tools used, and key findings.

---

#### 🟡 Java Caesar Cipher — Cryptography Basics

Built a basic Caesar cipher implementation in Java as an introduction to encryption concepts — covering character shifting, key-based encoding/decoding, and brute-force decryption logic.

---

### Technical Skills

**Security:** Threat Detection, Log Analysis, Alert Triage, Phishing Analysis, Incident Response

**SIEM & Monitoring:** Splunk SPL, Sysmon, Windows Event Logs, Suricata

**Adversary Emulation:** MITRE Caldera, MITRE ATT&CK, Mimikatz, Hydra

**Endpoint Security:** Application Allowlisting, Zero Trust, ThreatLocker

**OS & CLI:** Windows, Linux, PowerShell, Bash

**Networking:** TCP/IP, pfSense, Wireshark, Nmap

**Frameworks:** MITRE ATT&CK, NIST, Cyber Kill Chain

---

### Currently Working On

- Completing the 4-scenario adversary emulation series
- Learning Python and Git for scripting and automation
- Finishing B.S. at UCF (expected 2028)

---

*All homelab work performed in an isolated environment against dummy test data.*
