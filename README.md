# SOAR EDR Project

## Objective

This project integrates LimaCharlie (EDR) and Tines (SOAR) to automate threat detection and response in a SOC environment. Using LaZagne as a simulated credential-dumping attack, LimaCharlie detects the threat via D&R rules and triggers an automated response in Tines. The SOC analyst receives an alert via email/Slack with an option to isolate the compromised endpoint—if confirmed, LimaCharlie automatically quarantines the affected system from the network. This project showcases EDR-SOAR integration, automated incident response, and real-world SOC workflows.

### Skills Learned

- Endpoint Detection & Response (EDR): Configured LimaCharlie to detect malicious activity using Detection & Response (D&R) rules.
- Security Orchestration, Automation, and Response (SOAR): Automated incident response workflows using Tines to handle security alerts and remediation.
- Threat Detection & Incident Response: Simulated LaZagne credential-dumping attack, detected it in real-time, and automated response actions.
- Automated Threat Containment: Implemented endpoint isolation via LimaCharlie to contain compromised systems upon analyst approval.
- Security Alerting & Notification Systems: Configured email and Slack alerts to notify SOC analysts of detected threats.
- SOC Workflow Automation: Created decision-based response mechanisms for analysts to approve or deny remediation actions.
- Hands-on Experience with Cybersecurity Tools: Worked with EDR, SOAR, Python scripting, API integrations, and security automation.
- Real-World SOC Simulation: Practiced SOC workflows, improving skills in monitoring, threat analysis, and incident management.

### Tools Used

- LimaCharlie (EDR): Configured Detection & Response (D&R) rules to detect malicious activity and automate endpoint isolation.
- Tines (SOAR): Designed automated workflows to trigger alerts and execute response actions.
- LaZagne (Credential Dumping Tool): Simulated an attack to test EDR detection and incident response capabilities.
- Slack to push notification for simulated team members about potential attack and prompt to isolate the compromised machine. 

## Steps

All steps and documentation for this lab are linked below.

<a href="https://github.com/hameetbenipal/SOAR-EDR-Project/blob/main/SOAR%20Project%20Documentation.pdf">Lab Documentation</a>
