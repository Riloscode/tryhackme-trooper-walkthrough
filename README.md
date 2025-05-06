# 🕵️ TryHackMe: Trooper – SOC Level 1 Cyber Threat Intelligence Walkthrough

This project contains my analysis and investigative process for the [TryHackMe: Trooper](https://tryhackme.com/room/trooper) room. It simulates a real-world scenario where I acted as a Cyber Threat Intelligence (CTI) analyst to identify an advanced persistent threat (APT) using OpenCTI and the MITRE ATT&CK Navigator.

## 🧠 Room Summary

- **Platform**: TryHackMe  
- **Difficulty**: Easy  
- **Time Estimation**: 60 minutes  
- **Focus**: Cyber Threat Intelligence (CTI), MITRE ATT&CK, STIX IDs, Malware Analysis  
- **Tools Used**: OpenCTI, ATT&CK Navigator

## 🎯 Objective

Investigate an APT attack against a multinational company using threat intelligence platforms to answer questions related to:

- Phishing techniques
- Malware identifiers (STIX)
- MITRE techniques and tactics
- Threat actor identity and associated tools

## 🔧 Tools and Platforms

| Tool              | URL                          |
|-------------------|------------------------------|
| OpenCTI           | `http://10.10.248.114:8080`  |
| ATT&CK Navigator  | `http://10.10.248.114:4200`  |

## ✅ Key Findings

| Question                                              | Answer                                |
|-------------------------------------------------------|----------------------------------------|
| What kind of phishing campaign is used?              | `spear-phishing emails`               |
| Name of malware used by APT X                         | `USBferry`                             |
| STIX ID of malware                                    | `malware--5d0ea014-1ce9-5d5c-bcc7-f625a07907d0` |
| Initial Access technique using USB                    | `Replication Through Removable Media`            |
| Identity of APT X                                     | `Tropic Trooper`                       |
| Number of ATT&CK techniques linked to the APT         | `39`                                    |
| Name of tool used by the APT                          | `BITSAdmin`                              |
| Sub-technique used under Valid Accounts               | `Local Accounts`                       |
| Associated MITRE Tactics                              | `Persistence, Defense Evasion, Privilege Escalation` |
| Technique under Collection                            | `Screen Capture`                       |

## 📁 Project Structure

tryhackme-trooper-walkthrough/
├── README.md
├── walkthrough.md
├── images/
│ ├── opencti-dashboard.png
│ ├── attack-navigator.png
├── notes/
│ └── trooper-findings.txt

