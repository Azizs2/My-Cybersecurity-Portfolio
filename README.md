# My-Cybersecurity-Portfolio
Technical documentation of my cybersecurity labs, PoCs, and penetration testing projects. Proof of work in action
___
# Malware Analysis & Threat Intelligence: njRAT Investigation
Executed a comprehensive dynamic and static analysis of an njRAT (Bladabindi) sample to identify its infection vectors, persistence mechanisms, and command-and-control (C2) infrastructure. Utilized Triage Sandboxing to observe real-time behavior, resulting in a 10/10 risk score classification. Mapped all observed adversary behaviors to the MITRE ATT&CK framework, specifically identifying T1059 (Command and Scripting Interpreter) and T1547 (Boot or Logon Autostart Execution). Extracted critical Indicators of Compromise (IoCs), including C2 IP addresses and file hashes, to support proactive threat hunting and network defense.

**Technologies Used**: Triage Sandbox, Static Analysis, MITRE ATT&CK Mapping, Network Traffic Analysis, IoC Extraction, Malware Reporting.

---
# Penetration Testing & Findings Report: DibiShop E-Commerce Investigation
Executed a comprehensive black-box penetration testing on the "DibiShop" e-commerce platform to identify critical security flaws before its production release. Conducted automated and manual exploitation to map the application's attack surface, resulting in the discovery of a Critical Attack Chain. Mapped findings to the OWASP Top 10, specifically identifying A01:2021-Broken Access Control, A02:2021-Cryptographic Failures, and A05:2021-Security Misconfiguration. Extracted sensitive data, including administrative credentials and source code, demonstrating a total system compromise.


**Technologies Used**: Manual Review, Gobuster (Directory Brute-forcing), Git-Dumper, SQL View, OWASP Methodology, CVSS v3.1 Scoring

---
# Digital Forensics & Incident Response: SIEM-Based Post-Breach Investigation
Executed a comprehensive passive digital forensics investigation and threat hunting on a compromised e-commerce infrastructure using a co-located Wazuh SIEM. Reconstructed a "Low and Slow" attack chain from log telemetry, identifying initial SSH brute force attempts, subsequent malicious web directory scanning (HTTP 400 anomalies), and the critical point of breach via compromised local credentials. Executed structured incident handling aligned with the NIST SP 800-61 r2 framework across Detection, Containment, Eradication, and Recovery phases. Mapped adversary behaviors to the MITRE ATT&CK matrix, specifically identifying T1595.002 (Active Scanning), T1110.001 (Password Guessing), and T1078.003 (Valid Accounts). Developed a comprehensive system hardening roadmap featuring key-based authentication migration, Fail2ban integration, and ModSecurity WAF deployment to mitigate residual risks.

**Technologies Used**: Wazuh SIEM, Linux CLI Analytics, NIST SP 800-61 r2, MITRE ATT&CK Mapping, Log Correlation, Cross-Log Analysis, CVSS v3.1 Scoring, System Hardening.


