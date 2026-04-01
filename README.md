# Soc-homelab
Hands-on SOC homelab simulating attacker and victim environments using Kali Linux and Windows. Includes network scanning, reconnaissance, and security analysis using tools like Nmap.
# 🛡️ SOC Homelab Project

## 📌 Overview
Built a virtualized cybersecurity lab in VirtualBox to simulate attacker and victim environments and practice foundational SOC analyst skills.

## 🖥️ Lab Setup
- Virtualization: VirtualBox  
- Attacker Machine: Kali Linux  
- Victim Machine: Windows 11  

## 🎯 Objective
Simulate network reconnaissance against a Windows host and analyze how firewall protections affect scan results.

---

## 🔍 Activity Performed

### Network Scan with Nmap
**Command used:**
bash
nmap 192.168.56.101

### Findings
- All scanned ports were in filtered/no-response state
- Indicates presence of firewall protections on the Windows host
### Screenshot
![Nmap Scan](nmap%20scan.png)
---

## 🧠 Analysis

The Nmap scan showed that the target host was reachable, but the scanned ports did not return normal responses. This indicates that firewall protections are likely preventing external visibility into exposed services.

This demonstrates an important defensive concept: even when a system is online, security controls can reduce an attacker's ability to identify open ports and available services during reconnaissance.

---

## 🚀 Skills Demonstrated

- Virtual lab setup
- Network reconnaissance
- Port scanning with Nmap
- Basic interpretation of scan results
- Understanding firewall impact on network visibility

---

## 🔮 Future Improvements

- Install Sysmon on the Windows host for endpoint logging
- Deploy Splunk for centralized log collection and analysis
- Re-run reconnaissance activity and investigate resulting logs
- Create alerting and detection notes for observed behavior
