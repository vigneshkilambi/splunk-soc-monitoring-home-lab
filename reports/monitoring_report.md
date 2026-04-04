# SOC Monitoring Report

## 📝 Summary
This project focuses on continuous monitoring of system activity using Splunk SIEM and Sysmon logs to detect suspicious behavior.

## 🔍 Monitoring Activities

### 1. PowerShell Activity
- Detected PowerShell execution using Sysmon Event ID 1
- Command-line details analyzed for suspicious activity

### 2. File Creation Monitoring
- Monitored file creation events using Sysmon Event ID 11
- Identified new files created on the system

### 3. Failed Login Detection
- Monitored failed login attempts using Event ID 4625
- Detected multiple failed login attempts indicating possible brute-force attack

---

## 📊 Findings
- PowerShell activity observed and analyzed  
- File creation events successfully monitored  
- Multiple failed login attempts detected  

---

## ✅ Conclusion
The lab demonstrates how SOC analysts monitor endpoint activity and detect suspicious behavior using SIEM tools.

---

## 🎯 Skills Demonstrated
- SIEM Monitoring (Splunk)  
- Log Analysis (Sysmon & Windows Logs)  
- Threat Detection  
- Security Monitoring  
