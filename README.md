# 🏰 Seven Kingdoms Offensive Security Lab

> A Game of Thrones–themed multi-stage penetration testing lab built for students to gain real-world offensive security experience.

---

![Seven Kingdoms Lab Banner](game%20of%20throne.jpeg)

## 🚀 About This Lab

The **Seven Kingdoms Lab** is a hands-on internal network simulation designed for cybersecurity students.

It combines:

- 🟢 eJPT fundamentals  
- 🟡 OSCP-style Linux exploitation  
- 🔵 CRTP Active Directory attacks  
- 🔴 CRTO NTLM relay & lateral movement  

This lab simulates a realistic enterprise network where students must think like real penetration testers.

This is NOT a single vulnerable machine — it is a full attack chain.

---

## 🎯 Learning Objectives

Students will practice:

- 🔎 Network & service enumeration  
- 🌐 Web application exploitation (DVWA, Juice Shop, bWAPP)  
- 🐧 Linux privilege escalation  
- 🗂 SMB enumeration & legacy protocol abuse  
- 🔐 NTLM relay attacks  
- 🧠 Kerberoasting  
- 👑 Active Directory privilege escalation  
- 🏴 Multi-stage flag capture  

---

# 🧱 Lab Architecture

All services run inside a Docker bridge network:

---

# ⚙️ Setup Instructions

## 1️⃣ Requirements

- Docker
- Docker Compose
- Minimum 8GB RAM recommended
- Linux / macOS / Windows (WSL2 recommended)

Check installation:

```bash
docker --version
docker compose version


