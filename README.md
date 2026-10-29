🛡️ Alert Triage With Splunk — TryHackMe SOC Level 1

🎯 Project Overview

This project focuses on security alert triage and log analysis using Splunk SIEM in a controlled TryHackMe cybersecurity training environment.

The objective was to investigate suspicious system activity by analyzing Linux authentication logs, identifying potential brute-force attacks, examining privilege escalation events, and investigating suspicious user account creation.

This lab provided practical experience with the type of investigative tasks performed by Security Operations Center (SOC) analysts when monitoring security events and identifying potential threats.

🔍 Investigation Summary

During this investigation, I examined security events associated with authentication failures, privileged account activity, and potential persistence mechanisms.

The analysis focused on identifying suspicious behavior, correlating relevant log entries, and understanding how system logs can help security analysts reconstruct potentially malicious activity.

📊 Key Findings

- Failed Login Attempts: Identified 500 failed login attempts in the lab evidence.
- Brute-Force Activity: Investigated a brute-force attack reported to have lasted approximately five minutes.
- Privilege Escalation: Examined events indicating access to root-level privileges.
- Suspicious Account Creation: Investigated the creation of a user account named "system-utm".
- Persistence Investigation: Reviewed account-related activity for potential persistence indicators.

These findings reflect the evidence and answers displayed in the training lab. They should not be interpreted as confirmation of an independently verified real-world compromise.

🛠️ Tools & Technologies

- Splunk SIEM: Used to search, filter, and analyze security events.
- Search Processing Language (SPL): Used to investigate relevant log entries and identify suspicious activity.
- Linux Authentication Logs: Examined authentication events and privileged account activity.
- TryHackMe: Provided the controlled environment for practical SOC training.

🔬 Investigation Methodology

1. Security Event Review

Reviewed available log events to identify suspicious authentication activity and determine which events required further investigation.

2. Authentication Analysis

Investigated failed login attempts and related authentication events to understand patterns that may indicate brute-force activity.

3. Privilege Escalation Analysis

Examined events involving root access and privileged commands to understand how elevated permissions were used during the observed activity.

4. User Account Investigation

Reviewed account creation events to identify the suspicious account "system-utm" and understand why unexpected account creation can be a security concern.

5. Persistence Investigation

Explored account-related evidence for potential persistence indicators. Unauthorized accounts may allow an attacker to regain access after an initial intrusion.

6. Findings Documentation

Recorded the key observations and summarized the evidence to support a structured security investigation.

🧠 Skills Demonstrated

- Security alert triage
- SIEM monitoring and log analysis
- SPL-based event investigation
- Brute-force attack identification
- Linux authentication analysis
- Privilege escalation investigation
- Suspicious account detection
- Persistence analysis
- Security incident documentation

🚨 SOC Analyst Relevance

Alert triage is an important part of daily SOC operations. Analysts review security alerts, assess their significance, investigate supporting evidence, and determine whether escalation is necessary.

This lab helped me understand how authentication logs and system events can be used to identify suspicious activity and support the incident investigation process.

It also reinforced the importance of distinguishing between an initial indicator of compromise and a confirmed security incident.

📚 Key Learning Outcomes

- Understanding how SIEM platforms support security monitoring.
- Recognizing patterns associated with repeated authentication failures.
- Investigating privileged account activity through system logs.
- Understanding why unexpected user account creation requires investigation.
- Using event evidence to build a clearer picture of suspicious activity.
- Documenting findings in a structured and professional format.

🏁 Conclusion

This hands-on lab strengthened my foundational knowledge of SOC workflows, SIEM-based investigations, Linux log analysis, and threat detection.

It provided an opportunity to practice identifying suspicious activity, reviewing relevant evidence, and documenting findings in a manner consistent with entry-level security operations tasks.

I will continue developing these skills through practical cybersecurity labs, independent investigations, and ongoing learning.

⚠️ Disclaimer

This project was completed for educational purposes in a controlled cybersecurity training environment. All analysis was performed using authorized lab resources and training data provided by TryHackMe.

This documentation is intended to demonstrate learning and practical investigation skills. It does not claim that a real-world system was compromised or that a live incident was remediated.

👨‍💻 Project Information

- Author: Cybersecurity Learner
- Learning Platform: TryHackMe
- Learning Path: SOC Level 1
- Lab: Alert Triage With Splunk
- Category: Security Operations / Blue Team
- Primary Tool: Splunk SIEM
- Focus Areas: Alert Triage, Log Analysis, Threat Detection, Privilege Escalation Investigation, and Persistence Analysis

---

