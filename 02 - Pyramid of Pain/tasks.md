# Practical Tasks – Lab 02: Pyramid of Pain

> ✅ Room: [Pyramid of Pain](https://tryhackme.com/room/pyramidofpain)  
> 👤 Completed by: [Petras20 on TryHackMe](https://tryhackme.com/p/Petras20)

---

## 🔹 Task 2 – Hash Values (Trivial)

**Exercise 1:**  
🔍 Analyze the report associated with the hash `b8ef959a9176aef07fdca8705254a163b50b49a17217a4ff0107487f59d4a35d`.  
📄 **Filename of the sample:** `Sales_Receipt 5606.xls`
<img width="1439" alt="Screenshot 2025-06-22 at 1 10 06 AM" src="https://github.com/user-attachments/assets/cef1b21f-33fe-4a49-8b09-bbfe85b90b7f" />
<img width="1407" alt="Screenshot 2025-06-22 at 1 13 24 AM" src="https://github.com/user-attachments/assets/a1122b17-0b6c-4538-a9ec-2295ebec3ed9" />



---

## 🔹 Task 3 – IP Address (Easy)

**Exercise 1:**  
💻 What is the first IP address the malicious process (PID 1632) attempts to communicate with?  
✅ **Answer:** `50.87.136.52`
<img width="1289" alt="Screenshot 2025-06-22 at 1 35 05 AM" src="https://github.com/user-attachments/assets/784b67de-d030-4dcc-8791-69970ccdc431" />


**Exercise 2:**  
🌐 What is the first domain name the malicious process (PID 1632) attempts to communicate with?  
✅ **Answer:** `craftingalegacy.com`
<img width="870" alt="Screenshot 2025-06-22 at 1 32 44 AM" src="https://github.com/user-attachments/assets/205ba1f8-7848-417b-969c-6f39d9077e7d" />
<img width="1440" alt="Screenshot 2025-06-22 at 1 37 42 AM" src="https://github.com/user-attachments/assets/471a6497-8128-40e0-a1a1-32347717c075" />


---

## 🔹 Task 4 – Domain Names (Simple)

**Exercise 1:**  
🚩 First suspicious domain request in the report on app.any.run  
✅ **Answer:** `craftingalegacy.com`
<img width="1440" alt="Screenshot 2025-06-22 at 1 49 21 AM" src="https://github.com/user-attachments/assets/ceeb1827-2360-41c4-866f-99f57ae6a105" />


**Exercise 2:**  
❓ What term refers to an address used to access websites?  
✅ **Answer:** *Domain name*
<img width="1440" alt="Screenshot 2025-06-22 at 1 49 21 AM" src="https://github.com/user-attachments/assets/64e91389-85ba-40c7-84ef-ce82acd2f9f6" />

**Exercise 3:**  
🧠 What type of attack uses Unicode characters in the domain name to imitate a known domain?  
✅ **Answer:** *Punycode attack*
**Exercise 4:**  
🔁 Redirected website from the shortened URL using a preview: `https://tinyurl.com/bw7t8p4u+`  
✅ **Answer:** `https://tryhackme.com/`
<img width="1403" alt="Screenshot 2025-06-22 at 2 06 59 AM" src="https://github.com/user-attachments/assets/cbcad94e-5109-4c51-8a00-f6dbaa0fa3c0" />
<img width="1376" alt="Screenshot 2025-06-22 at 2 08 09 AM" src="https://github.com/user-attachments/assets/10ae5d87-5fa4-49c4-97b7-6bf6728aeadb" />



---

## 🔹 Task 5 – Host Artifacts (Annoying)

**Exercise 1:**  
📡 What IP address does `regidle.exe` send a POST request to on port 8080?  
✅ **Answer:** `96.126.101.6`
<img width="1440" alt="Screenshot 2025-06-22 at 2 22 38 AM" src="https://github.com/user-attachments/assets/07d8baee-4d5d-4c50-ab0f-9bb20b3c78ae" />

**Exercise 2:**  
🧪 What is the name of the dropped malicious executable?  
✅ **Answer:** `G_jugk.exe`
<img width="1436" alt="Screenshot 2025-06-22 at 2 28 26 AM" src="https://github.com/user-attachments/assets/22aed358-f790-4f0e-99c5-9a9da65e7c28" />

**Exercise 3:**  
🛡️ How many vendors determined the host to be malicious on VirusTotal?  
✅ **Answer:** `9`
<img width="1439" alt="Screenshot 2025-06-22 at 2 32 17 AM" src="https://github.com/user-attachments/assets/0227469a-2fa4-4746-b0c2-f755c2ddb437" />


<img width="1413" alt="Screenshot 2025-06-22 at 2 32 27 AM" src="https://github.com/user-attachments/assets/97a07f21-6b68-4274-b3ba-eb92ef1c4403" />

---

## 🔹 Task 6 – Network Artifacts (Annoying)

**Exercise 1:**  
🌐 What browser uses the User-Agent string shown in the screenshot?  
✅ **Answer:** *Internet Explorer*

**Exercise 2:**  
📥 How many POST requests are in the PCAP screenshot?  
✅ **Answer:** `6`
<img width="1371" alt="Screenshot 2025-06-22 at 2 51 53 AM" src="https://github.com/user-attachments/assets/335b3b63-6a22-44e7-b53e-4a7ac58c9a6e" />

---

## 🔹 Task 7 – Tools (Challenging)

**Exercise 1:**  
🧮 What method is used to determine similarity between files?  
✅ **Answer:** *Fuzzy Hashing*

**Exercise 2:**  
🧾 What is the full name (not abbreviation) of fuzzy hashes?  
✅ **Answer:** *Context Triggered Piecewise Hashes*
<img width="1414" alt="Screenshot 2025-06-22 at 3 09 17 AM" src="https://github.com/user-attachments/assets/2b3f8bf2-8f26-4628-934c-2d7225cfe1bf" />


---

## 🔹 Task 8 – TTPs (Tough)

**Exercise 1:**  
📊 How many techniques fall under the Exfiltration category in the MITRE ATT&CK Matrix?  
✅ **Answer:** `9`

**Exercise 2:**  
🕵️ What is the name of the commercial remote access tool used by the Chimera group?  
✅ **Answer:** *Cobalt Strike*
<img width="1435" alt="Screenshot 2025-06-22 at 3 30 07 AM" src="https://github.com/user-attachments/assets/e44afbde-8d4a-4236-90ea-1054d2bda425" />


---

## 🔹 Task 9 – Practical: The Pyramid of Pain

**Exercise:**  
🧩 Deployed the static site and classified prompts correctly into Pyramid of Pain tiers.

✅ **Final Flag:**  
`THM{PYRAMIDS_COMPLETE}`
<img width="1438" alt="Screenshot 2025-06-22 at 3 32 24 AM" src="https://github.com/user-attachments/assets/4b344c66-69d4-4bf6-a87a-ac2ba7390325" />
<img width="682" alt="Screenshot 2025-06-22 at 3 49 01 AM" src="https://github.com/user-attachments/assets/c1ef5026-1994-4411-9a2f-b82adc5c9555" />
<img width="1433" alt="Screenshot 2025-06-22 at 3 48 41 AM" src="https://github.com/user-attachments/assets/9c29ad79-a132-44f5-bbc0-49dd8feb9a46" />
<img width="1437" alt="Screenshot 2025-06-22 at 4 03 04 AM" src="https://github.com/user-attachments/assets/e9d14c54-9f1a-41e7-957e-0cb6200e4988" />

---
