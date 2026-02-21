# 💀 AH4 TC | SMS RELAY SYSTEM 💀
### [ Protocol v1.0 | f s o c i e t y ]

**The most sophisticated SMS relay infrastructure designed for high-pressure network testing and automated packet delivery.**

Developed and Maintained by: **AHSAN** & **AH4 Team**

---

## 🎭 The Philosophy
> "Our democracy has been hacked. Our privacy has been compromised. The system is broken. We are here to show you how."
> — **fsociety**

---

## 🚀 Advanced Features

- **Multi-Node Relay Network** - Integration with 35+ diverse API endpoints (BTCL, GP, Healthcare, E-Commerce).
- **Dual Execution Protocols**:
  - **GHOST MODE**: Stealth-optimized sequential packet delivery to bypass basic rate-limiting.
  - **BLITZ MODE**: High-concurrency flood sequence for maximum throughput and pressure testing.
- **Deep System Infiltration** - Displays real-time [NODE INFO] including **MAC Address**, **CPU Architecture**, and **Kernel Version**.
- **Adaptive Packet Formatting** - Intelligent normalization of target node addresses (Phone Numbers) into 8+ different protocol formats.
- **Resilient Infrastructure**:
  - **Auto-Recovery**: Self-healing protocol that restarts on critical socket failures.
  - **Signal Interception**: Custom handlers for `SIGINT` (Halt) and `SIGTSTP` (Suspend) for operational control.
- **Asynchronous Core** - Built on `aiohttp` for non-blocking I/O, capable of handling hundreds of concurrent sessions.
- **Anti-Forensics & Stealth**:
  - Dynamic User-Agent rotation.
  - SSL/TLS certificate verification bypass.
  - Automated session recycling and cookie management.

---

## 🛠️ Deployment Instructions

### 📥 Environment Setup (Windows/Linux/Termux)

```bash
# Clone the encrypted repository
git clone https://github.com/ahsan13411/AH4-SMS-boomer.git
cd AH4-sms-boomer

# Initialize the virtual environment (Optional)
python -m venv venv
source venv/bin/activate  # Linux/Termux
.\venv\Scripts\activate   # Windows

# Install required sub-modules
pip install -r requirements.txt
```

### ⚡ Execution

```bash
python AH4-sms-boomer.py
```

---

## 📱 Operational Parameters

### 1. Ghost Mode (Sequential)
- **Use Case:** Persistent, long-term pressure.
- **Mechanism:** Cycles through all 35+ nodes, sending 5 specialized packets per node with 2-second delays.
- **Stealth Rating:** High.

### 2. Blitz Mode (Concurrent)
- **Use Case:** Rapid system overload.
- **Mechanism:** Parallel execution across all nodes simultaneously in multiple waves.
- **Power Rating:** Maximum.

---

## 🧬 System Information [Node Info]
The system automatically extracts and displays:
- **Timestamp:** Local operation time.
- **Hostname:** Target machine identifier.
- **IPv4:** Network interface address.
- **MAC:** Hardware unique identifier.
- **CPU:** Processor architecture.
- **Kernel:** Operating system and build version.

---

## 🛡️ Operational Security (OPSEC)
- **Header Masking:** All requests use randomized headers to mimic legitimate browser traffic.
- **Connection Pooling:** Optimized TCP connectors to prevent socket exhaustion.
- **Request Obfuscation:** Critical API endpoints are base64 encoded within the source to prevent simple string-based detection.

---

## 🚨 Troubleshooting

| Issue | Mitigation |
| :--- | :--- |
| **SSL Handshake Failure** | `pip install --upgrade certifi urllib3` |
| **I/O Loop Latency** | `pip install uvloop` (Linux only) |
| **Dependency Conflicts** | `pip install -U aiohttp async-timeout` |
| **ANSI Color Support** | Use Windows Terminal, PowerShell, or Termux |

---

## ⚠️ Legal & Ethical Mandate
**THIS SYSTEM IS FOR EDUCATIONAL AND AUTHORIZED TESTING PURPOSES ONLY.**

The **AH4 Team** provides this infrastructure to demonstrate vulnerabilities in SMS gateway protocols. 
- Do **NOT** use this for illegal harassment.
- Do **NOT** use this to violate privacy laws.
- The developers (Ahsan & AH4 Team) assume **zero responsibility** for unauthorized or malicious use.

---

## 🎉 Credits & Alliance

**Lead Developer:** [AHSAN](https://github.com/ahsan13411)
**Core Engineering:** [AH4 Team](https://github.com/ahsan13411/AH4-SMS-boomer)

**Special Acknowledgments:**
- The fsociety collective.
- Open-source async-IO contributors.
- All researchers documenting SMS gateway vulnerabilities.

---

## 📝 Transmission Log (Changelog)

### v1.0.0-AH4
- Re-branded to **AH4 TC**.
- Integrated **fsociety** aesthetic and red-team UI.
- Added **MAC** and **CPU** telemetry.
- Optimized directory structure for CMD/PowerShell compatibility.
- Fixed nested path execution errors.

---
**"Hello, friend. Let's get to work."** 💀
