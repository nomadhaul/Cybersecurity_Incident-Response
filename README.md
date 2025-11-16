# Cybersecurity_Incident-Response
##Incident report analysis
##Instructions
As you continue through this course, you may use this template to record your findings after completing an activity or to take notes on what you've learned about a specific tool or concept. You can also use this chart as a way to practice applying the NIST framework to different situations you encounter.
##Summary:
Due to a DDoS attack, the internal network was compromised for 2 hours until it was resolved. Network services stopped suddenly due to an incoming flood of ICMP packets. This was responded to by blocking all incoming ICMP packets, stopping non-critical networks, and restoring critical networks. ICMP pings were sent through an unconfigured firewall, causing the DDoS. This impacted internal network traffic, disabling access to network resources. 
##Identify:
We were told that the attack was DDoS and that the malicious actor sent a flood of ICMP pings into the network. In this case, it’s safe to assume this was an ICMP flood DDoS
##Protect:
The network security team has implemented firewall rules to limit the rate of ICMP packets coming in and IP address verification from the source.
##Detect:
Network monitoring software to detect abnormal traffic has been installed, as well as an IDS/IPS system to filter out ICMP traffic.
##Respond:
The cybersecurity team will isolate all affected systems to mitigate damage and loss of secure information and to prevent further network disruptions. Attempts to restore critical operating systems will be made. Network logs will be analyzed and reported.
##Recover:
A DDoS attack by ICMP flooding requires access to the restored network. ICMP flood is now blocked through the firewall. All non-critical networks will be shut down to allow the network to regulate and restore, and then they can be brought back online.

________________________________________

Reflections/Notes: The team seems to have grown greatly from this attack. And they have been shown the importance of correct firewall configurations. This will keep the team sharp for future occurrences. 

