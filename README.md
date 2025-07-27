# Use-the-NIST-Cybersecurity-Framework-to-respond-to-a-security-incident

Overview
This project documents a cybersecurity incident report and response plan developed after a Distributed Denial of Service (DDoS) attack on a multimedia company. The plan is guided by the NIST Cybersecurity Framework (CSF), which provides a flexible and customizable structure for identifying, protecting, detecting, responding to, and recovering from cybersecurity incidents.

The report includes an in-depth analysis of the incident, technical remediation steps, and long-term network hardening strategies aimed at reducing the likelihood of future attacks.

🧾 Scenario Summary
A malicious actor launched a DDoS attack by flooding the company’s internal network with spoofed ICMP packets, taking network resources offline for two hours. An investigation revealed that the packets were able to bypass defenses due to an unconfigured firewall.

✅ Incident Response Measures Taken:
Implemented a firewall rule to rate-limit ICMP traffic.

Added source IP verification to detect spoofed IP addresses.

Deployed network monitoring software to identify abnormal traffic.

Installed an IDS/IPS system to filter suspicious ICMP packets.

🔍 Framework Used: NIST Cybersecurity Framework (CSF)
The response plan is structured around the five core NIST CSF functions:

Function	Action Taken
Identify	Performed audits of firewalls, network configurations, and access policies to find weaknesses.
Protect	Updated firewall settings, trained staff on incident response protocols, and implemented access controls.
Detect	Introduced network monitoring tools and signature-based intrusion detection systems.
Respond	Blocked incoming ICMP traffic, enabled IP filtering, and conducted root-cause analysis.
Recover	Restored network services and implemented long-term safeguards for resiliency.


💡 Learning Objectives
Analyze real-world network attacks using structured frameworks.

Apply NIST CSF principles in a practical scenario.

Create actionable security incident reports.

Improve network defense through both reactive and proactive methods.

🧠 Skills Demonstrated
Incident detection and response

Network defense configuration

Threat analysis and risk assessment

Application of cybersecurity frameworks

