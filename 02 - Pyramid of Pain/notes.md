# Pyramid of Pain: Key Concepts & Summary

## 1. Introduction
The **Pyramid of Pain** is a cybersecurity framework that ranks indicators based on how difficult they are for adversaries to change.  
Understanding this is essential for me as a Threat Hunter, Incident Responder, or SOC Analyst to build effective detection strategies.

---

## 2. Pyramid Levels (Bottom → Top)

| Level               | Difficulty | Description & Key Points                                   |
|---------------------|------------|------------------------------------------------------------|
| **Hash Values**      | Trivial    | Unique numeric identifiers of files (e.g., MD5, SHA-1, SHA-256). Easy to change but widely used to identify malware samples. Hash collisions exist, so they’re not fully secure. |
| **IP Addresses**     | Trivial    | Identify devices on a network. Easy to change (e.g., via Fast Flux networks). Blocking IPs is common but can be bypassed. |
| **Domain Names**     | Easy       | Domains map to IPs and are harder to change than IPs but still modifiable. Includes risks like Punycode attacks and URL shorteners used for phishing. |
| **Host Artifacts**   | Annoying   | File paths, registry keys on endpoints. More persistent than network indicators. |
| **Network Artifacts**| Annoying   | Command and Control (C2) traffic patterns and other network behaviors indicating compromise. |
| **Tools**            | Challenging| Custom malware, utilities, and backdoors attackers use. Replacing or changing these requires significant effort. |
| **TTPs**             | Tough      | Tactics, Techniques & Procedures — attacker behaviors and methods. Hardest to evade and most valuable for long-term defense. |

---

## 3. My Practical Notes on Key Levels

### Hash Values
- Common algorithms I learned about include:  
  - **MD5:** 128-bit, outdated and vulnerable to collisions.  
  - **SHA-1:** 160-bit, deprecated due to vulnerabilities.  
  - **SHA-2 (SHA-256):** 256-bit, currently the secure standard.  
- Hashes help me uniquely identify malware samples, but attackers can easily modify files to change the hash.

### IP Addresses & Fast Flux
- IP addresses can be blocked, but attackers often use **Fast Flux**, where many IPs rapidly rotate behind a domain to hide malicious activity.

### Domain Names & Punycode
- Domains are more persistent but still modifiable.
- **Punycode** lets attackers create visually similar domains for phishing.
- URL shorteners can mask malicious links, so I must analyze shortened URLs carefully.

### Tools & Malware
- Attackers invest time and money into custom tools.
- I can use antivirus signatures, YARA rules, and fuzzy hashing (e.g., SSDeep) to detect these tools.

### TTPs (Tactics, Techniques & Procedures)
- These represent attacker behaviors throughout an attack lifecycle, from phishing to data exfiltration.
- Detecting TTPs quickly lets me stop attacks early and forces adversaries to retreat or regroup.

---

## 4. Practical Exercise Summary
- I deployed a static site to classify indicators into the Pyramid tiers.
- I earned a flag by correctly completing the exercise.

---

## 5. Conclusion & Application
- The Pyramid of Pain helps me focus on indicators that are harder for attackers to change, creating stronger, long-lasting defenses.
- When researching APT groups or building detection rules, I ask myself:  
  - What detections can I build?  
  - Where do these fit on the Pyramid?  
  - How will this disrupt attacker operations?

---

### Resources & Tools I Use
- Malware lookup: VirusTotal, Metadefender Cloud (OPSWAT)  
- Threat feeds & hunting: MalwareBazaar, Malshare, SOC Prime Marketplace  
- Fuzzy hashing: [SSDeep](https://ssdeep-project.github.io/)

---

**I’m ready to explore deeper and build defenses that really hurt attackers!**
