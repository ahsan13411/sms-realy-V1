![Banner](./banner.png)

# 🚀 AH4-SMS-boomer (AH4 TC)
### Powerful, Fast, and Easy-to-Use SMS Testing Tool

Welcome to **AH4-SMS-boomer**, a professional SMS relay tool designed for network testing and fun. Created by **Ahsan** and the **AH4 Team**, this tool combines over 35+ services into one simple interface.

---

## 👤 Credits & Links
- **Lead Developer:** [AHSAN](https://github.com/ahsan13411)
- **Official Repository:** [AH4-SMS-boomer](https://github.com/ahsan13411/AH4-SMS-boomer)
- **Team:** **AH4 Team**

---

## ✨ Key Features
- **35+ Working APIs:** Support for BTCL, Grameenphone, Healthcare, and E-commerce services.
- **Two Simple Modes:**
  - **👻 Ghost Mode:** Sends messages steadily and slowly to avoid being blocked.
  - **⚡ Chaos Flood:** Advanced burst mode with random jitter, task shuffling, and maximum throughput.
- **🛡️ Advanced OPSEC:** Spoofs Referers (Google, FB) and randomizes request patterns to bypass WAFs.
- **🔍 Phone Tracking:** Automatically extracts carrier, region, and timezone info for any number.
- **🌐 Proxy Support:** Load custom proxies from `proxies.txt` or use the Auto-Scraper.
- **📡 Auto-Scrape:** Instantly fetches thousands of fresh SOCKS4, SOCKS5, and HTTP proxies from global GitHub repositories.
- **📱 Device Spoofing:** Rotates through 500+ random User-Agents and IP headers to mimic real users.
- **System Dashboard:** View your hardware info (CPU, MAC address, and IP) right in the app.
- **Auto-Formatting:** Just enter the number; the tool handles the country code automatically.
- **Smart Recovery:** Automatically restarts if it runs into connection issues.

---

## 🛠️ How to Install

### 1. Download the Tool
Open your terminal (CMD, PowerShell, or Termux) and run:
```bash
git clone https://github.com/ahsan13411/AH4-SMS-boomer.git
cd AH4-SMS-boomer
```

### 2. Install Dependencies
Make sure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 3. Start the Tool
```bash
python AH4-sms-boomer.py
```

---

## 🎯 How to Use
1. **Launch the script** using the command above.
2. **Choose your mode:** Type `1` for Ghost Mode (Stealth) or `2` for Blitz Mode (Fast).
3. **Enter the target number:** Enter the phone number you want to test.
4. **Relax:** The tool will handle the rest. Press `CTRL+C` anytime to stop.

---

## 🧬 System Info [Node Info]
The tool displays your current system status for better tracking:
- **Timestamp:** Current time.
- **IPv4 & MAC:** Your network identifiers.
- **CPU:** Your processor model.
- **Kernel:** Your Operating System version.

---

## ⚠️ Important Disclaimer
**FOR EDUCATIONAL PURPOSES ONLY.**

This tool was created by the **AH4 Team** to demonstrate how SMS gateways work. 
- Please **do not** use this for harassment or illegal activities.
- The developers are **not responsible** for any misuse of this tool.
- Use it responsibly and respect others' privacy.

---

## 🚨 Troubleshooting
If you see errors, try updating your Python packages:
- **SSL Errors:** `pip install --upgrade certifi urllib3`
- **Connection Errors:** `pip install -U aiohttp async-timeout`

---
**"Hello, friend. Let's get to work."** 💀
