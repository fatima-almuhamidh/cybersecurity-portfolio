# Italy Cyber Attack – Network Forensics Analysis

## Overview
This project is a network forensics investigation of a cyber attack involving malicious Word documents, Pushdo, Ursnif, suspicious HTTP traffic, and command-and-control communication.

## Objective
The objective was to analyze a PCAP file, identify malicious activity, extract indicators of compromise, reconstruct the infection chain, and document evidence using Wireshark.

## Tools Used
- Wireshark
- PCAP analysis
- DNS analysis
- TLS SNI inspection
- HTTP stream analysis
- Export Objects
- Conversations and I/O Graphs

## Attack Summary
The attack started with a malicious Word document delivered through email. After user interaction, the infection chain led to malware execution, C2 communication, and suspicious outbound network activity.

## Malware and Threats Identified
- Pushdo
- Ursnif
- TA551 / Shathak-related activity

## Key Evidence
- Exported objects included suspicious files such as xmas.rar, k.avi, and Oh.avi.
- DNS traffic showed OpenDNS activity resolving the victim public IP.
- TLS Client Hello revealed SNI communication with a suspicious C2 domain.
- HTTP POST flood activity indicated Ursnif C2 behavior.
- SMTP stream analysis showed suspicious communication behavior.

## Skills Demonstrated
- Network forensics
- Wireshark investigation
- IOC extraction
- Infection chain reconstruction
- C2 traffic identification
- Evidence-based reporting

## Recommendations
- Block identified C2 domains and IPs.
- Monitor for suspicious HTTP POST traffic.
- Block suspicious file downloads from unknown hosts.
- Educate users about malicious Office documents.
- Implement email attachment sandboxing.