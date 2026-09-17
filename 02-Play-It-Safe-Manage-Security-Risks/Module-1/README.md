# Course 2: Play It Safe - Manage Security Risks

**Certification:** Google Cybersecurity Professional Certificate
**Module 1:** Security Domains & Risk Management
**Status:** Complete

---

## 🛠️ Module Overview
This module explores the core principles of organizational cybersecurity, focusing on the 8 CISSP Security Domains, risk management frameworks (including NIST RMF), security audits, and common tools. It details how security professionals categorize assets, manage threats, risks, and vulnerabilities, analyze the layers of the web, and respond to operational, financial, and reputational security impacts.

---

## 🛡️ The 8 CISSP Security Domains

### 1. Security and Risk Management
* **Focus:** Defining security goals, risk mitigation, compliance, business continuity, and legal regulations.
* **Key Concepts:**
  * **Risk Mitigation:** Implementing rules, policies, and controls to quickly reduce the impact of security risks.
  * **Business Continuity:** Establishing disaster recovery plans to maintain operational productivity during an incident.
  * **Core InfoSec Processes:** Incident response, vulnerability management, application security, cloud security, and infrastructure security.

### 2. Asset Security
* **Focus:** Securing digital and physical assets throughout their storage, maintenance, retention, and destruction lifecycle.
* **Key Practices:**
  * Safeguard sensitive data categories like **PII** (Personally Identifiable Information) and **SPII**.
  * Enforce physical destruction policies for hardware (e.g., supervising hard drive shredding).
  * Conduct security impact analyses, establish recovery plans, and manage data backup protocols.

### 3. Security Architecture and Engineering
* **Focus:** Optimizing security using effective tools, systems, and engineering principles.
* **Key Principles:**
  * **Shared Responsibility:** Active role taken by all individuals to maintain physical and virtual security.
  * **Design Principles:** Least privilege, defense in depth, fail securely, separation of duties, keep it simple, threat modeling, and zero trust.
  * **SIEM Implementation:** Monitoring flags for suspicious activity or abnormal user logins.

### 4. Communication and Network Security
* **Focus:** Managing and securing physical networks, cloud environments, and remote access channels.
* **Key Practices:**
  * Protecting remote workers connecting via public Wi-Fi or insecure Bluetooth connections.
  * Implementing network access controls, encrypted channels, and network segmentation.

### 5. Identity and Access Management (IAM)
* **Focus:** Controlling access and authorization to systems to ensure compliance with security policies.
* **Core Principles:**
  * **Principle of Least Privilege:** Granting only the minimum access necessary to complete tasks.
  * **Accountability:** Eliminating shared administrator accounts to ensure actions can be traced to individual users.
* **4 Pillars of IAM:**
  1. **Identification:** Asserting identity via username, access card, or biometrics.
  2. **Authentication:** Verifying identity using credentials such as passwords or PINs.
  3. **Authorization:** Defining access levels based on user roles.
  4. **Accountability:** Logging and monitoring user activity to verify proper system use.

### 6. Security Assessment and Testing
* **Focus:** Testing security controls, analyzing security data, and conducting audits.
* **Key Practices:**
  * Performing vulnerability scans and penetration testing (pen testing).
  * Auditing user permission levels to validate appropriate access controls.
  * Evaluating control efficiency and implementing multi-factor authentication (MFA).

### 7. Security Operations
* **Focus:** Conducting investigations, managing active incidents, and enforcing preventive measures.
* **Core Tools & Practices:**
  * Utilizing **SIEM** tools, intrusion detection/prevention systems, and central log management.
  * Executing incident response **Playbooks** and conducting post-breach digital forensics.
  * Analyzing post-incident lessons learned to update security controls.

### 8. Software Development Security
* **Focus:** Embedding secure coding practices into every phase of the Software Development Lifecycle (SDLC).
* **Key Practices:**
  * Performing secure design reviews during design and secure code reviews during development.
  * Executing penetration testing before software deployment.
  * Configuring robust encryption for databases, web applications, and medical/IoT devices storing sensitive data.

---

## ⚠️ Navigating Threats, Risks, and Vulnerabilities

### Core Definitions
* **Asset:** Any item of value to an organization (e.g., PII, office space, intellectual property, hardware).
* **Threat:** Any circumstance or event with the potential to negatively impact assets (e.g., phishing, social engineering, APTs).
* **Vulnerability:** A weakness in a system, process, or user that can be exploited by a threat.
* **Risk:** The likelihood of a threat exploiting a vulnerability to impact the Confidentiality, Integrity, or Availability (CIA Triad) of an asset.
  * **Formula:** Vulnerability + Threat = Risk

### Asset Risk Categorization
* **Low-Risk Assets:** Publicly accessible data (e.g., website content) that causes minimal harm if compromised.
* **Medium-Risk Assets:** Internal non-public data (e.g., unreleased financial reports) that could cause minor financial or reputational damage.
* **High-Risk Assets:** Highly sensitive data (e.g., PII, SPII, intellectual property) protected by regulations, where exposure results in severe operational, legal, or financial consequences.

### Risk Management Strategies
* **Acceptance:** Acknowledging risk without intervention to preserve normal business operations.
* **Avoidance:** Modifying plans to eliminate exposure to a specific risk.
* **Transference:** Shifting risk management responsibility to a third party (e.g., insurance, vendors).
* **Mitigation:** Implementing technical or administrative controls to reduce risk severity.

---

## 🌐 The 3 Layers of the Web
* **Surface Web:** Standard web pages indexed by commercial search engines and accessible to the public.
* **Deep Web:** Unindexed content requiring authentication/authorization (e.g., medical records, private intranets, online banking).
* **Dark Web:** Encrypted overlay networks requiring specialized routing software (e.g., Tor), frequently used by threat actors to traffic stolen PII and malware.

---

## 🔄 NIST Risk Management Framework (RMF) Steps
1. **Prepare:** Conduct pre-breach planning to identify risks and determine appropriate controls.
2. **Categorize:** Classify systems and data based on potential impact to the CIA Triad.
3. **Select:** Choose, customize, and document controls required to protect organizational assets.
4. **Implement:** Execute security plans and deploy technical/administrative controls.
5. **Assess:** Evaluate whether controls are operating correctly and producing desired results.
6. **Authorize:** Senior leadership accepts accountability for remaining system and privacy risks.
7. **Monitor:** Continuously track system changes, operational health, and emerging risks.
