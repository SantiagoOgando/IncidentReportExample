<h1>Incident Report Example</h1>

<h2>Summary</h2>
The organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources.


<br />

<h2>Identify:</h2>
The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack.  

<h2>Protect:</h2>
To address this security event, the network security team implemented: 
A new firewall rule to limit the rate of incoming ICMP packets
Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
Network monitoring software to detect abnormal traffic patterns
An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

<h2>Detect:</h2>
Enhance network monitoring capabilities to promptly detect abnormal traffic patterns indicative of DDoS attacks. Implement real-time alerts for unusual ICMP traffic.

<h2>Respond:</h2>
Establish a well-defined incident response plan for DDoS attacks. Assign roles and responsibilities. Implement procedures for blocking malicious traffic, shutting down non-critical services, and restoring critical ones.


<h2>Recover:</h2>
After the incident, assess the impact on affected systems. Initiate recovery efforts to restore services to normal operation. Conduct a thorough post-incident analysis to determine improvements to prevent future attacks.



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
