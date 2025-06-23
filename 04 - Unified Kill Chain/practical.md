# 🛠️ Practical Task: Unified Kill Chain Scenario Matching

As part of my Unified Kill Chain (UKC) training, I completed a hands-on scenario-matching exercise. The goal was to correctly align real-world attacker behaviors to the corresponding UKC phases using a static site provided in the lab.

This practical experience helped reinforce my understanding of how different attacker tactics fit into the broader chain of an intrusion campaign.

---

## 🔍 Scenario Matching Table

Here’s how I matched each attack behavior to its correct phase in the Unified Kill Chain:

| Scenario                                                            | UKC Phase            |
|---------------------------------------------------------------------|----------------------|
| Malware drops a scheduled task                                      | **Persistence**      |
| Lateral movement using PSExec                                       | **Lateral Movement** |
| Data uploaded to Mega.io                                            | **Exfiltration**     |
| Phishing email sent to employee                                     | **Delivery**         |
| Impersonating employee for password reset                           | **Social Engineering** |
| Setup of a Command & Control server                                 | **Weaponization**    |
| Exploiting a vulnerable web application                             | **Exploitation**     |
| Mimikatz used for credential dumping                                | **Credential Access**|
| Outbound spike to unknown IP                                        | **Exfiltration**     |
| Ransomware encrypts critical files                                  | **Impact**           |
| Sensitive client data leaked online                                 | **Objectives / Impact** |

This task gave me a practical framework for spotting and categorizing attacker techniques, which is crucial for SOC operations and defensive strategy.

---

## 🎯 Final Flag

After accurately completing the matching exercise, I was awarded the final flag:

> ✅ **Flag:** `THM{UKC_SCENARIO}`

---

## 🖼️ Proof of Completion

Below is the screenshot I captured after completing the challenge and revealing the flag:

![UKC Scenario Matching - Flag Screenshot](https://github.com/user-attachments/assets/35fb65b2-ffb1-4563-9931-5f3db46f2408)

---

## 🧠 My Takeaway

This scenario-matching task gave me real insight into how attacker behavior translates into the UKC model. It taught me to:

- Recognize attacker movements within real infrastructure
- Apply UKC knowledge to enhance detection in SIEMs and SOCs
- Develop better response logic tied to specific phases of an attack

This was a highly valuable exercise that connected theoretical models to realistic situations a key skill for any future cybersecurity professional like myself.
