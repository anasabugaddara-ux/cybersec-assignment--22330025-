1-Assignment Summary: 
Overview: This assignment involved a comprehensive static and dynamic analysis of a real-world malware sample to assess practical cybersecurity skills in malware identification, behavioral monitoring, and network traffic investigation. 

Scope: The project was divided into three core phases: Static Analysis (file identification and string extraction), Dynamic Analysis (execution in an isolated FLARE-VM environment with behavioral monitoring), and Traffic Analysis (identifying network anomalies and writing IDS rules). 

Tools Used: The analysis utilized professional security tools including Wireshark for packet capture, Strings and FLOSS for code inspection, Process Monitor (Procmon) for system event logging, and ProcDOT for visual behavioral correlation.

2- Malware Information:

Sample Name: WannaCry (WanaCrypt0r 2.0).

File Name: Malware.exe

File Size: 3.35 MB (3,514,368 bytes). 

MD5 Hash: 84c82835a5d21bbcf75a61706d8ab549.

SHA-256 Hash: ed01ebfbc9eb5bbea545af4d01bf5f1071661840480439c6e5babe8e080e41aa. Threat Category: Ransomware.

Key Indicators: The sample contains references to .wnry file extensions, multiple localized ransom messages (e.g., msg/m_english.wnry), and hardcoded Bitcoin addresses for payment.
