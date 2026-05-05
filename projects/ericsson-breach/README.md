[README.md](https://github.com/user-attachments/files/27410613/README.md)# Third-Party Vendor Vulnerabilities: 2025 Ericsson Service Provider Breach

**Course:** Information Technology Security (ITSY 1342)  
**Institution:** Del Mar College  
**Date:** April 2026

## Overview

This research paper analyzes the April 2025 Ericsson service provider vishing breach through the CIA triad framework. A threat actor called an employee at a third-party vendor of Ericsson Inc. and gained unauthorized access to sensitive data belonging to 15,661 individuals. Despite the breach occurring in April 2025, affected individuals were not notified until March 2026, representing an eleven-month compliance failure.

## Incident Summary

- **Attack type:** Vishing (voice phishing / social engineering)
- **Breach window:** April 17 to April 22, 2025
- **Individuals affected:** 15,661
- **Data compromised:** Names, addresses, Social Security numbers, driver's license numbers, financial information, medical information, and dates of birth
- **Notification delay:** Eleven months from breach to public notification

## CIA Triad Analysis

| Pillar | Failure |
|---|---|
| Confidentiality | No MFA in place, credentials compromised via vishing |
| Integrity | Seven-month delay made clean data baseline impossible to establish |
| Availability | Forced password resets and system disruptions caused operational downtime |

## Proposed Mitigations

- Implement multi-factor authentication for all vendor access
- Deploy a SIEM for real-time audit logging and anomaly detection
- Apply least privilege access controls to limit breach scope
- Develop a third-party vendor incident response plan
- Conduct regular employee cybersecurity awareness training

## Files

| File | Description |
|---|---|
| `Ericsson_Vishing_Breach_Ameyer.pdf` | Full research report |

## Frameworks Referenced

CIA Triad, NIST, CMMC 2.0, DFARS incident reporting requirements

