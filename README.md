SOC-Lab-CPT

Overview

SOC-Lab-CPT is a cybersecurity home lab project designed to simulate the daily activities of a Security Operations Center (SOC) Analyst.

The goal of this project is to develop practical skills in:

- Threat Detection
- Log Analysis
- Security Monitoring
- Incident Response
- Phishing Investigation
- Malware Analysis
- SIEM Operations

Technologies

- Wazuh SIEM
- Sysmon
- Windows Event Logs
- Linux
- TryHackMe
- LetsDefend
- GitHub

Skills Demonstrated

- Security Event Monitoring
- Alert Triage
- Incident Investigation
- IOC Analysis
- Threat Hunting
- Documentation

SOC Architecture

                  ┌─────────────┐
                  │  Internet   │
                  └──────┬──────┘
                         │
                  ┌──────▼──────┐
                  │  Firewall   │
                  └──────┬──────┘
                         │
         ┌───────────────┼───────────────┐
         │                               │
 ┌───────▼───────┐               ┌───────▼───────┐
 │ Windows Host  │               │ Linux Host    │
 └───────┬───────┘               └───────┬───────┘
         │                               │
         └───────────────┬───────────────┘
                         │
                  ┌──────▼──────┐
                  │ Wazuh Agent │
                  └──────┬──────┘
                         │
                  ┌──────▼──────┐
                  │Wazuh Manager│
                  └──────┬──────┘
                         │
                  ┌──────▼──────┐
                  │   Kibana    │
                  │ Dashboard   │
                  └──────┬──────┘
                         │
                  ┌──────▼──────┐
                  │ SOC Analyst │
                  └─────────────┘

Architecture Overview

This Security Operations Center (SOC) architecture demonstrates how security events are collected, analyzed, and investigated within a centralized monitoring environment. The lab simulates real-world SOC operations and provides hands-on experience with security monitoring, threat detection, incident response, and log analysis.

Security Monitoring Workflow

1. Activity occurs on Windows or Linux endpoints.
2. Wazuh Agents collect logs and security events.
3. Events are forwarded to the Wazuh Manager.
4. Detection rules analyze incoming data.
5. Alerts are generated when suspicious activity is detected.
6. Kibana displays alerts and supporting log data.
7. The SOC Analyst investigates and responds to incidents.

Investigation Reports

- Phishing Investigation 001
- Suspicious Login Investigation 001
- Malware Investigation 001

Future Improvements

- Deploy Wazuh
- Configure Sysmon
- Build Detection Rules
- Create Custom Dashboards
- Develop Incident Playbooks
- Threat Intelligence Integration
- MITRE ATT&CK Mapping

Author

Azaxole M

Aspiring SOC Analyst | ISC2 CC Candidate
