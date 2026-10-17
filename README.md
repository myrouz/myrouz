# Mysha Rouzard | Network Administrator

## **📜 Certifications**

![Microsoft Certified: Azure Fundamentals](https://img.shields.io/badge/Microsoft_Certified-Azure_Fundamentals_(AZ--900)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white)

---
## 🗂️ Portfolio Summary

This portfolio consists of five interconnected labs that simulate an enterprise IT environment and follow the core workflow of a security analyst: identity and access management ➡️ network visibility ➡️ log monitoring and threat detection ➡️ IT service management (ITSM) ➡️ vulnerability management.

Each lab builds on the previous one to demonstrate an end-to-end security operations workflow, from infrastructure deployment and network analysis to threat detection, incident tracking, and vulnerability remediation. The environment was established using Active Directory, normal network traffic was analyzed with Wireshark, simulated security events were investigated in Splunk, operational workflows were managed through ServiceNow, and vulnerabilities were identified, remediated, and verified using Nessus.

Collectively, these labs demonstrate foundational competencies in system administration, cloud infrastructure, network analysis, security monitoring, IT service management, and vulnerability management. Together, they illustrate how enterprise technologies integrate to support operational efficiency, threat detection, incident response, and continuous security improvement.

---

## 🧰 Lab Toolkit

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active%20Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-81B5A1?style=for-the-badge&logo=servicenow&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-00C1DE?style=for-the-badge&logo=tenable&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

----
## 💼 Featured Projects

## 🔐 Lab 1 — Active Directory Deployment

**Built the identity backbone for a small enterprise network in the cloud.**

Bottom Line Up Front: Build an enterprise identity backbone by promoting a Windows Server 2025 instance to a Domain Controller (lab.local), configuring an Organizational Unit (OU) structure, creating role-based security groups, provisioning user accounts via PowerShell scripts, and enforcing system configurations centrally using Group Policy Objects (GPOs). 

Core Value: Grants practical mastery over the foundational tool used for identity and access management across on-premises and hybrid cloud enterprise environments.

**Tools:** `Azure` `Windows Server` `Active Directory` `Group Policy`

🔗 [View Repository → https://github.com/myrouz/Lab-1-Active-Directory-Domain-Services-on-Azure](https://github.com/myrouz/Lab-1-Active-Directory-Domain-Services-on-Azure)

----

## 📡 Lab 2 — Network Traffic Analysis with Wireshark

**Turned raw packet captures into a plain-language picture of what happens on the wire.**

**Bottom Line Up Front:** Capture live raw network data using Wireshark, apply precise display filters (dns, http, tcp), investigate the steps of the TCP three-way handshake, analyze DNS lookup queries, trace cleartext credentials in unencrypted HTTP traffic, and reconstruct full TCP application streams.   

**Core Value:** Provides the hands-on diagnostic and packet-inspection skills required by network engineers and security analysts to troubleshoot connectivity failures and investigate security incidents.   

**Tools:** `Wireshark`

🔗 [View Repository → https://github.com/myrouz/Lab-2-WireShark-and-Network-Analysis](https://github.com/myrouz/Lab-2-WireShark-and-Network-Analysis)

----

## 📊 Lab 3 — SIEM Implementation with Splunk

**Detected simulated attacks in real time using centralized log monitoring.**

**Bottom Line Up Front:** Deploy a Splunk SIEM instance on Ubuntu, configure a Universal Forwarder on your Windows Server to stream Windows Event Logs over encrypted port 9997, write custom Splunk Processing Language (SPL) queries to isolate authentication activity, build operational security dashboards, and automate threat detection using scheduled alerts.  

**Core Value:** Develops essential Security Operations Center (SOC) capabilities for centralized log management, anomaly investigation, and scalable, continuous security monitoring.

**Tools:** `Splunk` `Linux` `Windows Event Logs`

🔗 [View Repository → https://github.com/myrouz/Lab-3-Splunk-SIEM-And-Log-Analysis](https://github.com/myrouz/Lab-3-Splunk-SIEM-And-Log-Analysis)

----

## 🎟️ Lab 4 — ITSM Workflow with ServiceNow

**Simulated how an IT department coordinates day-to-day operations, from the first request to final resolution.**

**Bottom Line Up Front:** Navigate a ServiceNow Personal Developer Instance (PDI) to manage the full ITIL lifecycle, including incident creation and resolution, priority and SLA calculations, self-service item development within the Service Catalog, automated change-management approval workflows, and analytical reporting.

**Core Value:** Introduces the standard enterprise IT Service Management platform used universally to track, route, and audit operational IT workflows.   

**Tools:** `ServiceNow`

🔗 [View Repository → https://github.com/myrouz/Lab-4-ServiceNow-ITSM-Information-Technology-Service-Management](https://github.com/myrouz/Lab-4-ServiceNow-ITSM-Information-Technology-Service-Management)

----

## 🛡️ **Lab 5 — Vulnerability Management with Nessus**

**Bottom Line Up Front:** Deploy Nessus Essentials, execute unauthenticated network discovery scans, conduct credentialed internal vulnerability assessments using administrative domain credentials, identify underlying operating system weaknesses, interpret Common Vulnerability Scoring System (CVSS) metrics, and complete the patching and verification remediation cycle.

**Core Value:** Develops proficiency in the industry-standard vulnerability management lifecycle, including security exposure identification, risk-based prioritization, and remediation to reduce the risk of exploitation.

**Tools:** `Nessus` `Azure` `Linux` `PowerShell`

🔗 [View Repository → https://github.com/myrouz/Lab-5-Nessus-Vulnerability-Scanning](https://github.com/myrouz/Lab-5-Nessus-Vulnerability-Scanning)

---

##  **Final Takeaway**

These five labs demonstrate how enterprise infrastructure, network visibility, centralized logging, IT service management, and vulnerability management work together to support a secure and operationally resilient environment. Through hands-on implementation, configuration, investigation, and remediation, this portfolio showcases foundational technical skills applicable to system administration, cloud operations, network security, and Security Operations Center (SOC) analysis.

The overall objective was to move beyond individual tools and understand how each technology contributes to the broader security lifecycle—from establishing secure access and identifying suspicious activity to documenting incidents, prioritizing risks, and validating remediation. This portfolio establishes a practical foundation for continued development in enterprise IT operations, threat detection, incident response, and defensive security.
