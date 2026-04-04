# File Creation Monitoring (Sysmon Event ID 11)

## Description
This detection monitors file creation events on the system to identify suspicious file drops or malware activity.

## Log Source
- Sysmon Logs
- Event ID: 11 (File Creation)

## Detection Logic
New file creation events are monitored, especially in sensitive directories, to detect potential malicious files.

## Analysis
File creation events were captured in the logs, showing new files being created on the system.

## Conclusion
This detection helps identify suspicious file activity and potential malware presence.
