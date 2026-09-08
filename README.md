# SOC Incident Investigation

## Overview

This project documents a practical Security Operations Centre (SOC) investigation involving suspicious PowerShell activity on a Windows endpoint.

The investigation was carried out using Microsoft Sentinel(as a Siem) and Microsoft Defender(as an EDR) to identify, analyse and investigate suspicious activity generated within the environment.

## Objective

The objective of this investigation was to:

- Detect suspicious activity on a Windows endpoint
- Investigate suspicious PowerShell execution
- Analyse alerts and incident information
- Review affected entities and processes
- Investigate endpoint activity using Microsoft Defender
- Identify potential security risks and vulnerabilities
- Document findings and determine appropriate response actions

## Tools Used

- Microsoft Sentinel (SIEM)
- Microsoft Defender(EDR)
- Microsoft Azure Environment
- Windows Endpoint

## Investigation Summary

During the investigation, Microsoft Sentinel generated an incident related to suspicious PowerShell activity on a Windows endpoint.

The incident was reviewed to understand the alerts, affected entities, processes and activities associated with the suspicious behaviour. Microsoft Defender was also used to investigate the endpoint and review additional security information.

This project demonstrates the practical process of investigating a security alert from detection through to analysis and response.

## Investigation Process

1. Security incident Detection
2. Incident Investigation
3. Endpoint and Entity analysis
4. Vulnerability Review
5. Key skills demonstrated
6. Conclusion

## Screenshots and Investigation Evidence

The following sections document the investigation process and evidence collected during the analysis.

### 1. Security Incident Detection

Microsoft Sentinel detected suspicious activity and generated an incident for investigation. The incident was classified as Medium severity and contained two related alerts.

This marked the beginning of the investigation and provided the initial information required to analyse the suspicious activity.

<img width="2048" height="1536" alt="fd7d2132-cef6-4345-a154-fcf476cf0d71" src="https://github.com/user-attachments/assets/993afabb-575a-4308-9ec5-c5274db55aec" />


### 2. Incident Investigation

Microsoft Sentinel was used to investigate the security incident and review the suspicious PowerShell activity.

The incident was classified as Medium severity and contained two related alerts. The graphical incident representation (Attack Story) visually shows the relationship between the affected user, endpoint, IP addresses, and processes involved in the incident.

This graphical view helped provide a clearer understanding of how the suspicious activity was connected across the affected entities.

<img width="2048" height="1536" alt="c79a89d8-4d1c-4df2-8696-3075c1d603b8" src="https://github.com/user-attachments/assets/eeaba7b6-85a4-48bf-ab86-7b389dda2a15" />


### 3. Endpoint and Entity Analysis

The affected endpoint and related entities were analysed to identify the systems and processes involved in the security incident.

The investigation identified the Windows 11 endpoint, associated processes, and relevant entities connected to the suspicious activity. Reviewing these entities helped provide additional context about the incident and its potential impact.

<img width="2048" height="1536" alt="b7247ff1-c679-44b8-92cd-b1ebf8a0dc78" src="https://github.com/user-attachments/assets/d23aab53-551e-4af9-b9ad-7c9bba1961f5" />

### 4. Vulnerability Review

The vulnerability review identified multiple discovered vulnerabilities affecting the Windows 11 endpoint. The vulnerabilities are listed with their CVE identifiers and severity scores, allowing security analysts to assess potential risks and prioritise remediation. This review helps identify security weaknesses that could be exploited and supports the process of keeping the endpoint secure through appropriate patching and mitigation.

<img width="2048" height="1536" alt="b62063ad-6377-4831-91a4-88ad05ddfd67" src="https://github.com/user-attachments/assets/cc54219f-99e3-4a12-9dfe-86f317cdefb7" />


## Key Skills Demonstrated

- Security Monitoring
- Incident Detection and Investigation
- SIEM Analysis
- Endpoint Security
- Alert Analysis
- Process Investigation
- Microsoft Sentinel
- Microsoft Defender
- Vulnerability Awareness
- Security Documentation

## Conclusion

This project demonstrates my practical experience investigating security alerts within a SOC environment. The investigation involved reviewing suspicious PowerShell activity, analysing alerts and entities, investigating the affected endpoint and reviewing potential security risks.

The project helped strengthen my understanding of the SOC investigation lifecycle and the process of analysing and responding to suspicious security events.
