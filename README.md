  # Hi, I'm Brandon! 👋

## 🏆 Certifications
 

* **[Microsoft Certified: Identity and Access Administrator Associate (SC-300)](https://learn.microsoft.com/api/credentials/share/en-us/BrandonBellamy-9512/E222246BBE6606E5?sharingId=B679C7FBE6A42B51)**  
---

  ## 🛠️ Identity & Access Management (IAM) Skill Stack

### 🆔 Identity Governance & Zero Trust Architecture (IGA)
* **Lifecycle Workflows & Automated Provisioning:** Designing and deploying automated Joiner-Mover-Leaver (JML) pipelines within Microsoft Entra ID to orchestrate secure employee lifecycle transitions at scale. *(Implemented in: Automated Identity Governance Lab)*
* **API Orchestration & Serverless Integration:** Integrating native identity governance frameworks with serverless Azure Logic Apps via secure webhooks; formulating custom expressions to parse JSON payloads and programmatically query the Microsoft Graph API. *(Implemented in: Automated Identity Governance Lab)*
* **Privileged Identity Management (PIM):** Engineering a Zero Trust, least-privilege posture by configuring time-bound Just-In-Time (JIT) role activations, mandatory MFA step-up challenges, and justification auditing for high-privilege directory roles. *(Implemented in: Entra ID PIM Project)*
* **Conditional Access Architecture:** Designing context-aware Zero Trust security policies—specifically deploying and testing `CA-Guest-All-APPS-Req-MFA` to restrict corporate resource access based on identity risk and platform signals. *(Implemented in: Entra ID Guest Access Project)*

### 📊 Cloud Security Operations & Threat Hunting
* **SIEM Pipeline Engineering:** Configuring diagnostic log-streaming pipelines from Microsoft Entra ID into centralized Log Analytics Workspaces to establish full tenant visibility. *(Implemented in: Microsoft Sentinel SIEM Project)*
* **KQL Threat Hunting:** Engineering custom Kusto Query Language (KQL) scripts to monitor identity risk tiers and analyze sign-in logs, specifically isolating password-validation errors (ResultType `50126`) to detect brute-force or credential-stuffing strings. *(Implemented in: Microsoft Sentinel SIEM Project)*

### 🔑 Core Identity Infrastructure & Technical Support Operations
* **Directory Administration & Hybrid Sync:** Designing Active Directory Domain Services (AD DS) structures, configuring Organizational Units (OUs), utilizing PowerShell scripting to automate bulk identity provisioning, and managing hybrid identity synchronization via Entra ID Connect.
* **ITSM & Support Operations Automation:** Utilizing Zendesk enterprise sandboxes to manage, document, and resolve complex technical support lifecycles; designing automated macros to streamline high-volume identity workflows (MFA registration, password resets) while strictly enforcing organizational SLAs.

---

 ## 👨‍💻 Enterprise Identity & Access Management (IAM) Projects
### 🆔 [Enterprise Identity-as-Code & GitOps Pipeline Automation](https://github.com/brandonbellamy400-maker/entra-id-gitops)
**Tech Stack:** `Terraform` | `GitHub Actions` | `OpenID Connect (OIDC)` | `Microsoft Entra ID` | `Azure DevSecOps`
* **Objective:** Designed and deployed a declarative, zero-trust GitOps automation pipeline to completely codify enterprise identity infrastructure and eliminate manual configuration drift.
* **Impact:** Established a secure, passwordless OpenID Connect (OIDC) cryptographic federation trust between GitHub Actions and Microsoft Entra ID. Engineered a multi-stage CI/CD pipeline that validates configurations via pull requests and applies directory modifications automatically upon approved merges, eliminating the risk of static client secret leaks.
* **Skills Verified:** Identity-as-Code (IaC), DevSecOps Pipelines, Zero-Trust Architecture, Microsoft Graph API Scoping, Secure State Management.
  ### 🆔 [Automated Identity Governance & API Orchestration technical project](https://github.com/brandonbellamy400-maker/entra-lifecycle-workflows-automation)
**Tech Stack:** `Entra ID Lifecycle Workflows` | `Azure Logic Apps` | `Microsoft Graph API` | `JSON Automation`
* **Objective:** Engineered an event-driven Identity Governance and Administration (IGA) pipeline to eliminate the security exposure window during employee termination cycles.
* **Impact:** Integrated Microsoft Entra ID Lifecycle Workflows with a serverless Azure Standard Logic App via secure webhooks. Formulated custom expressions to parse JSON payloads and dynamically query the Microsoft Graph API, programmatically extracting and routing manager metadata in real-time while forcefully revoking active user authentication sessions.
* **Skills Verified:** Identity Governance (IGA), Azure Logic Apps, API Integration, Microsoft Graph Triage, Log Diagnostics.

---

  ### 📊 [Microsoft Sentinel SIEM & Identity Threat Hunting Project](https://github.com/brandonbellamy400-maker/microsoft-sentinel-threat-hunting)
**Tech Stack:** `Microsoft Sentinel` | `Kusto Query Language (KQL)` | `Log Analytics` | `Entra ID Protection`

* **Objective:** Streamed Microsoft Entra ID diagnostic data to a centralized Log Analytics Workspace to detect and analyze identity-based attacks.
* **Impact:** Engineered custom KQL (Kusto Query Language) hunting queries to isolate and aggregate credential-stuffing and brute-force patterns (ResultType `50126`), exposing malicious actor IPs before initial access was achieved.
* **Skills Verified:** SIEM Management, Log Ingestion Pipelines, KQL Threat Hunting, Incident Response.

---

   ### 🔐 [Entra ID: Implementing Privileged Identity Management,implementing JIT Access (PIM)](https://github.com/brandonbellamy400-maker/entra-pim-lab)
**Tech Stack:** `Privileged Identity Management (PIM)` | `Just-In-Time (JIT) Access` | `Identity Governance` | `Audit Logs`
* **Objective:** Moved away from high-privilege permanent role assignments in the BRANDONTECH environment toward a Zero Trust model using Just-In-Time (JIT) access.
* **Impact:** Transformed standing administrative roles (like Security Administrator) into time-bound, eligible assignments requiring explicit MFA verification and justification logging, drastically shrinking the tenant's attack surface.
* **Skills Verified:** Privileged Identity Management (PIM), Just-In-Time (JIT) Access, Identity Governance, Audit Logging & Compliance.

---

  ### 🛡️ [Entra ID: Zero Trust Guest Access Implementation](https://github.com/brandonbellamy400-maker/-entra-conditional-access-lab)
**Tech Stack:** `Microsoft Entra ID` | `Conditional Access` | `Multi-Factor Authentication (MFA)` | `Zero Trust`

* **Objective:** Enforced a robust Zero Trust framework by deploying a specialized security policy (`CA-Guest-All-APPS-Req-MFA`).
* **Impact:** Mitigated unauthorized access risks by demanding mandatory Multi-Factor Authentication (MFA) for all guest identities trying to access internal organizational resources.
* **Skills Verified:** Conditional Access, Grant Controls, Sign-in Log Analysis, Zero Trust Architecture.

---

 ### 🔑 [Active Directory Home Lab (AWS)](https://github.com/brandonbellamy400-maker/-active-directory-lab)
**Tech Stack:** `Active Directory (AD DS)` | `Azure Virtual Networks` | `PowerShell Scripting` | `Hybrid Identity`
* **Objective:** Built a scalable sandbox infrastructure inside Amazon Web Services (AWS) to simulate a modern corporate directory infrastructure.
* **Impact:** Created a secure environment to test group policies, tenant syncing, and local-to-cloud security mapping using PowerShell automation for bulk user simulation.
* **Skills Verified:** Active Directory Domain Services (AD DS), Virtual Networks (VNets), PowerShell Automation, IAM Fundamentals.
---

## 🤳 Connect with me:
[![Brandon Bellamy | LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brandon-bellamy-3689803b8/)
 

 
 
