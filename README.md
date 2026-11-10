# Windows Security Log Analysis with PowerShell

## Project Overview
This project focuses on analyzing Windows Security Event Logs using PowerShell. It demonstrates how to monitor system activities, identify suspicious login attempts, detect possible brute-force attacks, and analyze security-related events.

The project connects Windows log analysis with the STRIDE Threat Modeling approach to improve security monitoring and threat detection.

## Objectives
- Analyze Windows Security Event Logs using PowerShell.
- Detect failed and successful login attempts.
- Identify possible brute-force attacks.
- Monitor privileged account activities.
- Detect suspicious account and group changes.
- Export security log reports in CSV and HTML formats.

## Tools & Technologies
- Operating System: Windows 11
- Shell: Windows PowerShell 5.1
- Command: Get-WinEvent
- Security Log: Windows Event Viewer
- Threat Modeling: STRIDE
- Reporting: CSV and HTML

## Event IDs Analyzed

| Event ID | Description |
|---|---|
| 4624 | Successful Logon |
| 4625 | Failed Logon |
| 4648 | Logon with Explicit Credentials |
| 4672 | Special Privileges Assigned |
| 4732 | Member Added to Security Group |
| 4798 | User's Local Group Membership Enumerated |
| 5140 | Network Share Accessed |

## Key Tasks Performed
1. Checked PowerShell version.
2. Configured script execution policy.
3. Retrieved Windows Security Events.
4. Analyzed successful and failed logons.
5. Inspected suspicious login activities.
6. Detected possible brute-force attacks.
7. Monitored explicit credential usage.
8. Checked network share access.
9. Monitored security group modifications.
10. Analyzed privileged logons.
11. Developed an automated security log analysis script.
12. Exported security reports in CSV and HTML formats.

## STRIDE Threat Modeling
This project relates Windows Security Events to the STRIDE threat categories:

- **Spoofing:** Detecting suspicious authentication attempts.
- **Tampering:** Monitoring security-related changes.
- **Repudiation:** Maintaining security audit records.
- **Information Disclosure:** Monitoring unauthorized information access.
- **Denial of Service:** Identifying repeated failed login attempts.
- **Elevation of Privilege:** Monitoring privileged account activities.

## Key Findings
- 3 failed logon events were identified within 24 hours.
- No source IP reached the configured brute-force threshold.
- 185 successful logon events were recorded.
- 8 explicit credential events were identified.
- No network share access was detected in the analyzed period.
- No security group modifications were detected in the previous 7 days.

## Recommendations
- Enable regular security log monitoring.
- Use strong passwords and Multi-Factor Authentication (MFA).
- Configure account lockout policies.
- Monitor failed login attempts.
- Review privileged account activities.
- Store security logs in a centralized location.

## Learning Outcomes
Through this project, I gained practical experience in:
- Windows Security Monitoring.
- PowerShell Scripting.
- Event Log Analysis.
- Threat Detection.
- STRIDE Threat Modeling.
- Security Report Generation.

## Author
**Name:** Mst. Bithi Khatun  
**Student ID:** 2404024  
**Department:** Cyber Security Engineering  
**University:** University of Frontier Technology, Bangladesh  
**Course Code:** SEC204  
**Course Title:** Threat Modeling and Security Monitoring Sessional

---

*This project was completed as part of an academic cybersecurity laboratory exercise.*
