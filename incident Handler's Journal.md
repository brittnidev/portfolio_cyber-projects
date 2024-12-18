# Incident Handler's Journal

# Instructions
As you continue through this course, you may use this template to record your findings after completing an activity or to take notes on what you've learned about a specific tool or concept. You can also use this journal as a way to log the key takeaways about the different cybersecurity tools or concepts you encounter in this course.

```
Date: 
1/18/24
Entry:
1
Description
Initial detection and documentation
Tool(s) used
N/A
The 5 W's 
Capture the 5 W's of an incident.
Who caused the incident? An organized group of unethical hackers
What happened? A  small U.S. healthcare clinic expereinces a security incident triggered by a phishing email containing malicious attachemnt and involving ransomware.
When did the incident occur? Tueaday Morning at 9am
Where did the incident happen? The incident occurred within the small U.S. health care clinic specializing in primary-care services.
Why did the incident happen? Employees were victimized by intelligent  hackers that used a phishing email as a tactic  to demand a ransome. They promise restoring access to their encrypted files by supplying the clinic with a decryption key if they first pay the hackers a large sum of money. 
Additional notes
Identified the type of phishing email and its contents. This inicident highlights the need for the critical need for cybersecurity awareness in order to safeguard the business and its clients information. 
```


```
Date: 
1/18/24
Entry:
2
Description
Triage and Analysis
Tool(s) used
Wireshark
The 5 W's 
Capture the 5 W's of an incident.
Who caused the incident? Detected communication with known malicious IP addresses and identified the delivery of a malicious payload.
What happened? N/A
When did the incident occur? N/A
Where did the incident happen? N/A
Why did the incident happen? N/A
Additional notes
The server affected seems to be overwhelmed, began to deploy preventative measures in orde to mitigate potential vulnerabilities and to block future phishing attempts. 
```


```
Date: 
1/18/24
Entry: 
3
Description
Packet Capture Review
Tool(s) used
Packet capture tool, Wireshark
Additional notes
Analyzed the packet capture for data exfiltration and malware communication. Detected communication with known malicious IP addresses and identified the delivery of a malicious payload.
```


```
Date: 
1/18/24
Entry:
4
Description
Expanded Investigation with SPLUNK
Tool(s) used
SPLUNK
Additional notes
Correlated logs from various sources to identify patterns of compromise. Extracted user activity logs to pinpoint the compromised account. Reviewed file access logs to track unauthorized encryption activities. Cross-referenced IP addresses and hashes with threat intelligence databases.
```


```
Date: 1/18/24
Entry:
5
Description
Suspicious File Analysis with VirusTotal
Tool(s) used
VirusTotal
Additional notes
Collected the hash of the suspicious file identified during the packet capture analysis. Submitted the file hash to VirusTotal for analysis. Reviewed the results from VirusTotal, which indicated [15,000] detections from various antivirus engines, confirming the file as malicious (e.g., "Ransomware" or "Trojan"). Analyzed the behavioral reports and additional metadata provided by VirusTotal for insights on the file's functionality and potential impact.

```


```
Date: 1/18/24
Entry:
6
Description
Incident Containment, Time of containment 19:45 PM
Additional notes
Isolated affected systems to prevent further spread of the ransomware. Disabled compromised user accounts and enforced password resets across the organization.
```

Reflections/Notes: Record additional notes.
The use of VirusTotal provided critical insights into the nature of the suspicious file and confirmed its malicious intent. This, combined with other investigative methods, allowed for a comprehensive understanding of the incident. The findings emphasize the importance of integrating threat intelligence tools into incident response efforts to enhance detection and mitigation capabilities.

