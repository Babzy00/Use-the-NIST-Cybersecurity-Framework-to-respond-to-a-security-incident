# Use-the-NIST-Cybersecurity-Framework-to-respond-to-a-security-incident

## Activity Overview
In this activity, you will create an incident report using the knowledge you’ve gained about networks throughout this course to analyze a network incident. You will analyze the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF). The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. Creating a quality cybersecurity incident report and applying the CSF can demonstrate a proactive approach to security, improving communication and transparency with stakeholders, and improve security practices within your organization. You can also add the incident report you create to your cybersecurity portfolio when  you complete it.

The CSF is scalable and can be applied in a wide variety of contexts. As you continue to learn more and refine your understanding of key cybersecurity skills, you can use the templates provided in this activity in other situations. Knowing how to identify which security measures to apply in response to business needs will help you determine which are the best available options when it comes to network security.

Be sure to complete this activity before moving on. In the next course item, you will be able to self-assess your response. After that, there will be a completed exemplar to compare to your own work. It will also provide an opportunity for you to answer rubric questions that allow you to reflect on key elements of your professional statement.

-----------------------------

## Scenario

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

- Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

- Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

- Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

- Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

------------------------------

### Summary of the Security Event
A distributed denial of service (DDoS) attack targeted your organization's network by flooding it with ICMP packets. This caused network services to become unresponsive for two hours. The incident was traced back to a misconfigured firewall that allowed the attacker to exploit this vulnerability.

### Identify
- Regular Audits: Conduct regular audits of internal networks, systems, devices, and access privileges to identify potential security gaps.

- Risk Assessment: Continuously assess potential risks to the network and create a risk management plan.

- Inventory Management: Maintain an up-to-date inventory of all network assets and ensure they are properly configured and secured.

### Protect
- Firewall Configuration: Implement a new firewall rule to limit the rate of incoming ICMP packets.

- IP Verification: Enable source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets.

- Policies and Procedures: Establish clear cybersecurity policies and procedures that employees must follow.

- Training: Conduct regular training sessions to keep employees informed about the latest cybersecurity threats and best practices.

- Access Controls: Implement strict access controls to ensure only authorized personnel have access to critical network resources.

### Detect
- Network Monitoring: Deploy network monitoring software to detect abnormal traffic patterns and potential security incidents.

- Intrusion Detection/Prevention System (IDS/IPS): Install an IDS/IPS system to filter out suspicious ICMP traffic and alert the security team of potential threats.

- Log Analysis: Regularly analyze network logs to identify unusual activities that may indicate a security breach.

### Respond
- Incident Response Plan: Develop an incident response plan that outlines the steps to contain, neutralize, and analyze security incidents.

- Communication Protocol: Establish a clear communication protocol for reporting security incidents to the incident management team and stakeholders.

- Post-Incident Analysis: Conduct a thorough analysis of each security incident to identify the root cause and implement improvements to the security process.

- Recovery Plan: Create a recovery plan to restore affected systems to normal operation and recover any lost data or assets.

### Recover
- System Restoration: Implement procedures for restoring systems to normal operation after an incident.

- Data Backup: Ensure regular backups of critical data and systems to facilitate quick recovery.

- Continuous Improvement: Continuously improve the cybersecurity framework based on lessons learned from previous incidents.





