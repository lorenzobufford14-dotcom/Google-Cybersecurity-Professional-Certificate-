# Course 2: Play It Safe - Manage Security Risks

**Certification:** Google Cybersecurity Professional Certificate
**Module 1:** Security Domains & Risk Management
**Status:** Complete

---

## 🛠️ Module Overview
This module explores the core principles of organizational cybersecurity, focusing on the 8 CISSP Security Domains, risk management frameworks (including NIST RMF), security audits, and common tools[span_0](start_span)[span_0](end_span). It details how security professionals categorize assets, manage threats, risks, and vulnerabilities, analyze the layers of the web, and respond to operational, financial, and reputational security impacts[span_1](start_span)[span_1](end_span).

---

## 🛡️ The 8 CISSP Security Domains

### 1. Security and Risk Management
* **Focus:** Defining security goals, risk mitigation, compliance, business continuity, and legal regulations[span_2](start_span)[span_2](end_span).
* **Key Concepts:**
  * **Risk Mitigation:** Implementing rules, policies, and controls to quickly reduce the impact of security risks[span_3](start_span)[span_3](end_span).
  * **Business Continuity:** Establishing disaster recovery plans to maintain operational productivity during an incident[span_4](start_span)[span_4](end_span).
  * **Core InfoSec Processes:** Incident response, vulnerability management, application security, cloud security, and infrastructure security[span_5](start_span)[span_5](end_span).

### 2. Asset Security
* **Focus:** Securing digital and physical assets throughout their storage, maintenance, retention, and destruction lifecycle[span_6](start_span)[span_6](end_span).
* **Key Practices:**
  * Safeguard sensitive data categories like **PII** (Personally Identifiable Information) and **SPII**[span_7](start_span)[span_7](end_span).
  * Enforce physical destruction policies for hardware (e.g., supervising hard drive shredding)[span_8](start_span)[span_8](end_span).
  * Conduct security impact analyses, establish recovery plans, and manage data backup protocols[span_9](start_span)[span_9](end_span).

### 3. Security Architecture and Engineering
* **Focus:** Optimizing security using effective tools, systems, and engineering principles[span_10](start_span)[span_10](end_span).
* **Key Principles:**
  * **Shared Responsibility:** Active role taken by all individuals to maintain physical and virtual security[span_11](start_span)[span_11](end_span).
  * **Design Principles:** Least privilege, defense in depth, fail securely, separation of duties, keep it simple, threat modeling, and zero trust[span_12](start_span)[span_12](end_span).
  * **SIEM Implementation:** Monitoring flags for suspicious activity or abnormal user logins[span_13](start_span)[span_13](end_span).

### 4. Communication and Network Security
* **Focus:** Managing and securing physical networks, cloud environments, and remote access channels[span_14](start_span)[span_14](end_span).
* **Key Practices:**
  * Protecting remote workers connecting via public Wi-Fi or insecure Bluetooth connections[span_15](start_span)[span_15](end_span).
  * Implementing network access controls, encrypted channels, and network segmentation[span_16](start_span)[span_16](end_span).

### 5. Identity and Access Management (IAM)
* **Focus:** Controlling access and authorization to systems to ensure compliance with security policies[span_17](start_span)[span_17](end_span).
* **Core Principles:**
  * **Principle of Least Privilege:** Granting only the minimum access necessary to complete tasks[span_18](start_span)[span_18](end_span).
  * **Accountability:** Eliminating shared administrator accounts to ensure actions can be traced to individual users[span_19](start_span)[span_19](end_span).
* **4 Pillars of IAM:**
  1. **Identification:** Asserting identity via username, access card, or biometrics[span_20](start_span)[span_20](end_span).
  2. **Authentication:** Verifying identity using credentials such as passwords or PINs[span_21](start_span)[span_21](end_span).
  3. **Authorization:** Defining access levels based on user roles[span_22](start_span)[span_22](end_span).
  4. **Accountability:** Logging and monitoring user activity to verify proper system use[span_23](start_span)[span_23](end_span).

### 6. Security Assessment and Testing
* **Focus:** Testing security controls, analyzing security data, and conducting audits[span_24](start_span)[span_24](end_span).
* **Key Practices:**
  * Performing vulnerability scans and penetration testing (pen testing)[span_25](start_span)[span_25](end_span).
  * Auditing user permission levels to validate appropriate access controls[span_26](start_span)[span_26](end_span).
  * Evaluating control efficiency and implementing multi-factor authentication (MFA)[span_27](start_span)[span_27](end_span).

