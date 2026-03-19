# 🛡️ ShadowSentinel AI – Real-Time Cybersecurity Bot

**ShadowSentinel AI** is an advanced, AI-powered cybersecurity system built on top of Wazuh that:
- Monitors logs in real-time
- Detects brute-force and suspicious activity
- Automatically blocks malicious IPs
- Generates daily reports
- Speaks alerts via voice assistant (Hazel)
- Supports face unlock & wake word detection
- Tracks system usage & suspicious behavior

> Built with ❤️ for modern Blue Teamers & SOC Analysts.

---

## 🚀 Key Features

- 🔍 Real-Time Log Monitoring (via Wazuh)
- 🧠 Brute-Force Detection & IP Auto-Blocking (iptables)
- 🔊 Voice Alert System (Hazel Assistant)
- 🧏‍♀️ “Hey Shadow” Wake Word Activation
- 🧑‍💻 Face Recognition Login
- 📨 Email Alerting System
- 📊 Daily Threat Reports
- 🎥 Suspicious Screen Recording & Stealth Mode
- 🧠 LLM-Based Threat Summarizer (LangChain, OpenRouter)
- 🔒 Vault Mode with Face Unlock
- ☁️ Cloud-Ready (with sync support)

---

## 📁 Project Structure

ShadowSentinel-AI/
│
├── modules/
│ ├── brute_force_blocker.py
│ ├── realtime_monitor.py
│ ├── daily_report.py
│ ├── intrusion_detector.py
│ ├── email_alert.py
│ └── summarizer.py
│
├── assistant/
│ ├── hazel_voice_assistant.py
│ ├── speak_alerts.py
│ ├── wake_word_hey_shadow.py
│
├── auth/
│ ├── face_auth.py
│ ├── vault_unlock.py
│
├── utils/
│ ├── resource_tracker.py
│ ├── email_config.py
│
├── README.md
└── screenshots/ (demo visuals)

yaml
Copy
Edit

---

## ⚙️ Installation & Setup

1. Install Wazuh & configure agent-server communication  
2. Clone this repo:  
   ```bash
   git clone https://github.com/cherry2811/ShadowSentinel-AI.git
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Update email_config.py with your credentials

Run Hazel or Realtime Monitor to begin protection

📸 Demo & Screenshots
Add screenshots or demo GIFs in /screenshots folder
You can also embed a YouTube demo here (later)

🧠 Tech Stack
Python

Wazuh SIEM

iptables

LangChain + LLM (OpenRouter/local)

Face Recognition (OpenCV)

Speech Recognition + pyttsx3

Hazel AI Assistant

Linux (Ubuntu, Kali)

Email + Cron + Firewall

📫 Contact
GitHub: cherry2811, Abhignan2003

Email: charanreddy098@gmail.com, abhignan2003@gmail.com

LinkedIn: linkedin.com/in/charanreddy098
