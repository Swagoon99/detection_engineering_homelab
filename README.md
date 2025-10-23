# Detection Engineering Homelab

**Author:** Frederick Adigun  
**Category:** Detection Engineering  

Detection engineering is the practice of creating, testing, and fine-tuning detection logic to identify malicious, suspicious, or policy-breaking activities across systems, networks, and applications.  

This homelab demonstrates how to build a complete detection stack using open-source tools to simulate realistic security operations, endpoint visibility, and response workflows.

##  Tools and Stack Overview

- **SIEM:** [Wazuh](https://wazuh.com/) — Open-source SIEM with built-in XDR capabilities for centralized log management and detection.  
- **IAM:** [Keycloak](https://www.keycloak.org/) — Provides identity and access management for secure authentication and authorization.  
- **Endpoint Visibility:** [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) — Offers deep system monitoring and event collection.  
- **Attack Simulation:** Controlled malware execution to observe how the detection stack responds to real-world attack patterns.  
- **Bonus:** [pfSense](https://www.pfsense.org/) — Configured as a firewall to manage inbound and outbound network traffic.

##  Project Structure

This project is organized into clearly labeled sections:
1. Wazuh setup and configuration  
2. Keycloak integration for IAM  
3. Sysmon deployment and event forwarding  
4. Controlled attack simulation and detection validation  
5. pfSense firewall setup and traffic rule configuration  

Each section includes setup steps, screenshots, and analysis of detection behavior.

##  Follow the Series

This project is a multi-section **Detection Engineering** series.  
All parts have been uploaded on my **[Medium page](#)** — each labeled in sequence for continuity.


*This homelab reinforces core detection engineering concepts by integrating SIEM, IAM, and endpoint telemetry to emulate modern SOC detection workflows.*
