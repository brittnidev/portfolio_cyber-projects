# Use the NIST Cybersecurity Framework to respond to a security incident <a name="five">
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

# To address this security event, the network security team implemented:
	• 	A new firewall rule to limit the rate of incoming ICMP packets
	• 	Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
	• 	Network monitoring software to detect abnormal traffic patterns
	• 	An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

	• 	**Identify** security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
	• 	**Protect** internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats.
	• 	**Detect** potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
	• 	**Respond** to contain, neutralize, and analyze security incidents; implement improvements to the security process.
 	• 	**Recover** affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.


# Incident report analysis (Portfolio Project #3)
- **Identify** Our organization recently faced a DDoS attack that disrupted the internal network for two hours. During this incident, network services became unresponsive due to an overwhelming influx of ICMP packets, preventing normal internal traffic from accessing network resources. The issue was resolved after the two-hour period.

- **Protect** The incident management team conducted an audit of the systems, devices, and access policies related to the attack to identify security gaps. They discovered that a malicious attacker had obtained an intern's login credentials, which were then used to access data from our customer database. Preliminary findings indicate that some customer data was deleted from the database.

- **Detect** The team has introduced new authentication policies to safeguard against future attacks, including multi-factor authentication (MFA), limiting login attempts to three, and providing training for all employees on securing their login credentials. Furthermore, we will establish a new firewall configuration and invest in an intrusion prevention system (IPS).

- **Respond** To detect unauthorized access attempts in the future, the team will utilize a firewall logging tool and an intrusion detection system (IDS) to monitor all incoming internet traffic.

- **Recover** The team has disabled the intern's network account and provided training to interns and employees on securing their login credentials moving forward. Upper management has been notified of this incident and will reach out to our customers via mail to inform them about the data breach. Additionally, management will contact law enforcement and other relevant organizations as mandated by local laws.
  
-------