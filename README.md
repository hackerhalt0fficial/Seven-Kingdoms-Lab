# 🏰 Seven Kingdoms Offensive Security Lab

> A multi-stage, Game of Thrones–themed offensive security lab designed to provide students with realistic, hands-on penetration testing experience.

---

## 🔗 Lab Access

📌 **Register / Access the Lab Here:**  
👉 https://docs.google.com/forms/d/e/1FAIpQLSdOGv7UbT1wzIFAbd5L5-jLnCtMD4MZed37I1HOnc6mXyR_lg/viewform?usp=sharing&ouid=103508935715663486190

---

<p align="center">
  <img src="game%20of%20throne.jpeg" alt="Seven Kingdoms Lab Banner" width="900">
</p>

---

## 🚀 Overview

The **Seven Kingdoms Offensive Security Lab** is a comprehensive internal network simulation built using Docker.

It is designed to help cybersecurity students and aspiring penetration testers develop practical, real-world skills within a structured and controlled environment.

This lab integrates techniques aligned with:

- 🟢 eJPT-level fundamentals  
- 🟡 OSCP-style Linux exploitation and privilege escalation  
- 🔵 CRTP-focused Active Directory attack paths  
- 🔴 CRTO-style NTLM relay and lateral movement techniques  

Unlike single-machine challenges, this lab simulates a **realistic enterprise attack chain**, requiring structured thinking, enumeration, pivoting, and privilege escalation across multiple interconnected systems.

---

## 🎯 Learning Objectives

Participants will gain hands-on experience in:

- Network and service enumeration  
- Web application exploitation (DVWA, Juice Shop, bWAPP)  
- Linux privilege escalation techniques  
- SMB enumeration and legacy protocol abuse (SMBv1)  
- NTLM relay attack concepts  
- Kerberoasting and credential extraction  
- Active Directory enumeration and privilege escalation  
- Multi-stage flag capture methodology  

---

# 🧱 Lab Architecture

All services operate within an isolated Docker bridge network, simulating a segmented internal enterprise infrastructure.

### 🏰 Infrastructure Components

- Vulnerable web applications  
- Linux-based SSH foothold system  
- MySQL database server  
- SMB file servers (including legacy configuration)  
- NTLM relay target  
- Active Directory Domain Controller  
- LDAP service  
- BloodHound (Neo4j) for AD attack path analysis  
- Kali Linux attacker machine  

This structure enables a full attack-chain simulation from initial access to complete domain compromise.

---

# ⚙️ Setup Instructions

## 1️⃣ Requirements

- Docker  
- Docker Compose  
- Minimum 8GB RAM recommended  
- Linux, macOS, or Windows (WSL2 recommended for Windows users)

Verify installation:

```bash
docker --version
docker compose version
```

## Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/seven-kingdoms-lab.git
cd seven-kingdoms-lab
```

## Start the Lab

```bash
docker compose up -d
```


Verify containers are running:
```bash
docker ps
```

## Initial Credentials
```bash
username: jon.snow
password: Winter123!
```
