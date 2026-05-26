  # Hi, I'm Brandon! 👋

## 🏆 Certifications
 

* **[Microsoft Certified: Identity and Access Administrator Associate (SC-300)](https://learn.microsoft.com/api/credentials/share/en-us/BrandonBellamy-9512/E222246BBE6606E5?sharingId=B679C7FBE6A42B51)** * *Credential ID: E222246BBE6606E5 | Active (Earned: May 20, 2026)*
---

 ## 🛠️ Identity & Access Management (IAM) Skill Stack

 ### 🔑 Identity & Access Management
* **Directory Administration:** Designing and deploying Active Directory Domain Services (AD DS) within Azure Virtual Networks, configuring Organizational Units (OUs), and automating bulk user provisioning via PowerShell scripts.
* **Modern Authentication:** Enforcing tenant-wide Multi-Factor Authentication (MFA), passwordless methods, and managing external collaboration structures for B2B/Guest identities.
* **Conditional Access Architecture:** Engineering context-aware Zero Trust security policies—specifically deploying and testing `CA-Guest-All-APPS-Req-MFA` to restrict resource access based on identity risk and platform signals.
 ### 🛡️ Identity Governance & Workload Security
* **Lifecycle Workflows & Automation:** Engineering automated joiner-mover-leaver (JML) processes using Microsoft Entra ID Lifecycle Workflows; configuring event-driven triggers and custom task execution to manage identity lifecycles at scale.
* **API Orchestration & Serverless Integration:** Integrating native governance workflows with serverless Azure Logic Apps using secure webhooks; formulating custom expressions to parse JSON payloads and execute targeted actions.
* **Privileged Identity Management (PIM):** Enforcing a Zero Trust least-privilege posture by configuring time-bound Just-In-Time (JIT) role activations, mandatory multi-factor authentication (MFA) step-up challenges, and justification auditing for high-privilege roles.

 ### 📊 Security Operations & Automation
* **SIEM Pipeline Engineering:** Configuring diagnostic log-streaming pipelines from Microsoft Entra ID into centralized Log Analytics Workspaces to establish full visibility over identity infrastructure.
* **KQL Threat Hunting:** Engineering custom Kusto Query Language (KQL) scripts to monitor identity risk tiers and analyze sign-in logs, specifically isolating password-validation errors (ResultType `50126`) to identify active brute-force or credential-stuffing strings.
* **Directory Automation:** Utilizing PowerShell scripting to automate bulk identity provisioning within sandbox infrastructure, deploy standardized security policies, and extract audit logs for administrative compliance reviews.

---

 ## 👨‍💻 Enterprise Identity & Access Management (IAM) Projects

 ### 📊 [Microsoft Sentinel SIEM & Identity Threat Hunting Lab](https://github.com/brandonbellamy400-maker/microsoft-sentinel-threat-hunting)
**Tech Stack:** `Microsoft Sentinel` | `Kusto Query Language (KQL)` | `Log Analytics` | `Entra ID Protection`
* **Objective:** Streamed Microsoft Entra ID diagnostic data to a centralized Log Analytics Workspace to detect and analyze identity-based attacks.
* **Impact:** Engineered custom KQL (Kusto Query Language) hunting queries to isolate and aggregate credential-stuffing and brute-force patterns (ResultType `50126`), exposing malicious actor IPs before initial access was achieved.
* **Skills Verified:** SIEM Management, Log Ingestion Pipelines, KQL Threat Hunting, Incident Response.

---

 ### 🛡️ [Entra ID: Zero Trust Guest Access Implementation](https://github.com/brandonbellamy400-maker/-entra-conditional-access-lab)
**Tech Stack:** `Microsoft Entra ID` | `Conditional Access` | `Multi-Factor Authentication (MFA)` | `Zero Trust`
* **Objective:** Enforced a robust Zero Trust framework by deploying a specialized security policy (`CA-Guest-All-APPS-Req-MFA`).
* **Impact:** Mitigated unauthorized access risks by demanding mandatory Multi-Factor Authentication (MFA) for all guest identities trying to access internal organizational resources.
* **Skills Verified:** Conditional Access, Grant Controls, Sign-in Log Analysis, Zero Trust Architecture.

---

 ### 🆔 [Automated Identity Governance & API Orchestration Lab](https://github.com/brandonbellamy400-maker/entra-lifecycle-workflows-automation)
**Tech Stack:** `Entra ID Lifecycle Workflows` | `Azure Logic Apps` | `Microsoft Graph API` | `JSON Automation`
* **Objective:** Engineered an event-driven Identity Governance and Administration (IGA) pipeline to eliminate the security exposure window during employee termination cycles.
* **Impact:** Integrated Microsoft Entra ID Lifecycle Workflows with a serverless Azure Standard Logic App via secure webhooks. Formulated custom expressions to parse JSON payloads and dynamically query the Microsoft Graph API, programmatically extracting and routing manager metadata in real-time while forcefully revoking active user authentication sessions.
* **Skills Verified:** Identity Governance (IGA), Azure Logic Apps, API Integration, Microsoft Graph Triage, Log Diagnostics.
---

 ### 🔐 [Entra ID: Implementing Privileged Identity Management (PIM)](https://github.com/brandonbellamy400-maker/entra-pim-lab)
**Tech Stack:** `Privileged Identity Management (PIM)` | `Just-In-Time (JIT) Access` | `Identity Governance` | `Audit Logs`
* **Objective:** Moved away from high-privilege permanent role assignments in the BRANDONTECH environment toward a Zero Trust model using Just-In-Time (JIT) access.
* **Impact:** Transformed standing administrative roles (like Security Administrator) into time-bound, eligible assignments requiring explicit MFA verification and justification logging, drastically shrinking the tenant's attack surface.
* **Skills Verified:** Privileged Identity Management (PIM), Just-In-Time (JIT) Access, Identity Governance, Audit Logging & Compliance.

---

 ### 🔑 [Active Directory Home Lab (Azure)](https://github.com/brandonbellamy400-maker/-active-directory-lab)
**Tech Stack:** `Active Directory (AD DS)` | `Azure Virtual Networks` | `PowerShell Scripting` | `Hybrid Identity`
* **Objective:** Built a scalable sandbox infrastructure inside Microsoft Azure to simulate a modern corporate directory infrastructure.
* **Impact:** Created a secure environment to test group policies, tenant syncing, and local-to-cloud security mapping using PowerShell automation for bulk user simulation.
* **Skills Verified:** Active Directory Domain Services (AD DS), Virtual Networks (VNets), PowerShell Automation, IAM Fundamentals.
---

## 🤳 Connect with me:
[![Brandon Bellamy | LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brandon-bellamy-3689803b8/)
 

 
 
