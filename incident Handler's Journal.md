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

# Phishing incident response playbook
```
Date: 
07/20/2022
Entry:
1
Description
Evaluate the alert
Tool(s) used
N/A
The 5 W's 
Who caused the incident? Clyde West
What happened? Phishing email 
When did the incident occur? Wednesday, July 20, 2022 09:30:14 AM
Where did the incident happen? The incident occurred within the businesses HR department
Why did the incident happen? A phishing email was recieved by sender Clyde West of Def Communications, with a password-protected attachment, “bfsvc.exe,” which was downloaded infecting the users system. 
Additional notes
Having previously investigated the file hash, it is confirmed to be a known malicious file. Furthermore, the alert severity is reported as medium. With these findings, I chose to escalate this ticket to a level-two SOC analyst to take further action.
```
# Final Report

```
Goal 1: Identify exactly what happened.
December 28, 2022, at 7:20 p.m., PT,
Goal 2: Identify when it happened.
At approximately 3:13 p.m., PT, on December 22, 2022, an organization recieved an phishing email. The employee that received the email from an external email address where the sender requested a $25,000 cryptocurrency payment. The employee assumed the email was spam and deleted it. The ransom increased to 50,000 byt the time the incident was brought to the security team for further investiation into whether data was in fact stolen and how.

Goal 3: Identify the response actions that the company took.
A vulnerabilty was detected in the e-commerce application which allowed the attacker to access customer transaction data. It has been determined that the attacker was able to accomplish this by modifying the order number included ub tge URL string of a purchase confirmation page, allowing them to access customer purchse confirmation pages. Thea attacker collected this customer data. The logs indicated that the attacker accessed the information of thousands of purchase confirmation pages.


Goal 4: Identify future recommendations.
To prevent future recurrences, we are taking the following actions:
-Perform routine vulnerability scans and penetration testing.
-Implement the following access control mechanisms:
-Implement allowlisting to allow access to a specified set of URLs and automatically block all -requests outside of this URL range.
-Ensure that only authenticated users are authorized access to content.

```
Reflections/Notes: Record additional notes.
The organization collaborated with the public relations department to disclose the data breach to its customers. Additionally, the organization offered free identity protection services to customers affected by the incident. 

After the security team reviewed the associated web server logs, the cause of the attack was very clear. There was a single log source showing an exceptionally high volume of sequentially listed customer orders.