### 7. Security Operations
* **Focus:** Conducting investigations, managing active incidents, and enforcing preventive measures[span_28](start_span)[span_28](end_span).
* **Core Tools & Practices:**
  * Utilizing **SIEM** tools, intrusion detection/prevention systems, and central log management[span_29](start_span)[span_29](end_span).
  * Executing incident response **Playbooks** and conducting post-breach digital forensics[span_30](start_span)[span_30](end_span).
  * Analyzing post-incident lessons learned to update security controls[span_31](start_span)[span_31](end_span).

### 8. Software Development Security
* **Focus:** Embedding secure coding practices into every phase of the Software Development Lifecycle (SDLC)[span_32](start_span)[span_32](end_span).
* **Key Practices:**
  * Performing secure design reviews during design and secure code reviews during development[span_33](start_span)[span_33](end_span).
  * Executing penetration testing before software deployment[span_34](start_span)[span_34](end_span).
  * Configuring robust encryption for databases, web applications, and medical/IoT devices storing sensitive data[span_35](start_span)[span_35](end_span).

---

## ⚠️ Navigating Threats, Risks, and Vulnerabilities

### Core Definitions
* **Asset:** Any item of value to an organization (e.g., PII, office space, intellectual property, hardware)[span_36](start_span)[span_36](end_span).
* **Threat:** Any circumstance or event with the potential to negatively impact assets (e.g., phishing, social engineering, APTs)[span_37](start_span)[span_37](end_span).
* **Vulnerability:** A weakness in a system, process, or user that can be exploited by a threat[span_38](start_span)[span_38](end_span).
* **Risk:** The likelihood of a threat exploiting a vulnerability to impact the Confidentiality, Integrity, or Availability (CIA Triad) of an asset[span_39](start_span)[span_39](end_span).
  * **Formula:** $\text{Vulnerability} + \text{Threat} = \text{Risk}$[span_40](start_span)[span_40](end_span)

### Asset Risk Categorization
* **Low-Risk Assets:** Publicly accessible data (e.g., website content) that causes minimal harm if compromised[span_41](start_span)[span_41](end_span).
* **Medium-Risk Assets:** Internal non-public data (e.g., unreleased financial reports) that could cause minor financial or reputational damage[span_42](start_span)[span_42](end_span).
* **High-Risk Assets:** Highly sensitive data (e.g., PII, SPII, intellectual property) protected by regulations, where exposure results in severe operational, legal, or financial consequences[span_43](start_span)[span_43](end_span).

### Risk Management Strategies
* **Acceptance:** Acknowledging risk without intervention to preserve normal business operations[span_44](start_span)[span_44](end_span).
* **Avoidance:** Modifying plans to eliminate exposure to a specific risk[span_45](start_span)[span_45](end_span).
* **Transference:** Shifting risk management responsibility to a third party (e.g., insurance, vendors)[span_46](start_span)[span_46](end_span).
* **Mitigation:** Implementing technical or administrative controls to reduce risk severity[span_47](start_span)[span_47](end_span).

---

## 🌐 The 3 Layers of the Web
* **Surface Web:** Standard web pages indexed by commercial search engines and accessible to the public[span_48](start_span)[span_48](end_span).
* **Deep Web:** Unindexed content requiring authentication/authorization (e.g., medical records, private intranets, online banking)[span_49](start_span)[span_49](end_span).
* **Dark Web:** Encrypted overlay networks requiring specialized routing software (e.g., Tor), frequently used by threat actors to traffic stolen PII and malware[span_50](start_span)[span_50](end_span).

---

## 🔄 NIST Risk Management Framework (RMF) Steps
1. **Prepare:** Conduct pre-breach planning to identify risks and determine appropriate controls[span_51](start_span)[span_51](end_span).
2. **Categorize:** Classify systems and data based on potential impact to the CIA Triad[span_52](start_span)[span_52](end_span).
3. **Select:** Choose, customize, and document controls required to protect organizational assets[span_53](start_span)[span_53](end_span).
4. **Implement:** Execute security plans and deploy technical/administrative controls[span_54](start_span)[span_54](end_span).
5. **Assess:** Evaluate whether controls are operating correctly and producing desired results[span_55](start_span)[span_55](end_span).
6. **Authorize:** Senior leadership accepts accountability for remaining system and privacy risks[span_56](start_span)[span_56](end_span).
7. **Monitor:** Continuously track system changes, operational health, and emerging risks[span_57](start_span)[span_57](end_span).
