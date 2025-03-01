<h1>🛡️ Assessing Common Attack Vectors</h1>

<h2>📌 Overview</h2>
This project examines **common attack vectors** through practical simulations of **injection attacks, malware execution, Distributed Denial-of-Service (DDoS) attacks, and social engineering**. The goal is to analyze attack methodologies, their impact on systems, and defensive strategies.

<h2>🛠 Tools & Technologies Used</h2>

- **Metasploit Framework** – Payload generation & malware execution  
- **SQL/XSS Injection Tools** – Web vulnerability exploitation  
- **Wireshark** – Traffic capture & DDoS attack analysis  
- **SET (Social Engineering Toolkit)** – Phishing attack simulation  

<h2>🔍 Key Findings & Attack Simulations</h2>

| Attack Type | Description | Exploitation & Observations |
|------------|-------------|-----------------------------|
| **Injection Attacks (SQL & XSS)** | Code execution via unsanitized input fields. | Successfully injected **DOM XSS and Reflected XSS** into a vulnerable web app. |
| **Malware Execution (Metasploit Payloads)** | Remote code execution via trojanized files. | Created and executed **malwarePayload.exe**, gaining system access. |
| **DDoS Attack** | Overwhelming a target server with traffic. | Recruited botnet hosts and simulated a **flood attack** causing service disruption. |
| **Social Engineering (Phishing Email)** | Deceiving users to obtain credentials. | Crafted and sent a **SET phishing email**, capturing login details. |

<h2>🚀 Report & Documentation</h2>

📄 **[Download Full Report (PDF)](https://github.com/user-attachments/files/18703978/Assessing.Common.Attack.Vectors.4e.-.Marc.Corona.pdf)**

<h2>✅ Defensive Measures & Mitigations</h2>

🔹 **Input Validation & Parameterized Queries** prevent SQL/XSS injection.  
🔹 **Endpoint Security & Regular Updates** protect against malware execution.  
🔹 **DDoS Mitigation (Rate Limiting, Firewalls)** reduces flood attack impact.  
🔹 **User Awareness & Email Filtering** help prevent social engineering attacks.  

---
