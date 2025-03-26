# Phishing Incident Response Plan

# Overview
This plan outlines the steps to contain, investigate, and remediate a phishing incident in which an employee was tricked into entering their password after clicking a link in a phishing email that appeared to come from our CEO. (Spear-Phishing)

# 1. Immediate Containment and Notification
- **Employee Action:**  
  - Instruct the employee to disconnect from the network (e.g., disable Wi-Fi, unplug the Ethernet cable) immediately.
  - Change the compromised password on all systems.
- **IT/Security Team:**  
  - Disable the affected account temporarily to prevent further unauthorized access.
  - Review accessed resources and data during the suspicious timeframe
  - Identify any suspicious activities (file downloads, email forwarding rules, etc.)
  - Scan endpoint devices used by the employee for malware.
  - Check if any unauthorized sessions are active and force logouts.
  
- **Notification:**  
  - **Internal:**  
    - Inform the IT/Security Operations Center (SOC) immediately.
    - Notify the employee’s manager and Human Resources.
    - Alert the incident response team.
  - **External:**  
    - Email security vendor (if using cloud email protection)
    - Managed security service provider (if applicable)
    - Cybersecurity insurance provider (if policy requires notification)

# 2. Investigation
-  **Email Analysis:**
    - Examine email headers and metadata. (mxtoolbox)
    - Identify sender IP and domain reputation.
    - Extract and analyze the phishing link (in sandboxed environment - *anyrun*).
-  **Log Analysis:**  
    - Review email logs, network traffic, and system access logs to determine the scope and timeline of the breach.
    - Identify any other affected systems or user accounts.
- **Forensic Analysis:**  
    - Preserve logs and evidence for further analysis.
    - Analyze the phishing email to understand its origin, payload, and delivery method.
- **Communication:**  
    - Keep relevant stakeholders updated (management, affected users, and legal/compliance teams).
    - Document every step taken during the investigation.
  
# 3. Remediation and Recovery
- **Password Reset & Multi-Factor Authentication (MFA):**  
  - Enforce password resets for the compromised account and potentially affected accounts.
  - Immediately implement or reinforce MFA across the organization.
- **Patch and Update:**  
  - Check for any vulnerabilities exploited by the phishing attempt and apply necessary patches.
- **User Education:**  
  - Notify all employees about the phishing attempt.
  - Provide immediate refresher training on phishing detection and safe practices.

# 4. Long-Term Improvements
- **Enhanced Training:**  
  - Implement periodic, mandatory phishing awareness training and simulated phishing exercises.
- **Technical Controls:**  
  - Deploy advanced email filtering solutions to detect and quarantine phishing attempts.
  - Improve monitoring and anomaly detection on user accounts and network activity.
- **Policy and Process Updates:**  
  - Review and update incident response and communication plans regularly.
  - Consider establishing a “phishing response team” dedicated to managing and mitigating such threats.
- **Vendor Coordination:**  
  - Regularly update and test external vendor incident response plans.
  - Ensure vendors are informed of our security policies and incident handling procedures.

# 5. Post-Incident Review
- **Debriefing:**  
  - Hold a meeting with all stakeholders to review the incident response, discuss lessons learned, and identify areas for improvement.
- **Reporting:**  
  - Prepare an incident report for internal records and any external regulatory requirements.
 
# Phishing IR Process (Baseline by Me)

![image](https://github.com/user-attachments/assets/94314008-5ee1-49ab-93a1-893bc22cf704)

