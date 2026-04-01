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

---

## 🧠 Analysis

The Nmap scan revealed exposed services commonly present in Windows environments.  
These services can be potential targets for attackers if not properly secured.

This demonstrates how reconnaissance is performed as an initial step in cyber attacks.

---

## 🚀 Skills Demonstrated

- Network reconnaissance  
- Port scanning  
- Service enumeration  
- Virtual lab setup  
- Basic security analysis  

---

## 📸 Screenshots

(Add screenshots here of your Nmap scan and lab setup)

---

## 🔮 Future Improvements

- Implement system monitoring using Sysmon  
- Integrate SIEM tool (Splunk) for log analysis  
- Detect and analyze attack activity in real time  
