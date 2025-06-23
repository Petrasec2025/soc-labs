# 📘 My Notes: Unified Kill Chain

This is my structured summary and reflection on the **Unified Kill Chain (UKC)** — a modern framework that breaks down how attackers operate across 18 distinct phases. Studying UKC gave me a clearer picture of how real-world cyberattacks unfold and where defenders like me can step in to break the chain.

---

## 🔄 Phase Overview

The **Unified Kill Chain** is grouped into **3 main stages**, totaling **18 phases**. Each phase reflects a tactic an attacker may use during an intrusion campaign.

---

### 🔹 Stage 1: Initial Foothold

This is where attackers gain access to the environment.

| Phase | Description |
|-------|-------------|
| [**Reconnaissance**](https://attack.mitre.org/tactics/TA0043/) | I learned this is the research phase, where attackers gather information like IPs, domains, and user data. |
| [**Weaponization**](https://attack.mitre.org/tactics/TA0001/) | In this phase, malware or backdoors are created to exploit the target. |
| **Delivery** | Payloads are sent through phishing emails, malicious links, or USBs. |
| [**Social Engineering**](https://attack.mitre.org/tactics/TA0001/) | This involves tricking users — like impersonating IT staff to reset a password. |
| [**Exploitation**](https://attack.mitre.org/tactics/TA0002/) | Vulnerabilities are exploited to gain execution or access. |
| [**Persistence**](https://attack.mitre.org/tactics/TA0003/) | Attackers maintain access using scheduled tasks or registry changes. |
| [**Defense Evasion**](https://attack.mitre.org/tactics/TA0005/) | Techniques like fileless malware or obfuscation are used to avoid detection. |
| [**Command & Control (C2)**](https://attack.mitre.org/tactics/TA0011/) | This phase establishes remote access for attacker control. |
| [**Pivoting**](https://attack.mitre.org/tactics/TA0008/) | Attackers move laterally within the network to expand their reach. |

---

### 🔹 Stage 2: Network Propagation

This is where the attacker escalates access and spreads across systems.

| Phase | Description |
|-------|-------------|
| [**Discovery**](https://attack.mitre.org/tactics/TA0007/) | Attackers identify internal assets and gather system info. |
| [**Privilege Escalation**](https://attack.mitre.org/tactics/TA0004/) | They try to obtain admin or SYSTEM-level access. |
| [**Execution**](https://attack.mitre.org/tactics/TA0002/) | Malicious code is executed to maintain control or pivot. |
| [**Credential Access**](https://attack.mitre.org/tactics/TA0006/) | Tools like Mimikatz are used to dump passwords and hashes. |
| [**Lateral Movement**](https://attack.mitre.org/tactics/TA0008/) | Attackers move to other systems using stolen credentials or exploits. |

---

### 🔹 Stage 3: Action on Objectives

Here, attackers carry out their mission, whether theft, destruction, or disruption.

| Phase | Description |
|-------|-------------|
| [**Collection**](https://attack.mitre.org/tactics/TA0009/) | Data like documents, screenshots, and credentials are gathered. |
| [**Exfiltration**](https://attack.mitre.org/tactics/TA0010/) | The data is sent outside the network — often to encrypted cloud drives or remote servers. |
| [**Impact**](https://attack.mitre.org/tactics/TA0040/) | Systems are damaged or disrupted — e.g., ransomware or wipers. |
| **Objectives** | Final attacker goals like espionage, data theft, extortion, or system sabotage are achieved. |

---

## 🆚 UKC vs. Cyber Kill Chain (CKC)

As I compared the UKC to the **Cyber Kill Chain (CKC)** by Lockheed Martin, I realized how much more modern and complete the UKC really is.

| Feature | Unified Kill Chain (UKC) | Cyber Kill Chain (CKC) |
|---------|--------------------------|-------------------------|
| **Release Year** | 2017 (Updated 2022) | ~2011 |
| **Total Phases** | 18 | 7 |
| **Cloud Ready** | ✅ Yes | ❌ No |
| **MITRE ATT&CK Integration** | ✅ Yes | ❌ No |
| **APT Coverage** | ✅ Strong | ❌ Limited |

> 🔍 **Why I prefer UKC**: It’s cloud-aware, aligned with the MITRE ATT&CK framework, and it covers everything from human error to technical exploitation — making it more realistic for today’s threats.

---

## 🧠 My Key Takeaways

Learning about the Unified Kill Chain helped me think like both an **attacker** and a **defender**.

### ✨ What I Learned:

- 🔗 How attackers **chain techniques** across stages for maximum impact  
- 🚨 Where SOC teams can **intervene to disrupt** an attack early  
- 🛠️ How to use UKC phases to build better **alert rules**, **incident playbooks**, and **threat hunts**  

This model will guide me in building more effective cybersecurity solutions and sharpen my thinking in ethical hacking, SOC analysis, and threat detection.

---

📂 *Created by:* **Petras Guilherme Kulyumba**  
📚 *Learning Track:* Ethical Hacking & Cyber Resilience  
🧰 *Tools Referenced:* MITRE ATT&CK, TryHackMe, Mimikatz, Wireshark, Splunk  
📅 *Date:* June 2025  
