# Assessment Notes

**Growfinix Cybersecurity Internship – Task 1**

**Prepared by:** Khushal Mudgil

**Date:** July 2026

---

## Overview

Supplementary notes and observations from the passive OSINT assessment.

---

## Key Takeaways

### 1. Infrastructure Insights

- **DNS Infrastructure:** Oracle Cloud DNS with 4 nameservers
- **Mail Infrastructure:** 5 MX records with priority levels
- **SSL/TLS:** Wildcard certificate for centralized management
- **Load Balancing:** Multiple IPv4 addresses

### 2. Passive OSINT Effectiveness

- Public sources provide significant infrastructure visibility
- Multiple sources provide complementary information
- No active probing required for comprehensive data

### 3. Ethical Considerations

- All information from public, non-authenticated sources
- Standard operations reveal significant details
- Organizations should understand exposure

---

## Tools Comparison

| Tool | Strengths | Limitations |
|------|-----------|-------------|
| WHOIS | Direct registration data | May be redacted |
| dig | Complete DNS control | No subdomains |
| nslookup | Standard resolver | Limited scope |
| CRT.sh | Certificate logs | Indexing delays |
| CertSpotter | Current certificates | Different datasets |
| RapidDNS | Historical records | Limited entries |

---

## Recommendations

### Immediate Actions
- Audit public records
- Verify DNS configuration
- Check certificate logs

### Long-term Strategy
- Continuous monitoring
- Automated scanning
- Regular assessments

---

**Date:** July 2026
