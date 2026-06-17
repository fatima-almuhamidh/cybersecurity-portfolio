CTI Workflow: MISP, TheHive, and Cortex

Project Overview

This project is a Cyber Threat Intelligence case study demonstrating how threat intelligence can be collected, structured, enriched, shared, and investigated using MISP, TheHive, and Cortex.

The original work was completed as a practical training task. This version has been rewritten as a professional case study to demonstrate CTI workflow knowledge, threat event documentation, IOC handling, MITRE ATT&CK mapping, and alert investigation process.

Objectives

The main objectives of this project were to:

* Create structured threat intelligence events in MISP.
* Document IOCs related to different threat scenarios.
* Apply relevant MITRE ATT&CK techniques.
* Use tags to classify threat actors, malware, campaigns, and attack types.
* Practice Delegate Share and Publish workflows in MISP.
* Create and investigate a case in TheHive.
* Add observables to TheHive for investigation.
* Enrich observables using Cortex analyzers.
* Document the full CTI workflow in a clear and professional format.

Tools Used

Tool	Purpose
MISP	Threat intelligence event creation, IOC management, tagging, and sharing
TheHive	Case management and investigation workflow
Cortex	Observable enrichment and analyzer execution
VirusTotal	File, hash, domain, IP, and URL reputation checks
URLScan	URL and web infrastructure analysis
Hybrid Analysis	Malware and sandbox enrichment
AbuseIPDB	IP reputation and abuse reporting checks
MITRE ATT&CK	Mapping adversary behavior to known techniques

Threat Intelligence Events Covered

The MISP workflow included multiple threat intelligence events, including:

1. Lazarus Group / AsyncRAT activity
2. MOVEit exploitation campaign
3. BlackCat ransomware activity
4. Redline Stealer activity

Each event included relevant IOCs, tags, threat context, and MITRE ATT&CK mapping.

Workflow Summary

The workflow followed these main steps:

Threat Scenario
      ↓
Create MISP Event
      ↓
Add IOCs and Attributes
      ↓
Apply Tags and Threat Context
      ↓
Map to MITRE ATT&CK
      ↓
Delegate Share / Publish Event
      ↓
Create TheHive Case
      ↓
Add Observables
      ↓
Run Cortex Analyzers
      ↓
Document Findings

MISP Event Creation

In MISP, threat events were created to organize intelligence related to specific campaigns or threat activity.

For each event, the following information was documented:

* Event title
* Threat actor or malware family
* Related campaign or incident
* Event distribution level
* Threat tags
* IOCs
* MITRE ATT&CK techniques
* Analysis status
* Publishing and sharing settings

Example event topics included:

* Lazarus Group using AsyncRAT
* MOVEit exploitation activity
* BlackCat ransomware indicators
* Redline Stealer infrastructure and indicators

IOC Types Documented

The events included different types of indicators, such as:

* Malicious IP addresses
* Domains
* URLs
* File hashes
* Malware names
* Email-related indicators
* Network indicators
* C2 infrastructure indicators

The full IOC list should be documented in:

IOC Documentation

MITRE ATT&CK Mapping

Threat activity was mapped to MITRE ATT&CK to explain attacker behavior in a structured way.

Examples of possible ATT&CK areas covered include:

* Initial Access
* Execution
* Persistence
* Defense Evasion
* Credential Access
* Command and Control
* Exfiltration
* Impact

The full mapping should be documented in:

MITRE ATT&CK Mapping

Tagging and Context

Tags were used in MISP to classify events and indicators. The tagging process helps improve searchability, sharing, and intelligence context.

Examples of tags used or applicable to this project:

* Threat actor tags
* Malware family tags
* Ransomware tags
* Campaign tags
* TLP tags
* Confidence level tags
* MITRE ATT&CK tags

Delegate Share and Publish

The project included practicing MISP sharing workflows, including Delegate Share and Publish.

This helped demonstrate how CTI teams can prepare intelligence for internal or external sharing while maintaining control over distribution and visibility.

TheHive Case Management

A case was created in TheHive to simulate an investigation workflow based on the threat intelligence collected.

The case included:

* Case title
* Description
* Severity
* Tags
* Observables
* Investigation tasks
* Enrichment results
* Analyst notes

Observables Added in TheHive

TheHive observables included indicators such as:

* IP addresses
* Domains
* URLs
* Hashes
* Malware-related artifacts

These observables were used for enrichment and investigation.

Cortex Analyzer Enrichment

Cortex analyzers were used to enrich observables and provide additional context.

Analyzers used included:

* VirusTotal
* URLScan
* Hybrid Analysis
* AbuseIPDB

The enrichment helped identify:

* Reputation status
* Related detections
* Malicious infrastructure
* Sandbox results
* Abuse reports
* Supporting evidence for investigation

Key Skills Demonstrated

This project demonstrates practical knowledge in:

* Cyber Threat Intelligence workflow
* IOC collection and documentation
* Threat intelligence platform usage
* MISP event creation
* TheHive case management
* Cortex analyzer enrichment
* MITRE ATT&CK mapping
* Threat actor and malware classification
* Intelligence sharing workflow
* Technical reporting

Screenshots

Screenshots should be added in the screenshots/ folder after removing or blurring sensitive information.

Suggested screenshots:

* MISP event overview
* MISP attributes / IOCs
* MISP tags
* MITRE ATT&CK mapping
* Delegate Share or Publish page
* TheHive case overview
* TheHive observables
* Cortex analyzer results

Important: Do not upload screenshots containing passwords, API keys, private URLs, internal IPs, usernames, tokens, or any sensitive information.

Files in This Project

misp-thehive-cortex-workflow/
│
├── README.md
├── iocs.md
├── mitre-attack-mapping.md
└── screenshots/

What I Learned

Through this project, I practiced how CTI teams structure, enrich, and share threat intelligence. I also learned how MISP, TheHive, and Cortex can work together to support intelligence-driven investigations, from IOC collection to case management and enrichment.

Disclaimer

This project is for educational and portfolio purposes only. All sensitive information, credentials, API keys, and private data must be removed before publishing.