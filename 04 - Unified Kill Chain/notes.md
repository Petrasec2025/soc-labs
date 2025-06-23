# 📘 My Notes: Unified Kill Chain

---

## 🔄 Overview of UKC Phases

The **Unified Kill Chain** breaks down modern cyberattacks into **18 phases**, grouped into **3 major stages**. As I studied the model, I found it incredibly useful in understanding how attackers progress from external reconnaissance all the way to achieving their final objectives inside a compromised network.

---

### 🔹 Initial Foothold

This stage shows how attackers gain access to the target environment:

- **Reconnaissance**: I learned that this phase involves collecting external info like exposed services or employee names. (TA0043)  
- **Weaponization**: Attackers build tools like malware, payloads, or C2 infrastructure. (TA0001)  
- **Delivery**: This is how payloads are sent — often via phishing emails, malicious links, or USB drops.  
- **Social Engineering**: A human-focused phase where attackers trick users into helping them.  
- **Exploitation**: Here, attackers exploit known vulnerabilities to execute code or gain access. (TA0002)  
- **Persistence**: After access is gained, attackers use tricks like scheduled tasks to maintain it. (TA0003)  
- **Defense Evasion**: Techniques like obfuscation, fileless malware, or encryption help attackers hide. (TA0005)  
- **Command & Control (C2)**: This phase allows attackers to remotely control compromised machines. (TA0011)  
- **Pivoting**: I found this phase crucial — attackers expand their access by jumping to other systems. (TA0008)

---

### 🔹 Network Propagation

Once inside, attackers spread through the network using these techniques:

- **Discovery**: They scan and map out the internal network to find targets. (TA0007)  
- **Privilege Escalation**: Gaining higher-level access (e.g., admin) to do more damage. (TA0004)  
- **Execution**: Running malicious code or commands after access is achieved. (TA0002)  
- **Credential Access**: Extracting credentials using tools like Mimikatz. (TA0006)  
- **Lateral Movement**: Using the newly gained credentials or tools like PSExec to access more systems. (TA0008)

---

### 🔹 Action on Objectives

This final stage is where attackers complete their mission:

- **Collection**: Sensitive files, passwords, screenshots, etc., are gathered. (TA0009)  
- **Exfiltration**: The collected data is sent out of the environment, often encrypted. (TA0010)  
- **Impact**: I saw this includes actions like ransomware deployment or wiping systems. (TA0040)  
- **Objectives**: Ultimately, it all leads to goals like extortion, data theft, disruption, or espionage.

---

## 🆚 UKC vs. Cyber Kill Chain (CKC)

While reviewing, I compared the **Unified Kill Chain (UKC)** to Lockheed Martin's **Cyber Kill Chain (CKC)**. Here's what stood out:

| Feature             | Unified Kill Chain (UKC) | Cyber Kill Chain (CKC) |
|---------------------|--------------------------|-------------------------|
| Release Year        | 2017 (updated 2022)      | ~2011                   |
| Phases              | 18                       | 7                       |
| Cloud Ready         | ✅ Yes                   | ❌ No                   |
| MITRE Integration   | ✅ Yes                   | ❌ No                   |
| APT Coverage        | ✅ Strong                | ❌ Limited              |

UKC is **modern**, **cloud-aware**, and **aligned with MITRE ATT&CK**, which makes it much more relevant for today’s attacks — especially APTs.

---

## 🛡️ My Takeaway

Studying the **Unified Kill Chain** gave me a much clearer understanding of how attackers operate and how each technique builds on the next. I can now:

- Visualize how attackers **chain multiple techniques** to compromise an organization
- Identify where a SOC should **monitor or detect** to break that chain
- Apply this model to improve **alert logic**, **threat hunting**, and **incident response**

This model has helped me think more like both an attacker and a defender — which is critical for anyone working in cybersecurity.
