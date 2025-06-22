# 🧠 Notes: SOC Analyst – Tier 1 (By Petras Guilherme Kulyumba)

---

## My Responsibilities as a Tier 1 SOC Analyst

As a Junior SOC Analyst, my responsibilities included:

- Monitoring network traffic and IDS/IPS alerts.
- Investigating low-level security incidents and performing triage.
- Escalating confirmed threats to Tier 2 analysts or Team Leads.
- Creating and managing incident tickets.
- Collaborating with other members of the SOC team during investigations.

---

## Skills I Applied and Developed

- Deepened my understanding of TCP/IP and OSI Models  
- Worked with Windows Event Logs and Linux Syslogs  
- Used multiple threat intelligence platforms to enrich alert data  
- Applied foundational knowledge from my CompTIA Security+ certification  
- Began developing scripting habits to support automation and investigation  

---

# 🔬 Lab Summary and Key Learnings

## Overview

In this lab, I simulated the real-world responsibilities of a Junior Security Analyst working in a Tier 1 Security Operations Center (SOC). I practiced triaging alerts, reviewing system logs, leveraging open-source threat intel tools, and taking basic response actions in a simulated environment.

---

## Key Concepts I Learned

### 👨‍💻 My Role in SOC

- Triaged and escalated alerts from IDS/IPS and SIEM systems  
- Monitored suspicious activity and performed investigations  
- Documented findings, managed tickets, and supported senior analysts  
- Learned how to assist with initial threat mitigation  

### 🏢 Understanding SOC Team Structure

| SOC Tier | Role Description                    |
|----------|-------------------------------------|
| Tier 1   | Alert triage, ticket handling       |
| Tier 2   | Incident response, threat hunting   |
| Tier 3   | Malware analysis, deep forensics    |

### 🧩 Core SOC Functions I Observed

- 24/7 monitoring of critical infrastructure  
- Threat detection, containment, and response  
- Integration of live threat intelligence  
- Escalation workflows for more complex incidents  

---

## 🛠️ Tools & Techniques I Used

| Tool                   | Purpose                                               |
|------------------------|--------------------------------------------------------|
| AbuseIPDB              | Verified and investigated suspicious IP addresses      |
| Cisco Talos            | Researched domain and IP reputations                   |
| IP Scanner (TryHackMe) | Confirmed IP threats in the lab simulation             |
| Firewall Tool          | Simulated blocking of malicious IPs                    |
| SIEM/EDR               | Analyzed logs and triaged alerts (simulated environment)|

---

## ✅ Task Summary

### Task 1: Junior SOC Analyst Role

- I reviewed IDS alerts and security logs  
- Performed basic triage, opened/closed tickets  
- Practiced communication and escalation within the SOC chain  

### Task 2: Understanding the SOC Framework

#### What I Learned About SOCs

A Security Operations Center (SOC) is a centralized team that monitors, detects, and responds to cyber threats 24/7. SOCs protect data, systems, and organizational integrity through active monitoring and fast response.

> According to McAfee, SOC teams implement the security framework and serve as the collaborative hub of all cyber defense efforts.

#### Prevention & Preparation Techniques I Practiced

- Followed threat intelligence feeds via CISA, Feedly, and Twitter  
- Explored TTPs (Tactics, Techniques, Procedures) from APT actors like APT40  
- Maintained simulated security infrastructure:
  - Patched vulnerabilities  
  - Updated detection signatures  
  - Blacklisted/whitelisted domains and IPs

📖 [CISA APT40 Threat Report](https://us-cert.cisa.gov/ncas/alerts/aa21-200a)

#### Monitoring & Investigating

- Used SIEM/EDR to track and investigate events  
- Prioritized alerts by severity (Critical to Low)  
- Performed structured triage asking:
  - How did the attack occur?  
  - When was it initiated?  
  - Why was this target chosen?

#### Responding to Incidents

- Practiced simulated incident response:
  - Isolating infected systems  
  - Terminating malicious processes  
  - Removing malicious files  
  - Reporting and documentation  

---

### Task 3: "A Day in the Life" – Static Site Lab

#### Objective

This task allowed me to simulate an alert investigation in a virtual SOC dashboard.

#### What I Did

1. Accessed the SOC static dashboard  
2. Analyzed alert categories and reviewed log data  
3. Investigated IP `221.181.185.159` flagged as malicious using open-source tools  
4. Used [TryHackMe IP Scanner](https://ip-scanner.thm) for deeper threat analysis  
5. Reported the incident to my simulated SOC Lead  
6. Blocked the IP using the simulated firewall tool

🏁 **Flag Captured:** `THM{UNTIL-WE-MEET-AGAIN}`

---

## 💼 A Day in My Life as a Junior SOC Analyst

Being on the front lines of cybersecurity means:

- Monitoring and analyzing live network alerts  
- Handling suspicious emails and log sources  
- Using threat intel tools to validate alerts  
- Taking quick response actions against potential threats

Each day offers new challenges—from identifying false positives to dealing with potentially compromised systems.

### Key Incident Response Questions I Ask

- Was there any data exfiltration?  
- Did lateral movement occur?  
- What were the attacker's goals?  
- How do we improve detection for next time?

---

## 🧗 My Career Path as I Progress in SOC

| Tier | Role                        | Responsibilities                                                |
|------|-----------------------------|-----------------------------------------------------------------|
| 1    | Junior Security Analyst     | Triaging, investigating basic threats, reporting                |
| 2    | SOC Analyst / Incident Responder | Threat hunting, complex incident response, remediation   |
| 3    | Threat Hunter / Forensics Expert | Malware analysis, adversary emulation, advanced forensics |

---

## Final Thoughts

This lab helped me develop practical experience in SOC operations and built my confidence to work in real-time alert environments. It confirmed my passion for cybersecurity and my goal to grow from Tier 1 to Tier 3 — and ultimately toward becoming a CISO.

> 🧠 I’m excited to continue my journey as a cybersecurity professional. This is just the beginning.

