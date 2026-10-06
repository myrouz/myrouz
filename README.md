# Mysha Rouzard | Network Administrator

---

📜 Certifications

![Microsoft Certified: Azure Fundamentals](https://img.shields.io/badge/Microsoft_Certified-Azure_Fundamentals_(AZ--900)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white)

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

Deployed a Windows Server 2025 domain controller in Azure, enforced settings through Group Policy Objects, and joined client machines to the domain. This domain environment serves as the foundation for every subsequent lab in this portfolio.

**Tools:** `Azure` `Windows Server` `Active Directory` `Group Policy`

🔗 [View Repository → https://github.com/myrouz/Lab-1-Active-Directory-Domain-Services-on-Azure](https://github.com/myrouz/Lab-1-Active-Directory-Domain-Services-on-Azure)

----

## 📡 Lab 2 — Network Traffic Analysis with Wireshark

**Turned raw packet captures into a plain-language picture of what happens on the wire.**

Captured live traffic and decoded DNS resolution, the TCP three-way handshake, and the difference between HTTP and HTTPS at the packet level. The write-up shows why encryption matters by comparing readable and unreadable payloads.

**Tools:** `Wireshark`

🔗 [View Repository → https://github.com/myrouz/Lab-2-WireShark-and-Network-Analysis](https://github.com/myrouz/Lab-2-WireShark-and-Network-Analysis)

----

## 📊 Lab 3 — SIEM Implementation with Splunk

**Detected simulated attacks in real time using centralized log monitoring.**

Forwarded Windows event logs to a Splunk Enterprise instance on Linux, then generated realistic security events such as failed logins and account lockouts. Built custom dashboards and alerts to surface those events as they happened.

**Tools:** `Splunk` `Linux` `Windows Event Logs`

🔗 [View Repository → https://github.com/myrouz/Lab-3-Splunk-SIEM-And-Log-Analysis](https://github.com/myrouz/Lab-3-Splunk-SIEM-And-Log-Analysis)

----

## 🎟️ Lab 4 — ITSM Workflow with ServiceNow

**Simulated how an IT department coordinates day-to-day operations, from the first request to final resolution.**

Worked through the full incident lifecycle in a ServiceNow Personal Developer Instance, including service catalog requests and change management. Added reporting dashboards to track ticket activity.

**Tools:** `ServiceNow`

🔗 [View Repository → https://github.com/myrouz/Lab-4-ServiceNow-ITSM-Information-Technology-Service-Management](https://github.com/myrouz/Lab-4-ServiceNow-ITSM-Information-Technology-Service-Management)

----

## 🛡️ **Lab 5 — Vulnerability Management with Nessus**

Took a vulnerability from detection to verified fix.

Deployed Nessus on an Azure Ubuntu Server VM and scanned for weaknesses, which flagged CVE-2013-3900. Remediated it with a PowerShell script that sets the required registry value in both the 64-bit and WOW64 (32-bit) paths, then confirmed the finding was resolved.

**Tools:** `Nessus` `Azure` `Linux` `PowerShell`

🔗 [View Repository → https://github.com/myrouz/Lab-5-Nessus-Vulnerability-Scanning](https://github.com/myrouz/Lab-5-Nessus-Vulnerability-Scanning)

---
Portfolio Summary
--- 

This portfolio consists of five labs that follow the core workflow of a security analyst: identity and access ➡️ network visibility ➡️ log monitoring ➡️ ITSM process ➡️ and vulnerability management.

Each lab builds on the one before it. I built the environment, learned what normal traffic looks like, detected simulated attacks in Splunk, tracked the work through ServiceNow, and closed the loop by finding, fixing, and verifying a vulnerability.

