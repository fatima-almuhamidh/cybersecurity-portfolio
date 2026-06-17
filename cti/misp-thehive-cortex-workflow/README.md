# MISP, TheHive, and Cortex CTI Workflow

## Overview
This project demonstrates a Cyber Threat Intelligence workflow using MISP, TheHive, and Cortex. The lab focused on creating threat intelligence events, enriching indicators, sharing intelligence between organizations, and supporting incident response decisions.

## Objective
The objective was to simulate a CTI environment where multiple organizations exchange threat intelligence related to APT activity, vulnerability exploitation, ransomware, and infostealer malware.

## Tools Used
- MISP
- TheHive
- Cortex
- VirusTotal
- URLScan
- AbuseIPDB
- Hybrid Analysis
- PulseDive
- Hunter.io
- MITRE ATT&CK

## Threat Events Created
1. Lazarus Group / AsyncRAT targeting the financial sector
2. MOVEit Transfer exploitation related to CVE-2023-34362
3. BlackCat / ALPHV ransomware targeting logistics
4. Redline Stealer credential theft activity

## Skills Demonstrated
- MISP event creation
- Threat intelligence sharing
- IOC enrichment
- TheHive case creation
- Cortex analyzer execution
- MITRE ATT&CK mapping
- Intelligence value assessment
- Final decision making based on evidence

## Methodology
1. Created multiple organizations in MISP.
2. Added threat intelligence events with IOCs, tags, threat levels, and references.
3. Published selected events to connected communities.
4. Used delegation sharing for restricted events.
5. Created investigation cases in TheHive.
6. Added observables from MISP into TheHive.
7. Ran Cortex analyzers to enrich observables.
8. Assessed the results and produced a final response decision.

## Key Findings
- High-risk threat activity was identified across financial, technology, logistics, and healthcare sectors.
- IOC enrichment supported the classification of malicious infrastructure and files.
- Cortex analysis helped validate the threat level and supported blocking decisions.
- TLP/PAP restrictions affected outbound analysis and required proper handling.

## Final Decision
The suspicious indicators were assessed as malicious or high-risk. Blocking actions were recommended for confirmed malicious IPs, domains, hashes, and related infrastructure.

## Lessons Learned
- CTI platforms must handle information sharing carefully based on TLP and PAP.
- IOC enrichment is useful, but final decisions require context, confidence levels, and source validation.
- MISP, TheHive, and Cortex together provide a strong workflow for CTI-driven investigations.

## Portfolio Note
All credentials, API keys, private lab details, and sensitive screenshots were removed before publishing.