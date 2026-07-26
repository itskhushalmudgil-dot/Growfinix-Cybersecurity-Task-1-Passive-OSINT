# Passive OSINT Command Reference

**Growfinix Cybersecurity Internship – Task 1**

**Prepared by:** Khushal Mudgil

**Target Domain:** tesla.com

---

## Introduction

This document provides a comprehensive reference for all commands executed during the passive OSINT assessment.

---

## WHOIS Enumeration

### Complete Domain WHOIS Lookup

\`\`\`bash
whois tesla.com
\`\`\`

**Description:** Queries the WHOIS registry to retrieve publicly available domain registration information.

---

## DNS Enumeration

### IPv4 Address Lookup (A Record)

\`\`\`bash
dig tesla.com A
\`\`\`

### Mail Server Lookup (MX Records)

\`\`\`bash
dig tesla.com MX
\`\`\`

### Text Record Lookup (TXT Records)

\`\`\`bash
dig tesla.com TXT
\`\`\`

### Nameserver Lookup (NS Records)

\`\`\`bash
dig tesla.com NS
\`\`\`

### Comprehensive DNS Query (All Records)

\`\`\`bash
dig tesla.com +all
\`\`\`

---

## Domain Resolution

### Basic Domain Resolution

\`\`\`bash
nslookup tesla.com
\`\`\`

### DNS Record Type Query

\`\`\`bash
nslookup -type=MX tesla.com
\`\`\`

---

## Certificate Transparency

### Certificate Transparency Search (CRT.sh)

\`\`\`bash
theHarvester -d tesla.com -b crtsh
\`\`\`

### Certificate Search (CertSpotter)

\`\`\`bash
theHarvester -d tesla.com -b certspotter
\`\`\`

### Multiple Certificate Sources

\`\`\`bash
theHarvester -d tesla.com -b crtsh,certspotter
\`\`\`

---

## Passive DNS Enumeration

### Passive DNS Search (RapidDNS)

\`\`\`bash
theHarvester -d tesla.com -b rapiddns
\`\`\`

### Comprehensive Passive OSINT

\`\`\`bash
theHarvester -d tesla.com -b crtsh,certspotter,rapiddns
\`\`\`

---

## Save Results to Files

\`\`\`bash
whois tesla.com > whois.txt
dig tesla.com +all > dns.txt
nslookup tesla.com > nslookup.txt
theHarvester -d tesla.com -b crtsh > certificates.txt
theHarvester -d tesla.com -b rapiddns > passive-dns.txt
\`\`\`

---

## Quick Reference

| Task | Command |
|------|---------|
| Domain registration | \`whois tesla.com\` |
| IPv4 address | \`dig tesla.com A\` |
| Mail servers | \`dig tesla.com MX\` |
| TXT records | \`dig tesla.com TXT\` |
| Nameservers | \`dig tesla.com NS\` |
| All DNS records | \`dig tesla.com +all\` |
| Domain resolution | \`nslookup tesla.com\` |
| Certificates (CRT.sh) | \`theHarvester -d tesla.com -b crtsh\` |
| Certificates (CertSpotter) | \`theHarvester -d tesla.com -b certspotter\` |
| Passive DNS (RapidDNS) | \`theHarvester -d tesla.com -b rapiddns\` |

---

**All commands documented here are passive, ethical, and intended for educational purposes only.**
