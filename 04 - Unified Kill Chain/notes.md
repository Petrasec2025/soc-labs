# 📘 My Notes: Unified Kill Chain

A structured summary of my learning and reflections on the **Unified Kill Chain (UKC)** framework — a comprehensive model that maps out how modern cyberattacks are executed and how defenders can break the chain.

---

## 🔄 UKC Phase Overview

The **Unified Kill Chain** is divided into **3 main stages**, encompassing a total of **18 detailed phases**:

---

### 🔹 Stage 1: Initial Foothold

This stage shows how adversaries gain initial access to a target environment.

| Phase              | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Reconnaissance** | Gathering public information like IPs, domains, and employee data (https://attack.mitre.org/tactics/TA0043/) |
| **Weaponization**  | Creating malware, payloads, or C2 infrastructure (https://attack.mitre.org/tactics/TA0001/)                   |
| **Delivery**       | Sending payloads via phishing emails, USBs, etc.                            |
| **Social Engineering** | Tricking users into taking action (e.g., resetting a password) (https://attack.mitre.org/tactics/TA0001/)        |
| **Exploitation**   | Exploiting known vulnerabilities (https://attack.mitre.org/tactics/TA0002/)                                   |
| **Persistence**    | Maintaining access (e.g., scheduled tasks, backdoors) (https://attack.mitre.org/tactics/TA0003/)              |
| **Defense Evasion**| Hiding activities from security tools (https://attack.mitre.org/tactics/TA0005/)                              |
| **Command & Control (C2)** | Establishing remote control of systems (https://attack.mitre.org/tactics/TA0011/)                    |
| **Pivoting**       | Moving deeper into the network (https://attack.mitre.org/tactics/TA0008/)                                     |

---

### 🔹 Stage 2: Network Propagation

This phase covers how attackers spread across a compromised environment.

| Phase                | Description                                                              |
|----------------------|--------------------------------------------------------------------------|
| **Discovery**         | Scanning the internal network to locate assets (https://attack.mitre.org/tactics/TA0007/)                |
| **Privilege Escalation** | Gaining elevated access to carry out further attacks (https://attack.mitre.org/tactics/TA0004/)      |
| **Execution**         | Running malicious scripts or payloads (https://attack.mitre.org/tactics/TA0002/)                         |
| **Credential Access** | Extracting stored credentials (e.g., using Mimikatz) (https://attack.mitre.org/tactics/TA0006/)          |
| **Lateral Movement**  | Using credentials to spread across systems (https://attack.mitre.org/tactics/TA0008/)                    |

---

### 🔹 Stage 3: Action on Objectives

Attackers achieve their final goals and cause damage or extract value.

| Phase              | Description                                                             |
|--------------------|-------------------------------------------------------------------------|
| **Collection**      | Gathering sensitive data (files, screenshots, passwords) (TA0009)      |
| **Exfiltration**    | Transferring stolen data outside the network (TA0010)                  |
| **Impact**          | Disrupting systems (ransomware, wiping, data corruption) (TA0040)      |
| **Objectives**      | Final goals: extortion, espionage, sabotage, etc.                      |

---

## 🆚 UKC vs. Cyber Kill Chain (CKC)

Here's how **UKC** compares to the older **Cyber Kill Chain** by Lockheed Martin:

| Feature             | Unified Kill Chain (UKC) | Cyber Kill Chain (CKC) |
|---------------------|--------------------------|-------------------------|
| **Release Year**    | 2017 (updated 2022)      | ~2011                   |
| **Number of Phases**| 18                       | 7                       |
| **Cloud Ready**     | ✅ Yes                   | ❌ No                   |
| **MITRE ATT&CK Alignment** | ✅ Yes            | ❌ No                   |
| **APT Coverage**    | ✅ Strong                | ❌ Limited              |

➡️ **Why I prefer UKC**: It’s modern, integrated with MITRE, and tailored for today’s hybrid networks and APT behavior.

---

## 🧠 My Key Takeaways

Studying the **Unified Kill Chain** gave me strong insight into both the attacker's strategy and the defender’s opportunity to respond.

### 🧩 What I Learned:

- **How attackers chain techniques** across multiple stages to reach their objectives
- **Where defenders can break the chain** through detection or response
- **How to use the UKC structure** to organize threat intel, SIEM logic, and alert rules in a real SOC environment

This model helps me think more like both an **ethical hacker** and a **cyber defender** — a perspective that will strengthen my future in cybersecurity.

---

📂 *File Created by:* `Petras Guilherme Kulyumba`  
🔐 *Learning Path:* Ethical Hacking + Cyber Resilience  
🛡️ *Tools Used:* MITRE ATT&CK, TryHackMe Labs, Mimikatz, Splunk, Wireshark  
📅 *Date:* June 2025  
