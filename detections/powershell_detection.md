# PowerShell Activity Detection

## Description
This detection monitors PowerShell execution on the system, which is commonly used by attackers for malicious activities.

## Log Source
- Sysmon Logs
- Event ID: 1 (Process Creation)

## Detection Logic
If PowerShell processes are executed, especially with suspicious command-line arguments, it may indicate malicious activity.

## Analysis
PowerShell execution was observed in the logs, including command-line details. This helps identify potentially harmful scripts or commands.

## Conclusion
PowerShell activity was successfully detected using Splunk, helping identify possible attacker behavior.
