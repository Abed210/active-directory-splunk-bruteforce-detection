# Active Directory Brute-Force Detection Using Splunk SIEM

This is a hands-on cybersecurity project that simulates a brute-force attack against a Windows domain environment and detects it using Splunk as a Security Information and Event Management (SIEM) platform. It demonstrates end-to-end log collection, event analysis, dashboard visualization, and real-time alerting.

## 📁 Project Structure
active-directory-splunk-bruteforce-detection/
├── inputs.conf # Splunk Forwarder config for log sources
├── network-diagram.png # Network topology diagram
├── Active Directory Project.docx # Full project documentation
└── README.md # Project overview and usage guide
---

## 🧰 Tools and Technologies

- **VirtualBox** – Virtualization environment
- **Windows Server 2022** – Active Directory Domain Controller
- **Windows 10** – Target machine
- **Kali Linux** – Attacker machine (Hydra)
- **Ubuntu Server** – Splunk SIEM server
- **Splunk Enterprise** – Log analysis and SIEM
- **Splunk Universal Forwarder** – Log forwarding agent
- **Sysmon** – Endpoint log enrichment

---

## 🔧 Key Features

- ✅ Deployment of an Active Directory environment with users and OUs  
- ✅ Brute-force attack simulation using Hydra (RDP protocol)  
- ✅ Log forwarding with Splunk Universal Forwarder and Sysmon  
- ✅ Detection and investigation of Events
- ✅ Creation of Splunk dashboards to visualize attack patterns  
- ✅ Custom SPL-based alerts for brute-force detection  

---

## 🖼️ Diagram

![Network Diagram](network-diagram.png)

---
📄 License
This project is for educational purposes. Attribution is appreciated if reused or modified.
