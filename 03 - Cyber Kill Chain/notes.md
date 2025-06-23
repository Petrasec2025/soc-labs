# Cyber Kill Chain: 7 Phases (My Notes)
<img width="1146" alt="Screenshot 2025-06-22 at 4 54 41 AM" src="https://github.com/user-attachments/assets/f94c1c48-d4f3-4c8d-9e3c-4de8e8c2602d" />

1. **Reconnaissance**  
   I gathered information on potential targets using OSINT tools like LinkedIn, Hunter.io, and theHarvester. The goal in this phase is to identify weak points through email addresses, exposed infrastructure, or employee data.

2. **Weaponization**  
   I learned how attackers combine exploits with malware (e.g., macro payloads in documents) to create deliverable attacks. Some payloads are custom-built, while others are bought on the dark web.

3. **Delivery**  
   Common delivery methods I studied include phishing emails, malicious USB drops, and watering hole attacks. Each is used to deliver malware to the victim.

4. **Exploitation**  
   In this phase, attackers trigger malicious code. I practiced identifying phishing links, macro exploits, and zero-day vulnerabilities.

5. **Installation**  
   I explored persistence techniques like planting web shells, using Meterpreter, creating malicious Windows services, and modifying Registry Run keys.

6. **Command & Control (C2)**  
   I simulated how attackers use DNS tunneling, HTTP/S beaconing, and fallback C2 servers to maintain access and control over infected systems.

7. **Actions on Objectives**  
   Finally, I learned how attackers escalate privileges, exfiltrate data, delete backups, and execute final objectives.

---

## 💻 Tools & Techniques I Used

- **Recon Tools**: OSINT Framework, theHarvester, Hunter.io  
- **Payload Delivery**: PowerShell, VBA macros, Metasploit  
- **Persistence**: Web shell, Registry startup keys, Meterpreter  
- **C2 Channels**: DNS tunneling, HTTPS C2 beaconing  
- **Evasion**: Timestomping to hide files

---

## ⚠️ Kill Chain Limitations I Observed

- Doesn't detect **insider threats**
- Too focused on malware-based attacks
- Not updated since 2011
- Better when combined with **MITRE ATT&CK** or **Unified Kill Chain**

---

## 📌 Real-World Use Case: Target Breach

- **Initial Access**: Spearphishing via HVAC vendor  
- **Exploitation**: Credentials stolen  
- **Installation**: Malware deployed to POS systems  
- **C2**: Attackers maintained access  
- **Actions on Objectives**: 40M+ card records stolen
