# 🛡️ Passive OSINT & Surface Reconnaissance

**Growfinix Cybersecurity Internship – Task 1**

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-OSINT-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Scope](https://img.shields.io/badge/Scope-Passive%20Reconnaissance-orange)
![Target](https://img.shields.io/badge/Target-tesla.com-red)

---

## 📋 Table of Contents

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

**Key Principle:** All data was obtained from publicly accessible sources without interacting with Tesla's infrastructure.

---

## Repository Structure

