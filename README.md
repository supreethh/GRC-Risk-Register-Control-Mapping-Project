# GRC Risk Register & ISO 27001 Control Mapping Project

## Overview

This project demonstrates a practical Governance, Risk, and Compliance (GRC) risk assessment for a simulated SaaS web application environment. The objective was to identify key security risks, evaluate their potential business impact, assess existing controls, and prioritize mitigation actions using a structured risk register aligned with ISO/IEC 27001.

The risk scenarios were informed by authentication abuse and system behavior identified during a separate SOC-style log analysis project, creating a realistic linkage between security operations and governance-based risk management.

---

## Environment Scope

The simulated organization operates a cloud-hosted web application including:

- User authentication and session management systems  
- Administrative management portal with elevated privileges  
- Cloud-hosted application servers and infrastructure  
- Centralized logging and monitoring platform  
- Identity and access management processes  
- Incident response workflows  

---

## Risk Assessment Methodology

Each identified risk was evaluated using a structured risk management approach:

- **Likelihood (1–5):** Probability of occurrence  
- **Impact (1–5):** Business, operational, and security impact  
- **Inherent Risk Score:** Likelihood × Impact  
- **Control Effectiveness (1–5):** Strength of existing controls  
- **Residual Risk Score:** Inherent risk minus control effectiveness  

Residual risk levels were categorized as **High**, **Medium**, or **Low** to support prioritization and treatment planning.

---

## Control Framework Alignment

Risk mitigation controls were mapped to **ISO/IEC 27001:2022 Annex A**, including:

- Access control and identity management  
- Secure authentication mechanisms  
- Logging and monitoring activities  
- Incident response governance  
- Risk management and compliance oversight  

This ensured alignment with internationally recognized information security management standards.

---

## Key Risk Areas Addressed

- Brute-force and credential reuse attacks  
- Privileged account compromise  
- Infrastructure-level authentication weaknesses  
- Insufficient security monitoring and detection  
- Incident response maturity gaps  
- Risk governance and review processes  

---

## Project Outcomes

- Developed an ISO-aligned enterprise risk register  
- Evaluated inherent and residual risk exposure  
- Mapped risks to applicable ISO 27001 controls  
- Defined mitigation strategies and treatment plans  
- Established governance review cycles and ownership  

---

## Files Included

- `Risk Register.xlsx` – Core risk register with scoring, control mapping, and treatment tracking  
- `Risk Register.pdf` – Visual overview of risk prioritization and governance structure
- `IR_Playbook_BruteForce.docx` – Incident response playbook for brute force attacks, aligned with NIST SP 800-61 lifecycle phases and MITRE ATT&CK framework.

---

## Skills Demonstrated

- ISO 27001 risk assessment and control mapping  
- Governance-focused risk analysis  
- Control effectiveness evaluation  
- Security operations to GRC translation  
- Risk treatment planning and lifecycle tracking  
- Documentation and reporting
- Incident response documentation and playbook development  
