# SYN-Flood-Attack-Investigation
Analyzed network traffic data from a simulated SYN flood attack causing a web server outage for a travel agency. This project demonstrates incident identification, packet analysis, and initial mitigation strategies for Denial-of-Service attacks.


SYN Flood Attack Analysis and Incident Response
Project Introduction
This project details the investigation of a simulated cybersecurity incident involving a significant service interruption on a travel agency's website. As a security analyst, I identified the root cause of the outage, analyzed its impact, and formulated initial response actions. This exercise demonstrates practical skills in incident identification, network traffic analysis, and preliminary mitigation strategies for common network attacks.

Methodology and Analysis
The incident investigation began with an automated alert indicating a web server problem, followed by a connection timeout error when attempting to access the company's website. Network traffic data, typically captured by a packet sniffer like Wireshark, was provided in a structured Google Sheet format for analysis.

My methodology involved:

Initial Assessment: Reviewing the scenario details and the provided log data to understand the context of the service interruption.

Data Examination: Analyzing the color-coded TCP log within the Google Sheet, focusing on the Protocol, Info, Source, and Destination columns to identify anomalous patterns.

Pattern Recognition: Specifically looking for high volumes of TCP SYN requests, the absence of corresponding ACK packets, and the impact on legitimate traffic.

Attack Identification: Correlating observed network behavior with known characteristics of common network attacks.

Impact Analysis: Determining how the identified attack affected the web server's functionality and the broader business operations.

Response Formulation: Outlining immediate and long-term mitigation strategies based on the analysis.

Incident Report & Findings
A detailed incident report, including the attack explanation, impact analysis, and recommendations, is provided in the SYN_Flood_Incident_Report.md file within this repository.

Key Learnings
This activity reinforced the importance of:

Rapidly identifying attack types from network traffic patterns.

Understanding the TCP three-way handshake and how its disruption leads to service denial.

The immediate need for containment and preliminary mitigation during an active incident.

The limitations of basic blocking mechanisms against sophisticated attackers.
