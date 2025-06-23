# 🛠️ Practical Task: Unified Kill Chain Scenario Matching

---

## 🔍 Scenario Matching Table

| Scenario                                                                 | UKC Phase            |
|--------------------------------------------------------------------------|----------------------|
| Malware drops a scheduled task                                           | Persistence          |
| Lateral movement using PSExec                                            | Lateral Movement     |
| Data uploaded to Mega.io                                                 | Exfiltration         |
| Phishing email sent to employee                                          | Delivery             |
| Impersonating employee for password reset                                | Social Engineering   |
| Setup of a Command & Control server                                      | Weaponization        |
| Exploiting a vulnerable web application                                  | Exploitation         |
| Mimikatz used for credential dumping                                     | Credential Access    |
| Outbound spike to unknown IP                                             | Exfiltration         |
| Ransomware encrypts critical files                                       | Impact               |
| Sensitive client data leaked online                                     | Objectives / Impact  |

---

## 🎯 Final Flag

> ✅ **Flag:** `THM{UKC_SCENARIO}`

The flag was revealed after successfully matching each scenario to the correct Unified Kill Chain phase using the static site provided in the lab.

---

## 🧠 Takeaway

This scenario-matching challenge solidified my ability to:

- Analyze adversary tactics
- Map attack behavior to UKC
- Strengthen real-world threat detection and triage
