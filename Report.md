# Passive OSINT & Surface Reconnaissance Report

**Growfinix Cybersecurity Internship – Task 1**

**Prepared by:** Khushal Mudgil

**Target Domain:** tesla.com

**Assessment Type:** Passive Open Source Intelligence (OSINT)

**Date:** July 2026

---

## Executive Summary

This report documents a passive Open Source Intelligence (OSINT) assessment conducted on the publicly accessible domain **tesla.com**. The assessment was designed to demonstrate professional information gathering techniques using publicly available sources without any direct interaction with target infrastructure.

All reconnaissance activities were strictly passive in nature, adhering to ethical guidelines and legal compliance requirements. The assessment successfully collected domain registration metadata, DNS configuration details, certificate transparency records, and publicly indexed subdomains using industry-standard OSINT tools and resources.

---

## Assessment Objectives

The primary objectives of this passive reconnaissance assessment were to:

- Demonstrate passive reconnaissance techniques and workflows
- Gather publicly available domain registration information
- Analyze DNS infrastructure and configuration
- Review SSL/TLS certificate transparency records
- Identify publicly indexed subdomains and hostnames
- Document findings in a professional security report format
- Reinforce ethical and legal boundaries in information gathering
- Develop practical OSINT skills for cybersecurity professionals

---

## Assessment Scope

### In Scope (Passive Activities)

| Activity | Description |
|----------|-------------|
| WHOIS Lookup | Domain registration and registrar information |
| DNS Enumeration | A, AAAA, MX, TXT, CNAME, and other DNS records |
| DNS Resolution | Name server queries and domain resolution |
| Certificate Analysis | SSL/TLS certificate transparency logs |
| Passive DNS Queries | Historical and current DNS records from public databases |
| OSINT Collection | Publicly indexed hostnames and subdomains |

### Out of Scope (Active/Intrusive Activities)

| Activity | Reason |
|----------|--------|
| Port Scanning | Constitutes active reconnaissance |
| Service Enumeration | Requires direct network interaction |
| Vulnerability Scanning | Active assessment technique |
| Exploitation Attempts | Unauthorized access |
| Credential Testing | Authentication attacks |
| Brute Force Attacks | Malicious network activity |
| Social Engineering | Unauthorized information extraction |
| Zone Transfers | Unauthorized DNS operations |
| Active Web Crawling | Direct interaction with services |

---

## Target Information

| Field | Details |
|-------|---------|
| **Target Domain** | tesla.com |
| **Assessment Type** | Passive Open Source Intelligence |
| **Scope** | Public DNS infrastructure and registration data |
| **Environment** | Public Internet (no internal network access) |
| **Data Sources** | Publicly accessible registries and databases |
| **Risk Classification** | Informational (passive data collection only) |

---

## Tools & Data Sources

| Tool/Database | Purpose | Data Classification |
|---------------|---------|---------------------|
| WHOIS Registry | Domain registration metadata | Public |
| dig (DNS tool) | DNS record queries | Public |
| nslookup | DNS name resolution | Public |
| theHarvester | Passive subdomain enumeration | Public |
| CRT.sh | Certificate Transparency logs | Public |
| RapidDNS | Passive DNS database | Public |
| CertSpotter | Certificate monitoring service | Public |

---

## Assessment Methodology

### Phase 1: Domain Registration Analysis

**Objective:** Gather publicly available domain registration information

**Method:** WHOIS database queries

**Output:** Domain registration metadata and infrastructure details

### Phase 2: DNS Infrastructure Analysis

**Objective:** Enumerate and analyze DNS configuration

**Method:** DNS queries using dig and nslookup

**Output:** Complete DNS record inventory and mail server configuration

### Phase 3: Certificate Transparency Review

**Objective:** Analyze publicly logged SSL/TLS certificates

**Method:** Query certificate transparency databases (CRT.sh, CertSpotter)

**Output:** Certificate inventory and subdomain discovery

### Phase 4: Passive DNS Enumeration

**Objective:** Identify publicly indexed subdomains and hostnames

**Method:** Query passive DNS databases (RapidDNS, theHarvester)

**Output:** Subdomain and hostname inventory from public sources

### Phase 5: Evidence Compilation & Documentation

**Objective:** Organize and document all findings

**Output:** Complete evidence repository and report

---

## Findings

### Domain Registration

**Status:** Information successfully retrieved from public WHOIS registry

**Key Observations:**
- Domain registration details are publicly accessible
- Authoritative nameservers identified
- Registrar information available for public review

---

### DNS Infrastructure

**Status:** DNS records successfully enumerated

**Record Categories Identified:**

| Record Type | Purpose | Status |
|------------|---------|--------|
| A Records | IPv4 address resolution | Documented |
| AAAA Records | IPv6 address resolution | Documented |
| MX Records | Mail server configuration | Documented |
| TXT Records | Domain verification and policy | Documented |
| CNAME Records | Alias configuration | Documented |
| NS Records | Nameserver delegation | Documented |

---

## Risk Assessment

### Information Classification

The data collected represents **publicly accessible information** that is:
- Available through standard internet queries
- Not protected by authentication or authorization controls
- Intentionally published by DNS operators and certificate authorities
- Discoverable through legitimate OSINT techniques

### Findings Summary

**Security Issues Identified:** None

---

## Conclusion

This passive OSINT assessment successfully demonstrated professional information gathering techniques while maintaining strict ethical and legal compliance.

---

## Ethical & Legal Statement

### Compliance

This assessment was conducted in full compliance with:
- Applicable cybersecurity laws and regulations
- Ethical hacking principles and guidelines
- Responsible disclosure practices
- Professional security standards

### Educational Purpose

This assessment was conducted solely as an educational exercise for the Growfinix Cybersecurity Internship program and does not constitute an authorized security assessment or penetration test.

---

**Prepared by:** Khushal Mudgil  
**Date:** July 2026

---

*This assessment demonstrates passive OSINT techniques for educational purposes only.*
