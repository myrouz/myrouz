# Mysha Rouzard | Network Operations Administrator 


## 👋 About Me

The most valuable technical experience comes from hands-on execution, working through real-world challenges, and understanding how technical decisions affect the broader enterprise.

I document my projects to reinforce what I learn, share practical experience, and build a portfolio that shows how I apply IT and cybersecurity principles. My goal for every project and guide is simple: clear, structured documentation that gives engineers actionable guidance and gives decision-makers the clarity to make informed security and business decisions.

I bring 5+ years of experience in help desk leadership, enterprise IT operations, and cybersecurity, supporting large-scale environments. I'm open to opportunities across IT and cybersecurity where I can build on that experience, deepen my skills in cloud infrastructure, identity and access management, and vulnerability management, and contribute to meaningful technical work.

I look forward to expanding my portfolios with more lab projects and continuing to share what I learn along the way!

## **📜 Certifications**

![Microsoft Certified: Azure Fundamentals](https://img.shields.io/badge/Microsoft_Certified-Azure_Fundamentals_(AZ--900)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white)

---
## 🗂️ Portfolio Summary

This portfolio consists of five connected, hands-on labs that simulate an enterprise IT environment and follow the core workflow of a security analyst: identity and access management ➡️  network visibility ➡️ log monitoring and threat detection ➡️ IT service management ➡️ and vulnerability management.

Each lab builds on the one before it. I deployed and secured the infrastructure, analyzed its network traffic, detected suspicious activity in the logs, tracked issues as incidents, and then identified, remediated, and verified vulnerabilities.

I used Microsoft Azure to host the lab environment, Active Directory to manage identity and access, Wireshark to analyze network traffic, Splunk to monitor and investigate security events, ServiceNow to manage incidents and service requests, and Nessus to find, fix, and verify vulnerabilities.

Together, these projects demonstrate hands-on experience in system administration, cloud infrastructure, network analysis, SIEM, ITSM, and vulnerability management, while highlighting how these disciplines work together to support the security operations lifecycle.

<img width="1024" height="673" alt="Lab Work Together" src="https://github.com/user-attachments/assets/33977060-3a42-46c3-929b-1a3d74bc27c9" />

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

*Establishing the identity backbone for an enterprise network in the cloud.*

**Bottom Line Up Front:** Deploy Windows Server 2025 as a domain controller for the lab.local domain, configure an Organizational Unit (OU) structure and role-based security groups, automate user provisioning with PowerShell scripts, and enforce centralized system configurations through Group Policy Objects (GPOs).

**Core Value:** Develops practical expertise in Active Directory administration and identity and access management (IAM), foundational to securing and managing identities across on-premises and hybrid cloud enterprise environments.

**Tools:** `Azure` `Windows Server` `Active Directory` `Group Policy`  

🔗 [View Repository → Lab 1: Active Directory Domain Services](https://github.com/myrouz/Lab-1-Active-Directory-Domain-Services-on-Azure)

----

## 📡 Lab 2 — Network Traffic Analysis with Wireshark

*Transforming raw packet captures into actionable insights into network communications.*

**Bottom Line Up Front:** Capture and analyze network traffic using Wireshark, apply targeted display filters (dns, http, tcp), examine the TCP three-way handshake, investigate DNS queries, identify cleartext credentials in unencrypted HTTP traffic, and reconstruct TCP application streams to understand network communications.

**Core Value:** Develops practical packet analysis and network troubleshooting skills essential for diagnosing connectivity issues, understanding network protocols, identifying insecure communications, and investigating potential security incidents.  

**Tools:** `Wireshark`

🔗 [View Repository → Lab 2: Network Traffic Analysis with Wireshark](https://github.com/myrouz/Lab-2-WireShark-and-Network-Analysis)

----

## 📊 Lab 3 — SIEM Implementation with Splunk

*Centralizing security logs to investigate suspicious activity and detect simulated attacks.*

**Bottom Line Up Front:** Deploy a Splunk SIEM instance on Ubuntu, configure a Universal Forwarder on Windows Server to transmit Windows Event Logs over port 9997 with encrypted transport, develop custom Splunk Processing Language (SPL) queries to investigate authentication activity, build security dashboards for operational visibility, and configure scheduled alerts to detect suspicious events.  

**Core Value:** Develops foundational Security Operations Center (SOC) skills in centralized log management, authentication monitoring, anomaly investigation, security event correlation, and automated threat detection to support continuous security monitoring.

**Tools:** `Splunk` `Linux` `Windows Event Logs` `Visio Code`

🔗 [View Repository → Lab 3: Splunk SIEM and Log Analysis](https://github.com/myrouz/Lab-3-Splunk-SIEM-And-Log-Analysis)

----

## 🎟️ Lab 4 — ITSM Workflow with ServiceNow

*Simulating enterprise IT service delivery, from initial request submission to resolution and reporting.*

**Bottom Line Up Front:** Configure and navigate a ServiceNow Personal Developer Instance (PDI) to manage core ITIL workflows, including incident creation and resolution, priority assignment and Service Level Agreement (SLA) tracking, self-service item configuration within the Service Catalog, automated change-management approval workflows, and operational performance reporting.

**Core Value:** Develops practical IT Service Management (ITSM) skills in incident tracking, service request fulfillment, change control, workflow automation, SLA management, and operational reporting using a widely adopted enterprise service management platform.

**Tools:** `ServiceNow`

🔗 [View Repository → Lab 4 — ITSM Workflow with ServiceNow](https://github.com/myrouz/Lab-4-ServiceNow-ITSM-Information-Technology-Service-Management)

----

## 🛡️ Lab 5 — Vulnerability Management with Nessus

*Identifying security weaknesses, prioritizing risk, and validating remediation across enterprise systems.*

**Bottom Line Up Front:** Deploy Nessus Essentials on Ubuntu and provision a Windows virtual machine (VM) as the target for vulnerability scanning. Perform unauthenticated network discovery scans and credentialed vulnerability assessments using administrative domain credentials, identify operating system and configuration weaknesses, interpret Common Vulnerability Scoring System (CVSS) scores to prioritize remediation, and complete the vulnerability management cycle through patching and verification scans.

**Core Value:** Develops practical skills in the vulnerability management lifecycle, including security exposure identification, risk-based prioritization, remediation planning, and verification to reduce exploitable weaknesses and strengthen enterprise security posture.

**Tools:** `Nessus` `Azure` `Linux` `PowerShell`

🔗 [View Repository → Lab 5 — Vulnerability Management with Nessus](https://github.com/myrouz/Lab-5-Nessus-Vulnerability-Scanning)

---

## 🏁 Final Takeaway

Completing these five labs helped me understand that cybersecurity is not simply a collection of separate tools and technologies, but an interconnected process that requires each component to work together. Identity and access management establishes who can access specific resources, network analysis provides visibility into how systems communicate, and SIEM solutions help transform raw log data into meaningful alerts that security teams can investigate. ITSM ensures that identified issues are properly documented, assigned, tracked, and resolved. Vulnerability management completes the process by identifying weaknesses, prioritizing risks, and verifying that corrective actions have been successful.

Building each environment step by step reinforced the importance of establishing strong technical foundations. Even a small configuration error, an unmonitored network segment, or an improperly managed ticket can create security and operational gaps. These experiences demonstrated that having the right tools is only part of an effective security strategy; those tools must also be properly configured, monitored, and integrated into established processes.

Most importantly, this project gave me valuable hands-on experience with the full security operations lifecycle: detect, respond, remediate, and verify. Working through each lab helped me better understand how these processes support one another and how security professionals use them to identify threats, manage vulnerabilities, and maintain a stronger security posture. Overall, the experience strengthened my technical understanding and provided a practical foundation for applying these concepts in real-world cybersecurity environments.


---

## 🤝 Let's Connect

I'm continuously expanding my technical skills through hands-on cybersecurity labs and practical projects, gaining experience in areas such as Identity & Access Management (IAM), SIEM, ITSM, and Vulnerability Management. With over 5 years of IT experience, I'm passionate about growing my expertise, taking on new challenges, and exploring opportunities across IT and cybersecurity.

I'm always open to connecting with IT professionals, recruiters, and others in the industry. Whether it's sharing knowledge, discussing opportunities, or learning from one another, I'd love to connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mysharouzard8b746b16a)
[![Email](https://img.shields.io/badge/Email-Message_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:myrouzard@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/myrouz)

### 💬 Happy to talk about
- Active Directory, Group Policy, and Azure lab builds
- Splunk, ServiceNow, and Nessus workflows
- Collaborating on or reviewing home lab projects

⭐ If you found these labs useful, a star on the repo goes a long way!

