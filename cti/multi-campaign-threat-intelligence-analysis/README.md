# Multi-Campaign Threat Intelligence Analysis

## Overview

This project presents a comprehensive Cyber Threat Intelligence (CTI) investigation workflow conducted using MISP, TheHive, and Cortex.

The objective of this project was to simulate the end-to-end intelligence lifecycle by creating threat intelligence events, documenting indicators of compromise (IOCs), enriching observables, mapping adversary behaviors to MITRE ATT&CK, and managing investigations through case management workflows.

The project covers multiple threat campaigns and demonstrates practical CTI skills applicable to real-world intelligence operations.

---

## Objectives

The objectives of this investigation were to:

- Create and manage threat intelligence events in MISP.
- Document and classify indicators of compromise.
- Apply MITRE ATT&CK techniques to observed behaviors.
- Practice intelligence sharing workflows.
- Create and investigate cases using TheHive.
- Add and investigate observables.
- Enrich observables using Cortex analyzers.
- Produce structured intelligence documentation.

---

## Threat Campaigns Covered

| Campaign | Category |
|----------|----------|
| Lazarus / AsyncRAT | Remote Access Trojan (RAT) |
| MOVEit Exploitation | Exploitation Campaign |
| BlackCat (ALPHV) | Ransomware |
| RedLine Stealer | Information Stealer |

---

## Tools Used

| Tool | Purpose |
|--------|--------|
| MISP | Threat intelligence event management |
| TheHive | Case management and investigations |
| Cortex | Observable enrichment |
| VirusTotal | Reputation analysis |
| URLScan | URL investigation |
| Hybrid Analysis | Sandbox enrichment |
| AbuseIPDB | IP reputation analysis |
| MITRE ATT&CK | Adversary behavior mapping |

---

## Investigation Workflow

```text
Threat Scenario
        ↓
Create MISP Event
        ↓
Add IOC Attributes
        ↓
Apply Tags
        ↓
MITRE ATT&CK Mapping
        ↓
Delegate Share / Publish
        ↓
Create TheHive Case
        ↓
Add Observables
        ↓
Run Cortex Analyzers
        ↓
Document Findings
```

---

## Intelligence Activities

### MISP

- Event Creation
- IOC Documentation
- Threat Classification
- Tag Management
- Event Publishing
- Delegate Sharing

### TheHive

- Case Creation
- Observable Management
- Investigation Tracking
- Case Documentation
- Incident Review

### Cortex

- VirusTotal Analysis
- URLScan Analysis
- Hybrid Analysis
- AbuseIPDB Checks
- IOC Enrichment

---

## Campaign Highlights

### Lazarus / AsyncRAT

Activities performed:

- Created MISP threat intelligence event.
- Added indicators of compromise.
- Applied threat tags.
- Mapped techniques to MITRE ATT&CK.
- Investigated observables using TheHive.
- Enriched indicators using Cortex analyzers.

### MOVEit Exploitation

Activities performed:

- Documented exploitation-related indicators.
- Added infrastructure observables.
- Performed intelligence enrichment.
- Mapped exploitation techniques.

### BlackCat (ALPHV)

Activities performed:

- Documented ransomware-related indicators.
- Investigated threat infrastructure.
- Performed intelligence enrichment.
- Applied ATT&CK mappings.

### RedLine Stealer

Activities performed:

- Added malware indicators.
- Investigated command-and-control artifacts.
- Enriched indicators using Cortex.
- Documented findings.

---

## Intelligence Outputs

| Output | Description |
|----------|----------|
| IOC Documentation | Threat indicators collected and categorized |
| MITRE Mapping | ATT&CK techniques associated with campaigns |
| TheHive Cases | Investigation tracking and documentation |
| Cortex Results | IOC enrichment and reputation analysis |
| Threat Reports | Structured intelligence reporting |

---

## Supporting Documentation

- [Indicators of Compromise](iocs.md)
- [MITRE ATT&CK Mapping](mitre-attack-mapping.md)

---

## Screenshots

Representative screenshots are stored in the `screenshots/` directory.

| Screenshot | Description |
|------------|------------|
| 01-misp-event-overview.png | MISP Event Overview |
| 02-misp-ioc-attributes.png | IOC Attributes |
| 03-misp-tags-and-sharing.png | Tags and Sharing Settings |
| 04-thehive-case-overview.png | TheHive Case Overview |
| 05-thehive-observables.png | Observable Investigation |
| 06-cortex-virustotal-analysis.png | VirusTotal Results |
| 07-cortex-hybrid-analysis.png | Hybrid Analysis Results |
| 08-mitre-mapping-example.png | MITRE ATT&CK Mapping |

---

## Repository Structure

```text
multi-campaign-threat-intelligence-analysis/
│
├── README.md
├── iocs.md
├── mitre-attack-mapping.md
└── screenshots/
```

---

## Key Skills Demonstrated

- Cyber Threat Intelligence
- Threat Investigation
- IOC Analysis
- Intelligence Enrichment
- MISP Administration
- TheHive Case Management
- Cortex Analyzer Usage
- MITRE ATT&CK Mapping
- Threat Reporting
- Intelligence Lifecycle Operations

---

## Learning Outcomes

Through this project, I gained hands-on experience with the intelligence lifecycle, threat investigation workflows, IOC management, ATT&CK mapping, intelligence enrichment, and structured reporting using MISP, TheHive, and Cortex.

---

## Disclaimer

Sensitive information, credentials, API keys, and private data have been removed prior to publication.

This project is shared for educational and portfolio purposes only.