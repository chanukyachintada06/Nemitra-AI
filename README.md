# 🛡️ Nemitra AI  
### *Your Visionary Friend That Sees Threats Before You Do.*

Nemitra AI is an **AI-powered cybersecurity MVP** built to detect phishing and malicious URLs using intelligent heuristic analysis and a simulated **Azure AI Security layer**. It provides users with **instant risk scoring, threat explanations, and scan history** in a clean, modern web interface.

This project was built as part of **Microsoft Imagine Cup 2026**.

---

## 🚀 Features

- 🔍 Real-time URL phishing detection  
- 🧠 Simulated Azure AI analysis layer  
- 📊 Risk score (0–100) with verdict:
  - SAFE
  - SUSPICIOUS
  - DANGEROUS
- 🧾 Detailed reasons for each detection  
- 🕓 Scan history stored locally  
- 🚨 Brand impersonation detection (Google, PayPal, Instagram, Banks, etc.)  
- 🏦 RBI `.bank.in` domain trust logic  
- 💡 Modern responsive UI  

---

## 🧠 How It Works (MVP Logic)

Nemitra AI analyzes URLs using:

- Suspicious keyword detection (login, verify, bonus, etc.)
- Brand impersonation detection
- Suspicious TLD checks (`.xyz`, `.click`, `.top`, etc.)
- IP address usage detection
- URL structure anomalies (`@`, double slashes, long URLs)
- Trusted domain & bank domain trust rules
- Simulated **Azure AI Security Model** layer (for demo & pitch)

> ⚠️ This is an MVP / prototype. In production, Azure OpenAI, Azure Functions, and Threat Intelligence APIs would be used.

---

## 🖥️ Tech Stack

- HTML  
- CSS  
- JavaScript  
- Azure AI (Simulated / Decoy for MVP)  
- LocalStorage (for scan history)

---

## 📸 UI

- Clean dashboard-style interface  
- Real-time scanning feedback  
- Risk meter & explanations  
- Recent scan history table  

---

## 🏗️ Project Structure
nemitra-ai/
 ├── nemitrai.html   (Main app file)
 └── README.md


---

## ▶️ How To Run

1. Download or clone this repository
2. Open `nemitrai.html` in any modern browser
3. Enter any URL and click **Scan Now**

---

## 🧪 Example Test URLs
- http://google.com@phish-site.xyz/login

- http://paypal-login-secure-account.xyz/verify

- http://192.168.1.1/bank/login

- https://www.sbi.co.in


---

## 🏆 Use Case

- Browser security extension (future)
- Email link scanning
- Enterprise security gateway
- Public phishing awareness tool

---

## 🔮 Future Roadmap

- 🔗 Real Azure OpenAI integration  
- 🖼️ Website screenshot analysis  
- 🌐 Domain reputation APIs  
- 🧩 Browser extension integration  
- 👤 User accounts & cloud history  
- 🏢 Enterprise dashboard  

---

## 👨‍💻 Built For

- Microsoft Imagine Cup 2026  
- Cybersecurity innovation  
- AI for social good  

---

## ⚠️ Disclaimer

This is a **prototype / MVP**. Do not rely on it as a sole security system in production.

---

## 📜 License

MIT License

Copyright (c) 2026 Nemitra AI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

> **Nemitra AI — Your Visionary Friend That Sees Threats Before You Do.**
