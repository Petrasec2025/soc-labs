# 🧪 Practical Tasks – Lab 02: Pyramid of Pain

> ✅ Room: [Pyramid of Pain](https://tryhackme.com/room/pyramidofpain)  
> 👤 Completed by: [Petras20 on TryHackMe](https://tryhackme.com/p/Petras20)

---

## 🔹 Task 2 – Hash Values (Trivial)

**Exercise 1:**  
I analyzed the report associated with the hash `b8ef959a9176aef07fdca8705254a163b50b49a17217a4ff0107487f59d4a35d`.  
**📝 Filename of the sample:** `Sales_Receipt 5606.xls`

![Hash Report Screenshot 1](https://github.com/user-attachments/assets/cef1b21f-33fe-4a49-8b09-bbfe85b90b7f)
![Hash Report Screenshot 2](https://github.com/user-attachments/assets/a1122b17-0b6c-4538-a9ec-2295ebec3ed9)

---

## 🔹 Task 3 – IP Address (Easy)

**Exercise 1:**  
The first IP address that the malicious process (PID 1632) attempted to communicate with was:  
✅ `50.87.136.52`

![IP Address Screenshot](https://github.com/user-attachments/assets/784b67de-d030-4dcc-8791-69970ccdc431)

**Exercise 2:**  
The first domain name that PID 1632 tried to communicate with was:  
✅ `craftingalegacy.com`

![Domain Report Screenshot 1](https://github.com/user-attachments/assets/205ba1f8-7848-417b-969c-6f39d9077e7d)  
![Domain Report Screenshot 2](https://github.com/user-attachments/assets/471a6497-8128-40e0-a1a1-32347717c075)

---

## 🔹 Task 4 – Domain Names (Simple)

**Exercise 1:**  
In the report on app.any.run, the first suspicious domain request I saw was:  
✅ `craftingalegacy.com`

![Domain Detection Screenshot](https://github.com/user-attachments/assets/ceeb1827-2360-41c4-866f-99f57ae6a105)

**Exercise 2:**  
The term that refers to an address used to access websites is:  
✅ *Domain name*

![Question Screenshot](https://github.com/user-attachments/assets/64e91389-85ba-40c7-84ef-ce82acd2f9f6)

**Exercise 3:**  
The type of attack that uses Unicode to imitate a known domain is called:  
✅ *Punycode attack*

**Exercise 4:**  
I previewed the shortened URL `https://tinyurl.com/bw7t8p4u+`, and it redirected to:  
✅ `https://tryhackme.com/`

![URL Redirect Screenshot 1](https://github.com/user-attachments/assets/cbcad94e-5109-4c51-8a00-f6dbaa0fa3c0)  
![URL Redirect Screenshot 2](https://github.com/user-attachments/assets/10ae5d87-5fa4-49c4-97b7-6bf6728aeadb)

---

## 🔹 Task 5 – Host Artifacts (Annoying)

**Exercise 1:**  
I found that `regidle.exe` made a POST request to an IP address in the US on port 8080:  
✅ `96.126.101.6`

![Regidle POST Screenshot](https://github.com/user-attachments/assets/07d8baee-4d5d-4c50-ab0f-9bb20b3c78ae)

**Exercise 2:**  
The malicious executable dropped was:  
✅ `G_jugk.exe`

![Executable Drop Screenshot](https://github.com/user-attachments/assets/22aed358-f790-4f0e-99c5-9a9da65e7c28)

**Exercise 3:**  
According to VirusTotal, the number of vendors that marked the host as malicious was:  
✅ `9`

![VirusTotal Screenshot 1](https://github.com/user-attachments/assets/0227469a-2fa4-4746-b0c2-f755c2ddb437)  
![VirusTotal Screenshot 2](https://github.com/user-attachments/assets/97a07f21-6b68-4274-b3ba-eb92ef1c4403)

---

## 🔹 Task 6 – Network Artifacts (Annoying)

**Exercise 1:**  
The browser identified from the User-Agent string was:  
✅ *Internet Explorer*

**Exercise 2:**  
I counted the POST requests in the PCAP screenshot and found:  
✅ `6`

![PCAP Screenshot](https://github.com/user-attachments/assets/335b3b63-6a22-44e7-b53e-4a7ac58c9a6e)

---

## 🔹 Task 7 – Tools (Challenging)

**Exercise 1:**  
The method used to determine similarity between files was:  
✅ *Fuzzy Hashing*

**Exercise 2:**  
The full name (not abbreviated) of fuzzy hashes is:  
✅ *Context Triggered Piecewise Hashes*

![Fuzzy Hash Screenshot](https://github.com/user-attachments/assets/2b3f8bf2-8f26-4628-934c-2d7225cfe1bf)

---

## 🔹 Task 8 – TTPs (Tough)

**Exercise 1:**  
I navigated to the ATT&CK Matrix and found that the number of techniques under the Exfiltration category is:  
✅ `9`

**Exercise 2:**  
The commercial remote access tool used by the Chimera APT group is:  
✅ *Cobalt Strike*

![MITRE ATT&CK Screenshot](https://github.com/user-attachments/assets/e44afbde-8d4a-4236-90ea-1054d2bda425)

---

## 🔹 Task 9 – Practical: The Pyramid of Pain

I deployed the static site and correctly categorized the given prompts into their respective Pyramid of Pain tiers.

✅ **Final Flag:**  
`THM{PYRAMIDS_COMPLETE}`

![Pyramid Flag Screenshot 1](https://github.com/user-attachments/assets/4b344c66-69d4-4bf6-a87a-ac2ba7390325)  
![Pyramid Flag Screenshot 2](https://github.com/user-attachments/assets/c1ef5026-1994-4411-9a2f-b82adc5c9555)  
![Pyramid Flag Screenshot 3](https://github.com/user-attachments/assets/9c29ad79-a132-44f5-bbc0-49dd8feb9a46)  
![Pyramid Flag Screenshot 4](https://github.com/user-attachments/assets/e9d14c54-9f1a-41e7-957e-0cb6200e4988)

---
