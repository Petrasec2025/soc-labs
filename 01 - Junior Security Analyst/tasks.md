# 🧪 Practical Task – Analyze a Suspicious IP

## 🎯 Task Description
In this task, I analyzed alerts triggered in a Security Information and Event Management (SIEM) tool, identified a suspicious IP address, verified it through threat intelligence platforms, escalated the event to the security team, and blocked the IP via a firewall rule.

---

## 🔎 Investigation Steps

### Step 1: Accessed the Static Site Lab
I began by clicking the **"View Site"** button in the TryHackMe room, which opened the Static Site Lab. I navigated to the **Security Monitoring Tool** on the right panel to review recent alerts.

### Step 2: Investigated IP Addresses
From the logs, I noted a list of IP addresses. I used the following threat intelligence platforms to analyze them:

- 🌐 [AbuseIPDB](https://abuseipdb.com)
- 🌐 [Cisco Talos Intelligence](https://talosintelligence.com)

---

## ✅ Malicious IP Details

After reviewing all suspicious addresses, I confirmed that the following IP was malicious:

- **IP Address**: `221.181.185.159`
- **Threat Level**: 100% Malicious
- **ISP**: China Mobile Communication Operations
- **Domain Name**: `chinamobileleted.thm`
- **Location**: Zhenjiang, Jiangsu, China

<img width="1440" alt="Screenshot 2025-06-23 at 4 11 45 AM" src="https://github.com/user-attachments/assets/a8fd2064-e539-435e-bd13-0c67d1554962" />


---

## 🚨 Response Actions

### Step 1: Escalated the Event
I escalated the incident to **Will Griffin**, the designated security analyst, providing all gathered information about the malicious IP.

### Step 2: Firewall Blocking
Following the escalation, I created a firewall rule to block the IP address `221.181.185.159`, preventing further malicious activity.

<img width="725" alt="Screenshot 2025-06-23 at 4 14 05 AM" src="https://github.com/user-attachments/assets/c5c0521d-1364-4774-bca9-a8c5dcdbd7c5" />


---

## 🏁 Final Outcome

### 💬 Message from the Attacker
After blocking the IP, I received the following message left by the malicious actor:
<img width="1440" alt="Screenshot 2025-06-23 at 4 14 32 AM" src="https://github.com/user-attachments/assets/350ac1ad-9d6b-4e46-ab54-bb993f58e452" />

