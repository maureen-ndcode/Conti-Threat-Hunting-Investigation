# Conti-Threat-Hunting-Investigation
# Project Overview
This project documents a threat-hunting investigation conducted in the TryHackMe Conti room.
The objective was to analyze Windows and Sysmon logs in Splunk to detect ransomware activity, trace attacker actions, and identify persistence mechanisms.
This project demonstrates practical skills in:
- Log analysis
- Threat hunting
- Incident investigation
- Web shell detection

# Investigation Timeline
- Accessed Splunk logs and corrected time range issues
- Identified suspicious executable and ransomware location
- Determined Sysmon event ID for file creation
- Retrieved MD5 hash of the ransomware
- Detected files replicated across directories
- Identified attacker account creation command
-Investigated process migration activity
-Detected web shell and execution command
-Investigated CVEs related to exploitation

# Tools Used
-Splunk
-Sysmon
-Windows Event Logs

# Key Skills Demonstrated
- Threat hunting in Windows environments
- Writing and analyzing Splunk queries
- Identifying attacker persistence
- Process and command-line investigation
- Web shell detection
- Investigating ransomware activity

# Challenges Faced
- Initial lack of log data due to incorrect time range
- Missing hash values in standard fields
- Difficulty confirming CVEs due to limited evidence
- Missing EventCode logs for process injection

# Learning Outcomes
Through this project, I learned:
- How to perform structured threat hunting
- How to investigate attacker behavior using logs
- How ransomware activity appears in Windows and Sysmon logs
- How to trace execution chains in Splunk

# Project Report

[Download Full Report](TryHackMe_Conti_Threat_Hunting_Report.pdf)

# Author
Maureen
Cybersecurity & Data Science Student
Interested in Threat Hunting, Ethical Hacking, and Log Analysis
