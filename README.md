# Soc-homelab
Hands-on SOC homelab simulating attacker and victim environments using Kali Linux and Windows. Includes network scanning, reconnaissance, and security analysis using tools like Nmap.
# 🛡️ SOC Homelab Project

## 📌 Overview
Built a virtualized cybersecurity lab to simulate real-world attack and defense scenarios using VirtualBox.

## 🖥️ Lab Setup
- Virtualization: VirtualBox  
- Attacker Machine: Kali Linux  
- Victim Machine: Windows 11  

## 🎯 Objective
To simulate network reconnaissance and identify exposed services on a target system.

---

## 🔍 Activity Performed

### Network Scan using Nmap

Command used: nmap 192.168.56.101

### Findings
- All scanned ports were in filtered/no-response state
- Indicates presence of firewall protections on the Windows host
### Screenshot
![Nmap Scan](nmap%20scan.png)
---

## 🧠 Analysis

The Nmap scan indicated that all ports were in a filtered/no-response state.

This suggests that the Windows host is protected by a firewall, preventing external visibility of services.

This behavior demonstrates how defensive controls can limit reconnaissance efforts and reduce an attacker's ability to identify exposed services.

---

## 🚀 Skills Demonstrated

- Network reconnaissance  
- Port scanning  
- Service enumeration  
- Virtual lab setup  
- Basic security analysis  

---

## 📸 Screenshots



---

## 🔮 Future Improvements

- Implement system monitoring using Sysmon  
- Integrate SIEM tool (Splunk) for log analysis  
- Detect and analyze attack activity in real time  
