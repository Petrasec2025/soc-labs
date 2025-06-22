# Notes

## SOC Analyst Tier 1 Responsibilities
- Monitor network traffic & IDS alerts.
- Investigate low-level incidents.
- Escalate confirmed threats to Tier 2.

## Skills Required
- TCP/IP, OSI Model
- Windows Event Logs, Linux Syslogs
- Security+ knowledge base

---

# Lab Summary and Key Learnings

## Overview
This introductory lab simulates the day-to-day responsibilities of a Junior Security Analyst in a Tier 1 SOC.  
I learned how to triage alerts, analyze logs, use threat intelligence tools, and take initial incident response actions.

## Key Concepts Learned

### Junior SOC Analyst Responsibilities
- Triage and escalate alerts from IDS/IPS and SIEM platforms  
- Monitor suspicious activity and respond to alerts  
- Collaborate with Tier 2 and Tier 3 teams  
- Document incidents and manage tickets

### SOC Team Structure

| SOC Tier | Role Description                     |
|----------|------------------------------------|
| Tier 1   | Alert triage, ticket handling      |
| Tier 2   | Incident response, threat hunting  |
| Tier 3   | Malware analysis, deep forensics   |

### Core SOC Functions
- 24/7 Infrastructure Monitoring  
- Attack Detection & Containment  
- Threat Intelligence Integration  
- Escalation & Response Workflows

## Tools & Techniques Used

| Tool           | Purpose                              |
|----------------|------------------------------------|
| AbuseIPDB      | Check for blacklisted IP addresses |
| Cisco Talos    | Investigate IP reputation           |
| Firewall Tool  | Block suspicious IPs and update rules |
| SIEM/EDR       | Log review and alert handling (simulated) |

## Task Summary

### Task 1: Role of a Junior SOC Analyst
- Reviewed alert queues and logs  
- Performed basic triage and ticket updates  
- Practiced communication with senior SOC members

### Task 2: Understanding the SOC Environment
- Studied the SOC 3-tier operational model  
- Reviewed [CISA APT40 Threat Report](https://us-cert.cisa.gov/ncas/alerts/aa21-200a) to understand attacker TTPs

### Task 3: Static Site Lab – “A Day in the Life”

#### Objective
Simulate alert investigation and response actions.

#### Investigation Flow
1. Launched SOC Static Dashboard  
2. Analyzed alert categories and log entries  
3. Investigated suspicious IPs (`221.181.185.159` flagged as malicious)  
4. Reported incident to SOC Lead  
5. Blocked the IP in simulated firewall  

🏁 **Flag Captured:** `THM{UNTIL-WE-MEET-AGAIN}`
