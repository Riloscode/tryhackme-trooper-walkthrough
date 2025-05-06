# 📝 Notes – TryHackMe: Trooper (SOC Level 1 CTI)

This file documents key findings and progress while completing the **TryHackMe: Trooper** room, focused on Cyber Threat Intelligence (CTI) analysis using **OpenCTI** and the **MITRE ATT&CK Navigator**.

---

## 🕵️ Scenario Overview

A multinational tech company experienced cyber attacks, leading to data theft and operational disruptions. As a CTI analyst, my task was to use OpenCTI and the ATT&CK Navigator to investigate and identify:

- Threat actor identity
- TTPs (Tactics, Techniques, and Procedures)
- Malware and tools used
- Associated MITRE techniques and tactics

---

## 🔧 Tools Used

| Tool              | URL                                |
|------------------|-------------------------------------|
| OpenCTI          | `http://10.10.248.114:8080`         |
| ATT&CK Navigator | `http://10.10.248.114:4200`         |

---

## 🧠 Questions & Answers

| Question                                                                 | Answer                                         |
|--------------------------------------------------------------------------|-----------------------------------------------|
| What kind of phishing campaign does APT X use?                          | spear-phishing emails                         |
| What is the name of the malware used by APT X?                          | USBferry                                      |
| What is the malware’s STIX ID?                                          | malware--5d0ea014-1ce9-5d5c-bcc7-f625a07907d0 |
| What technique was used via USB for initial access?                     | Replication through removable media           |
| What is the identity of APT X?                                          | Tropic Trooper                                |
| How many attack pattern techniques are associated with the APT?         | 39                                            |
| What is the name of the tool linked to the APT?                         | BITSAdmin                                     |
| Sub-technique used under “Valid Accounts”?                              | Local Accounts                                |
| Tactics linked to the above technique?                                  | Initial Access, Persistence, Defense Evasion, Privilege Escalation |
| Technique used under the “Collection” tactic?                           | Automated Collection                          |

---

## 📌 Observations

- **APT X** (Tropic Trooper) is a known threat actor that targets organizations using USB-based infection vectors.
- **USBferry**, the identified malware, leverages removable media execution and lateral movement.
- **OpenCTI** provided direct STIX objects for identifying attack patterns, malware, and related tools.
- **ATT&CK Navigator** helped map tactics to techniques, offering visual validation.

---

## 🧠 Key Learnings

- Hands-on usage of CTI tools to track real-world APT behavior.
- Practical understanding of STIX IDs and their application in threat tracking.
- Reinforcement of MITRE ATT&CK techniques and how to categorize threats accurately.

---

> 🛡️ *This exercise simulates real-world threat analysis, emphasizing structured intelligence gathering and adversary behavior mapping.*
