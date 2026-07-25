🛡️ Passive OSINT & Surface Reconnaissance

**Growfinix Cybersecurity Internship – Task 1**

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-OSINT-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Scope](https://img.shields.io/badge/Scope-Passive%20Reconnaissance-orange)
![Target](https://img.shields.io/badge/Target-tesla.com-red)

---

## 📑 Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
- [Repository Structure](#repository-structure)
- [Key Findings](#key-findings)
- [Scope & Ethical Boundaries](#scope--ethical-boundaries)
- [Learning Outcomes](#learning-outcomes)
- [Disclaimer](#disclaimer)
- [Author](#author)

---

## Overview

This repository documents **Task 1 – Passive Open Source Intelligence (OSINT) & Surface Reconnaissance** for the **Growfinix Cybersecurity Internship Program**.

The project demonstrates professional information gathering techniques using publicly available sources without any direct interaction with target infrastructure. This assessment follows industry best practices for passive reconnaissance and maintains strict ethical and legal compliance.

**Scope:** Passive reconnaissance only. No port scanning, vulnerability scanning, exploitation, credential attacks, or unauthorized access attempts were conducted.

---

## Objectives

- Understand the reconnaissance phase of penetration testing workflows
- Collect and analyze publicly available domain information
- Enumerate DNS configurations and records
- Identify publicly indexed subdomains via certificate transparency
- Examine domain registration details and infrastructure
- Document findings in a professional security report format
- Demonstrate adherence to ethical cybersecurity practices

---

## Tools & Technologies

| Tool | Purpose | Data Collected |
|------|---------|-----------------|
| **WHOIS** | Domain registration & registrar information | Registration details, nameservers, contact info |
| **dig** | DNS record enumeration | A, AAAA, MX, TXT, CNAME records |
| **nslookup** | Domain name resolution | IP addresses, DNS configuration |
| **theHarvester** | Passive subdomain & email enumeration | Publicly indexed hosts and domains |
| **CRT.sh** | Certificate Transparency logs | SSL/TLS certificate data |
| **CertSpotter** | Certificate monitoring & transparency | Public certificate records |
| **RapidDNS** | Passive DNS enumeration | Historical and current DNS records |

---

## Methodology

The reconnaissance workflow followed a structured, non-intrusive approach:

```
┌─────────────────┐
│  Target Domain  │
│   (tesla.com)   │
└────────┬────────┘
         │
         ▼
┌──────────────────────┐
│  WHOIS Enumeration   │
│  (Registration Data) │
└────────┬─────────────┘
         │
         ▼
┌──────────────────────┐
│  DNS Enumeration     │
│  (Records & Config)  │
└────────┬─────────────┘
         │
         ▼
┌──────────────────────┐
│  Certificate Analysis│
│  (Transparency Logs) │
└────────┬─────────────┘
         │
         ▼
┌──────────────────────┐
│  Passive DNS Lookup  │
│  (Subdomain Hunting) │
└────────┬─────────────┘
         │
         ▼
┌──────────────────────┐
│  Evidence Collection │
│  & Documentation     │
└──────────────────────┘
```

**Key Principle:** All data was obtained from publicly accessible sources without interacting with Tesla's infrastructure.

---

## Repository Structure

```
passive-osint-reconnaissance/
│
├── README.md                          # Project overview & documentation
├── REPORT.md                          # Detailed findings & analysis
├── COMMANDS.md                        # Tools & commands executed
│
├── evidence/
│   ├── whois-output.txt               # WHOIS enumeration results
│   ├── dns-records.txt                # DNS query results
│   ├── nslookup-results.txt           # Domain resolution data
│   ├── harvester-crtsh.txt            # theHarvester CRT.sh output
│   ├── harvester-certspotter.txt      # theHarvester CertSpotter output
│   ├── harvester-rapiddns.txt         # theHarvester RapidDNS output
│   └── screenshots/                   # Terminal screenshots & output
│
└── LICENSE
```

---

## Key Findings

### Domain Registration
- Domain registration metadata retrieved from WHOIS database
- Registrar and administrative contact information documented
- Authoritative nameservers identified

### DNS Infrastructure
- Primary DNS records enumerated (A, AAAA, MX, TXT, CNAME)
- Mail server configuration reviewed
- SPF and domain verification records documented

### Certificate Transparency
- Public certificate records reviewed from transparency logs
- Certificate issuers and validity periods documented
- Publicly indexed subdomains identified

### Passive DNS Analysis
- Publicly accessible DNS records examined
- Historical DNS data reviewed from passive sources
- No unauthorized queries or zone transfers performed

---

## Scope & Ethical Boundaries

### ✅ Activities Conducted
- WHOIS queries on public registries
- DNS record enumeration
- Certificate transparency log analysis
- Passive DNS database searches
- Public documentation review

### ❌ Activities NOT Conducted
- Port scanning or service enumeration
- Vulnerability scanning or assessment
- Exploitation or proof-of-concept attacks
- Credential testing or brute-force attacks
- Social engineering attempts
- Unauthorized network access
- Active reconnaissance of any kind

**Legal Compliance:** This assessment was conducted in accordance with applicable laws and ethical guidelines. All data sources are publicly accessible and require no special permissions to query.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- **Passive Reconnaissance:** Understanding information gathering without target interaction
- **Open Source Intelligence (OSINT):** Leveraging public sources for security intelligence
- **DNS Analysis:** Interpreting DNS records and infrastructure
- **Domain Registration Research:** Analyzing WHOIS and registrar data
- **Certificate Transparency:** Understanding SSL/TLS certificate ecosystems
- **Security Documentation:** Professional report writing and evidence presentation
- **Ethical Hacking:** Maintaining compliance with legal and ethical boundaries
- **Industry Best Practices:** Following professional penetration testing standards

---

## Disclaimer

**Educational Purpose:** This repository has been created solely for educational purposes as part of the Growfinix Cybersecurity Internship program.

**Public Data Only:** All information presented in this repository was obtained from publicly accessible sources and databases. No unauthorized access, intrusion, or hacking of any kind was performed.

**No Vulnerabilities Claimed:** This project does not claim the existence of vulnerabilities, security weaknesses, or unauthorized access to Tesla or any organization.

**Passive Assessment:** This represents a passive reconnaissance exercise and does not constitute an authorized security assessment or penetration test.

**Usage:** This repository is intended for educational and legitimate security research purposes only. Unauthorized access to computer systems is illegal.

---

## Author

**Khushal Mudgil**  
Cybersecurity Internship - Growfinix  
BCA Student | Security Researcher

---

## License

This project is licensed under the MIT License – see the LICENSE file for details.

---

<div align="center">

⭐ If you found this repository helpful, consider giving it a star.

*Last Updated: 2026*

</div>
```- DNS record enumeration
- Certificate transparency log analysis
- Passive DNS database searches
- Public documentation review

### ❌ Activities NOT Conducted
- Port scanning or service enumeration
- Vulnerability scanning or assessment
- Exploitation or proof-of-concept attacks
- Credential testing or brute-force attacks
- Social engineering attempts
- Unauthorized network access
- Active reconnaissance of any kind

**Legal Compliance:** This assessment was conducted in accordance with applicable laws and ethical guidelines. All data sources are publicly accessible and require no special permissions to query.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- **Passive Reconnaissance:** Understanding information gathering without target interaction
- **Open Source Intelligence (OSINT):** Leveraging public sources for security intelligence
- **DNS Analysis:** Interpreting DNS records and infrastructure
- **Domain Registration Research:** Analyzing WHOIS and registrar data
- **Certificate Transparency:** Understanding SSL/TLS certificate ecosystems
- **Security Documentation:** Professional report writing and evidence presentation
- **Ethical Hacking:** Maintaining compliance with legal and ethical boundaries
- **Industry Best Practices:** Following professional penetration testing standards

---

## Disclaimer

**Educational Purpose:** This repository has been created solely for educational purposes as part of the Growfinix Cybersecurity Internship program.

**Public Data Only:** All information presented in this repository was obtained from publicly accessible sources and databases. No unauthorized access, intrusion, or hacking of any kind was performed.

**No Vulnerabilities Claimed:** This project does not claim the existence of vulnerabilities, security weaknesses, or unauthorized access to Tesla or any organization.

**Passive Assessment:** This represents a passive reconnaissance exercise and does not constitute an authorized security assessment or penetration test.

**Usage:** This repository is intended for educational and legitimate security research purposes only. Unauthorized access to computer systems is illegal.

---

## Author

**Khushal Mudgil**  
Cybersecurity Internship - Growfinix  
BCA Student | Security Researcher

---

## License

This project is licensed under the MIT License – see the LICENSE file for details.

---

⭐ If you found this repository helpful, consider giving it a star.

*Last Updated: July 2026*
