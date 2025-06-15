# 🔍 Threat Detection in Windows using Python and Splunk

This project detects security threats from Windows Event Logs using Python and visualizes them using Splunk dashboards.

## 📁 Project Files

| File | Description |
|------|-------------|
| `log_parser.py` | Python script to read Windows Security logs |
| `threat_report.txt` | Detected threats in text format |
| `threat_report.csv` | CSV version for Splunk ingestion |
| `screenshots/` | Splunk dashboard & script output images |

## 🔒 Threats Detected:
- Brute Force (Event ID 4625)
- Privilege Escalation (Event ID 4672)
- Encoded PowerShell Execution
- User Account Creation (Event ID 4720)
- Admin Group Addition (Event ID 4732)

## 🧠 Tools Used
- Python + pywin32
- Regex
- Splunk Enterprise (Free Edition)
- Windows 11 Event Logs

## 📊 Splunk Visualization

![Dashboard](screenshots/dashboard.png)

## 📈 Future Improvements
- Add live monitoring via scheduled tasks
- Email/SMS alerts for high severity threats
- Support for firewall/AV logs

## 🧑‍💻 Created By
Shubham Mali  
[LinkedIn Profile](https://www.linkedin.com/in/shubham-mali-2a4817271/)
