# Cybersecurity Projects Portfolio

Hands-on cybersecurity + cloud security labs focused on **SOC workflows, incident response, threat detection, vulnerability management, and system hardening**.  

Everything here is built to be **repeatable**, **documented**, and **reviewable** (screenshots, configs, commands, findings).

---

## 🧭 Quick Navigation

🧠 **[Enterprise SIEM Lab](https://github.com/Arnold-Luna/cybersecurity-projects/tree/main/Enterprise%20SIEM%20Lab%20%E2%80%93%20Wazuh%20%2B%20Suricata%20%2B%20Kali%20Linux%20%2B%20Fail2Ban)**  
📌 **[Incident Response](https://github.com/Arnold-Luna/cybersecurity-projects/tree/main/Incident%20Response)**  
☁️ **[Cloud Security / AWS](https://github.com/Arnold-Luna/cybersecurity-projects/tree/main/cloud-projects)**  
🖥️ **[Endpoint Security](https://github.com/Arnold-Luna/cybersecurity-projects/tree/main/endpoint-security)**  
🌐 **[Network Defense](https://github.com/Arnold-Luna/cybersecurity-projects/tree/main/network-defense)**  
🧠 **[Threat Analysis](https://github.com/Arnold-Luna/cybersecurity-projects/tree/main/threat-analysis)**  
🛡️ **[Vulnerability Management](https://github.com/Arnold-Luna/cybersecurity-projects/tree/main/vulnerability-management)**

---

## 📂 What’s Inside 

### Incident Response
- **Enterprise SIEM Lab** – Simulated SSH brute-force attack using Hydra, analyzed authentication failures in Wazuh (Rule 5760), mapped activity to MITRE ATT&CK (T1110 – Brute Force), and implemented automated IP blocking with Fail2Ban  
- IR notes, triage workflows, evidence handling, and documented investigations  
- Artifacts: timelines, indicators, root cause, lessons learned

### Cloud Projects (AWS)
- IAM, logging/monitoring, secure networking (VPC), least privilege, audit trails  
- Focus: “secure-by-default” infrastructure patterns

### Endpoint Security
- Hardening steps, detection logic, host-based telemetry, baseline configs  
- Focus: reduce attack surface + catch weird behavior early

### Network Defense
- **Enterprise SIEM Lab** – Conducted Nmap reconnaissance, identified exposed SSH services, correlated brute-force attempts, and validated host-based defensive controls  
- Scanning, segmentation concepts, firewall/ACL logic, traffic analysis  
- Focus: enforce controls and validate them with testing

### Threat Analysis
- **Enterprise SIEM Lab** – Investigated authentication failure spikes, reviewed Wazuh rule metadata, analyzed alert severity, and mapped attacker behavior to MITRE ATT&CK  
- IOC analysis, attacker techniques, mapping to MITRE ATT&CK  
- Focus: explain what happened in normal human language

### Vulnerability Management
- Finding → risk rating → remediation → verification  
- Focus: prioritize what actually reduces risk

---

## 🧪 Project Format 
Most folders follow a structure like:
- **README.md** (overview + objective)
- **steps/** (exact commands + procedure)
- **findings/** (screenshots + outputs)
- **notes/** (why it matters + lessons learned)

---

## 🛠️ Tools & Skills Demonstrated
- SIEM deployment & detection engineering (Wazuh)
- Log ingestion & alert correlation
- MITRE ATT&CK mapping
- SSH brute-force simulation (Hydra)
- Network reconnaissance (Nmap)
- Automated containment (Fail2Ban)
- IAM, least privilege, cloud logging concepts
- Vulnerability lifecycle: identify → assess → mitigate → verify
- Documentation that someone else can reproduce

---

## 📈 Highlights

- **Enterprise SIEM Lab – Wazuh + Suricata + Kali + Fail2Ban**  
  End-to-end attack simulation, detection engineering, MITRE ATT&CK mapping, and automated containment workflow.

- **Email Authentication Assessment (SPF/DKIM/DMARC)**  
  Evidence-based review of email security posture with screenshots + recommendations.

- **AWS Logging & Monitoring Setup**  
  Built baseline logging and auditing posture, validated events, documented findings.

- **Network Recon & Service Enumeration Lab**  
  Ran controlled scans, interpreted results, mapped risk, proposed mitigations.

---

## 🏅 Certifications

- **[CompTIA CYSA+](https://www.credly.com/badges/c019545c-ef1b-4d21-9e1d-06b64f526a68/public_url)**
- **[CompTIA Security+](https://www.credly.com/badges/1799b438-c246-4e19-a714-6b1f6811874c/public_url)**
- **[CompTIA Cloud+](https://www.credly.com/badges/1799b438-c246-4e19-a714-6b1f6811874c/public_url)**
- **[CompTIA Security Analytics Professional (CSAP)](https://www.credly.com/badges/1d5ec92d-63af-4b97-a872-cdf958b3e31c/public_url)**
- **[CompTIA Secure Cloud Professional (CSCP)](https://www.credly.com/badges/e098d92f-cacf-4c34-85d2-6241e9291641/public_url)**
- **[Google Project Management Professional Certificate](https://www.credly.com/badges/a1511b5e-30c4-45ab-90ce-938cdf70d4bb/public_url)**

---

## 📬 Contact
<a href="https://www.linkedin.com/in/arnoldo-luna/">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="40"/>
</a>

---

## Disclaimer
This repository is for **educational and defensive security** purposes.  
All testing is performed in controlled environments or on systems I own/have permission to assess.
