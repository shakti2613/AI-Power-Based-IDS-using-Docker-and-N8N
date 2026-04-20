# 🚀 AI Power-Based Intrusion Detection System (IDS)
### Using Docker & n8n with Explainable AI (XAI)

## 📌 Overview
This project presents an AI-powered Intrusion Detection System (IDS) designed to monitor network traffic in real time and detect malicious activities such as SQL Injection, Cross-Site Scripting (XSS), and Command Injection.

The system uses a rule-based detection mechanism enhanced with Explainable AI (XAI) to provide transparency in decision-making. Docker is used for containerization, and n8n is integrated for automated alert generation and response.

---

## 🎯 Features

- 🔍 Real-time Intrusion Detection  
- 🧠 Explainable AI (XAI) for attack analysis  
- ⚡ Automated Alerts using n8n  
- 📊 Real-time Dashboard Monitoring  
- 🐳 Docker-based Deployment  
- 🔗 Correlation Engine for risk analysis  
- 📝 Logging and Reporting System  

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Backend Framework:** Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **Real-time Communication:** Socket.IO  
- **Containerization:** Docker  
- **Automation Tool:** n8n  

---

## ⚙️ System Architecture

The system consists of multiple modules:

- Data Collection Module  
- Detection Module (Rule-based Engine)  
- XAI Module  
- Alert Module (n8n Integration)  
- Correlation Engine  
- Dashboard Module  

---

## 🔄 Workflow

1. Capture incoming HTTP request  
2. Analyze request data (headers, payload, user-agent)  
3. Match patterns for attack detection  
4. Classify request (Safe / Suspicious / Malicious)  
5. Generate XAI explanation  
6. Trigger alert via n8n  
7. Store logs and display on dashboard  




