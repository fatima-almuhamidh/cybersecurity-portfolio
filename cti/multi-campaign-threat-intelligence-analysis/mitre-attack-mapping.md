MITRE ATT&CK Mapping

Overview

This document maps observed threat behaviors to the MITRE ATT&CK framework to provide structured context around adversary tactics and techniques.

⸻

Lazarus / AsyncRAT

Tactic	Technique	ATT&CK ID
Initial Access	Phishing	T1566
Execution	Command and Scripting Interpreter	T1059
Persistence	Registry Run Keys / Startup Folder	T1547.001
Defense Evasion	Obfuscated Files or Information	T1027
Command and Control	Application Layer Protocol	T1071

⸻

MOVEit Exploitation

Tactic	Technique	ATT&CK ID
Initial Access	Exploit Public-Facing Application	T1190
Execution	Exploitation for Client Execution	T1203
Discovery	System Information Discovery	T1082
Collection	Data from Local System	T1005
Exfiltration	Exfiltration Over Web Services	T1567

⸻

BlackCat (ALPHV)

Tactic	Technique	ATT&CK ID
Initial Access	Valid Accounts	T1078
Discovery	Network Service Scanning	T1046
Lateral Movement	Remote Services	T1021
Impact	Data Encrypted for Impact	T1486
Defense Evasion	Indicator Removal on Host	T1070

⸻

RedLine Stealer

Tactic	Technique	ATT&CK ID
Execution	User Execution	T1204
Credential Access	Credentials from Password Stores	T1555
Collection	Archive Collected Data	T1560
Command and Control	Web Protocols	T1071.001
Exfiltration	Exfiltration Over C2 Channel	T1041

⸻

Why MITRE Mapping Matters

MITRE ATT&CK mapping helps analysts:

* Understand attacker behavior.
* Standardize threat reporting.
* Improve detection engineering.
* Identify defensive gaps.
* Communicate findings effectively across teams.

⸻

Disclaimer

The mappings in this document are based on the scenarios used during the practical exercise and are intended for educational and portfolio purposes.