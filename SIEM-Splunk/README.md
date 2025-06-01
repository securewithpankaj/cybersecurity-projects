# 🔐 SIEM Log Monitoring using Splunk

## 🧾 Project Overview
This project demonstrates how to build a basic SIEM setup using Splunk to collect, analyze, and alert on logs from Windows and Linux machines.

## 🧰 Tools Used
- Splunk Enterprise (Free version)
- Splunk Universal Forwarder
- Ubuntu Linux
- Windows 10 VM
- VirtualBox

## 🔍 Key Features
- Real-time log ingestion from multiple machines
- Detection of failed login attempts
- Custom alerts for suspicious activities
- Dashboard for visual monitoring

## 📸 Screenshots
![Splunk Dashboard](screenshots/splunk-dashboard.png)

## 📁 Files Included
- `alerts/failed-login-alert.spl`: SPL query to detect brute-force logins
- `SOC-report.md`: Analyst report on findings and actions taken

## 📖 How to Run
1. Install Splunk on your main machine or VM
2. Forward logs using Universal Forwarder from Linux/Windows
3. Import alert SPL queries into Splunk
4. Set up real-time alerts and dashboards

## ✅ Outcome
This setup helps detect common security threats like brute-force attacks and user account changes.
