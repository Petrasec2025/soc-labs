# 📘 My Notes: Unified Kill Chain

---

## 🔄 Overview of UKC Phases

The Unified Kill Chain has **18 total phases** grouped into **3 main stages**:

---

### 🔹 Initial Foothold

- **Reconnaissance**: External info gathering (TA0043)  
- **Weaponization**: Prepping malware or C2 infrastructure (TA0001)  
- **Delivery**: Sending payloads via phishing, etc.  
- **Social Engineering**: Manipulating users to act  
- **Exploitation**: Exploiting known system flaws (TA0002)  
- **Persistence**: Maintaining access (e.g., scheduled tasks) (TA0003)  
- **Defense Evasion**: Obfuscation to avoid detection (TA0005)  
- **Command & Control (C2)**: Establishing remote control (TA0011)  
- **Pivoting**: Expanding access within the environment (TA0008)

---

### 🔹 Network Propagation

- **Discovery**: Identifying network assets (TA0007)  
- **Privilege Escalation**: Gaining higher access (TA0004)  
- **Execution**: Running commands or malware (TA0002)  
- **Credential Access**: Extracting credentials (TA0006)  
- **Lateral Movement**: Spreading across systems (TA0008)

---

### 🔹 Action on Objectives

- **Collection**: Gathering sensitive data (TA0009)  
- **Exfiltration**: Sending data out (TA0010)  
- **Impact**: Damage like encryption or destruction (TA0040)  
- **Objectives**: Final goals – extortion, espionage, etc.

---

## 🆚 UKC vs. Cyber Kill Chain (CKC)

| Feature             | Unified Kill Chain (UKC) | Cyber Kill Chain (CKC) |
|---------------------|--------------------------|-------------------------|
| Release Year        | 2017 (update 2022)       | ~2011                   |
| Phases              | 18                       | 7                       |
| Cloud Ready         | ✅ Yes                   | ❌ No                   |
| MITRE Integration   | ✅ Yes                   | ❌ No                   |
| APT Coverage        | ✅ Strong                | ❌ Limited              |

---

## 🛡️ My Takeaway

The UKC model is more comprehensive and realistic for today’s threat landscape. I now better understand:

- How attackers chain techniques
- Where defenders must monitor
- How to organize detection logic in a SOC
