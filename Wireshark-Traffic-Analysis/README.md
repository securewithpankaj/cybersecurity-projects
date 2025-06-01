# 🌐 Network Traffic Analysis using Wireshark

## 📘 Project Overview
This project involves analyzing live network traffic using Wireshark to detect security anomalies such as ARP spoofing and DNS tunneling.

## 🔧 Tools Used
- Wireshark
- VirtualBox lab setup
- Ubuntu and Windows test VMs

## 📊 Key Findings
- Identified ARP spoofing using repeated ARP requests from a rogue MAC
- Detected DNS tunneling by observing abnormal query patterns

## 📂 Project Structure
- `captures/arp-spoof.pcapng`: Captured malicious ARP traffic
- `screenshots/`: Packet details and protocol analysis
- `SOC-report.md`: Security operations report documenting findings

## 📸 Screenshots
![ARP Detection](screenshots/arp-spoof-detection.png)

## 💡 Filters Used
```wireshark
arp
dns
