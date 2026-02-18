# GRC Risk Register & Control Mapping Project

## Overview

This project demonstrates a practical Governance, Risk, and Compliance (GRC) risk assessment for a simulated SaaS web application environment. The objective was to identify key security risks, evaluate their potential business impact, assess existing controls, and prioritize mitigation actions using a structured risk register.

The risk scenarios were informed by observed authentication abuse and system behavior detected during a separate SOC-style log analysis project, creating a realistic link between security operations and risk management.

---

## Environment Scope

The simulated organization operates a cloud-hosted web application that includes:

- User authentication and session management system  
- Administrative management portal with elevated privileges  
- Customer database containing personal information  
- Cloud application servers and infrastructure  
- Centralized logging and monitoring system  
- Third-party service integrations (email, analytics, payment processing)

---

## Risk Assessment Methodology

Each risk was evaluated using a structured approach:

- **Likelihood (1–5):** Probability of the risk occurring  
- **Impact (1–5):** Business, operational, and security impact if realized  
- **Inherent Risk Score:** Likelihood × Impact  
- **Control Effectiveness (1–5):** Strength of existing controls  
- **Residual Risk Score:** Inherent Risk minus control effectiveness  

Risks were categorized as **High**, **Medium**, or **Low** based on residual exposure.

---

## Control Framework Reference

Mitigation controls were aligned with principles from the **NIST Cybersecurity Framework (CSF)**:

- Identify  
- Protect  
- Detect  
- Respond  

This ensured governance-focused risk management rather than purely technical remediation.

---

## Key Risk Areas Covered

- Authentication abuse and brute-force attacks  
- Excessive privilege access  
- Customer data exposure  
- Insufficient monitoring and alerting  
- Patch management gaps  
- Third-party security dependencies  

---

## Project Outcomes

- Created a structured asset inventory and risk register  
- Prioritized high-impact security risks  
- Mapped mitigation controls to governance frameworks  
- Defined treatment strategies and review cycles  

This project reflects real-world GRC workflows used to translate security threats into business-focused risk management actions.

---

## Files Included

- `Risk Register.xlsx` – Core risk register with scoring and control mapping  
- `Screenshots/` – Risk overview and prioritization visuals  

---

## Skills Demonstrated

- Risk assessment and prioritization  
- Control evaluation and mitigation planning  
- Governance framework alignment (NIST CSF)  
- Translating security operations into GRC risk processes  
- Documentation and reporting
