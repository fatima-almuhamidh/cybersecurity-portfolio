# Italy Cyber Attack Investigation

## Overview

This project presents a network forensic investigation involving a cyber attack targeting an organization in Italy.

The investigation focused on analyzing packet capture (PCAP) data, identifying malicious communications, reconstructing the infection chain, extracting indicators of compromise (IOCs), and documenting adversary activity.

The analysis involved multiple malware families including Pushdo and Ursnif and leveraged network artifacts to understand attacker behavior and infrastructure.

---

## Project Context

This project was completed as part of a team-based cybersecurity investigation exercise.

The investigation was conducted collaboratively, with team members contributing to different parts of the analysis and reporting process.

### My Contribution

My primary responsibility in this project was DNS analysis.

My work focused on:

- Reviewing DNS traffic in Wireshark.
- Identifying suspicious domain queries.
- Investigating domain patterns related to malware activity.
- Correlating DNS activity with the overall infection chain.
- Supporting IOC extraction from DNS artifacts.
- Contributing DNS-related findings to the final investigation report and presentation.

The findings documented in this repository focus on the analysis activities and investigation areas that I personally contributed to within the team project.

---

## Investigation Objectives

The objectives of this investigation were to:

- Analyze network traffic captures.
- Identify malicious communications.
- Investigate malware delivery mechanisms.
- Trace command-and-control communications.
- Extract indicators of compromise.
- Reconstruct the infection chain.
- Analyze DNS activity.
- Analyze TLS communications.
- Document attacker infrastructure.

---

## Scenario Summary

The investigation revealed evidence of:

- Malicious Microsoft Word document delivery.
- Pushdo malware activity.
- Ursnif malware communications.
- Suspicious DNS queries.
- Command-and-control communications.
- HTTP POST activity.
- External attacker infrastructure.

---

## Malware Families Identified

| Malware | Category |
|----------|----------|
| Pushdo | Malware Downloader |
| Ursnif | Banking Trojan |

---

## Tools Used

| Tool | Purpose |
|----------|----------|
| Wireshark | Packet analysis |
| PCAP Files | Network investigation |
| DNS Filters | DNS traffic review |
| DNS Analysis | Domain and query investigation |
| TLS Analysis | Encrypted traffic analysis |
| HTTP Analysis | Web traffic investigation |
| IOC Documentation | Threat intelligence collection |

---

## Investigation Workflow

```text
PCAP Acquisition
        ↓
Traffic Review
        ↓
DNS Analysis
        ↓
Suspicious Domain Identification
        ↓
Correlation With Malware Activity
        ↓
TLS / HTTP Review
        ↓
IOC Extraction
        ↓
Infection Chain Reconstruction
        ↓
Final Report
```

---

## DNS Analysis Focus

Since my main responsibility was DNS analysis, this section summarizes the DNS-focused investigation workflow.

Key DNS analysis activities included:

- Filtering DNS traffic in Wireshark.
- Reviewing queried domains.
- Identifying suspicious or unusual domain activity.
- Checking domain patterns associated with malware behavior.
- Correlating DNS queries with other network events.
- Supporting the identification of potential command-and-control infrastructure.
- Documenting DNS-based indicators of compromise.

---

## Key Findings

The investigation identified:

- Suspicious DNS queries associated with malware activity.
- Malicious document delivery indicators.
- Malware download activity.
- DNS activity supporting infrastructure investigation.
- Suspicious TLS sessions.
- HTTP POST communications.
- External command-and-control infrastructure.
- Indicators suitable for threat hunting and detection.

---

## Analysis Areas

### DNS Analysis

Activities included:

- DNS query review.
- Suspicious domain identification.
- Domain pattern analysis.
- DNS-based IOC extraction.
- Infrastructure correlation.

### TLS Analysis

Activities included:

- TLS session review.
- SNI analysis.
- Encrypted communication identification.
- Supporting traffic correlation.

### HTTP Analysis

Activities included:

- POST request analysis.
- Malware communication review.
- Traffic reconstruction.
- Data transfer review.

---

## Supporting Documentation

- [Indicators of Compromise](iocs.md)
- [Infection Chain](infection-chain.md)
- [Wireshark Analysis](wireshark-analysis.md)

---

## Screenshots

Representative screenshots are stored in the `screenshots/` directory.

| Screenshot | Description |
|------------|------------|
| 01-pcap-overview.png | PCAP Overview |
| 02-dns-analysis.png | DNS Traffic Analysis |
| 03-suspicious-domain-query.png | Suspicious DNS Query |
| 04-dns-ioc-extraction.png | DNS-Based IOC Extraction |
| 05-http-analysis.png | HTTP Traffic |
| 06-tls-analysis.png | TLS Sessions |
| 07-pushdo-activity.png | Pushdo Evidence |
| 08-ursnif-activity.png | Ursnif Evidence |

---

## Repository Structure

```text
italy-cyber-attack-investigation/
│
├── README.md
├── iocs.md
├── infection-chain.md
├── wireshark-analysis.md
└── screenshots/
```

---

## Key Skills Demonstrated

- Network Forensics
- Wireshark Analysis
- DNS Analysis
- Suspicious Domain Investigation
- PCAP Investigation
- IOC Extraction
- Threat Intelligence
- Incident Investigation
- Technical Reporting
- Team-Based Cybersecurity Investigation

---

## Team Project Notice

This repository documents my individual contribution within a larger team investigation.

The complete project deliverables included contributions from multiple team members. My primary contribution was DNS analysis and DNS-based IOC identification.

---

## Learning Outcomes

Through this project, I gained practical experience in analyzing DNS traffic, identifying suspicious domain activity, correlating DNS artifacts with malware behavior, and contributing findings to a team-based network forensic investigation.

---

## Disclaimer

PCAP files, indicators, and screenshots have been sanitized before publication.

This project is shared for educational and portfolio purposes only.