# Cybersecurity Control Mapping

## Purpose

This section maps the key cybersecurity risks identified in the risk register to common cybersecurity control categories. The goal is to demonstrate how a GRC analyst connects risks to practical controls, remediation actions, and recognized cybersecurity frameworks.

Control mapping helps organizations understand which safeguards are needed to reduce risk, support audit readiness, and improve cybersecurity governance.

## Frameworks Referenced

This case study references the following cybersecurity frameworks and control sources at a high level:

- NIST Cybersecurity Framework
- NIST SP 800-53
- CIS Controls
- General GRC and cybersecurity risk management practices

The purpose of this mapping is not to provide a complete formal audit, but to demonstrate practical GRC analysis and risk-to-control thinking.

## Risk-to-Control Mapping

| Risk ID | Risk Area | Recommended Control Category | Example Controls | Framework Alignment |
|---|---|---|---|---|
| R-001 | Unauthorized access to customer personal or financial data | Access Control / Identity and Access Management | MFA, least privilege, access reviews, privileged access monitoring, strong authentication | NIST CSF Protect, NIST 800-53 AC, IA, CIS Controls |
| R-002 | Phishing attack targeting employees or administrative users | Security Awareness / Email Security / Authentication | Phishing training, email filtering, MFA, suspicious login alerts, incident reporting process | NIST CSF Protect & Detect, NIST 800-53 AT, IA, IR, CIS Controls |
| R-003 | Excessive employee access privileges | Role-Based Access Control / Privileged Access Management | RBAC, quarterly access reviews, approval workflows, privileged access management | NIST 800-53 AC, AU, CIS Controls |
| R-004 | Weak offboarding process for terminated employees or contractors | Identity Lifecycle Management | Termination checklist, immediate access removal, account deactivation, audit of terminated-user activity | NIST 800-53 AC, PS, CIS Controls |
| R-005 | Third-party vendor security weakness or data breach | Third-Party Risk Management | Vendor due diligence, security questionnaires, SOC 2 review, breach notification requirements, ongoing vendor monitoring | NIST CSF Govern, NIST 800-53 SR, CA, CIS Controls |
| R-006 | Misconfigured cloud storage exposing sensitive files | Cloud Security / Data Protection | Cloud configuration monitoring, encryption, access restrictions, data classification, periodic security reviews | NIST CSF Protect & Detect, NIST 800-53 SC, AC, CM, CIS Controls |
| R-007 | Incomplete security logging or monitoring | Logging / Monitoring / Audit Trails | Centralized logs, privileged activity monitoring, alert thresholds, log retention, audit trail review | NIST CSF Detect, NIST 800-53 AU, SI, CIS Controls |
| R-008 | Incomplete incident response documentation or testing | Incident Response Planning | Incident response plan, defined roles, tabletop exercises, escalation procedures, lessons learned documentation | NIST CSF Respond, NIST 800-53 IR, CP, CIS Controls |
| R-009 | Insecure handling of loan application documents | Data Protection / Records Management | Encryption, restricted access, retention rules, document classification, monitoring document access | NIST CSF Protect, NIST 800-53 AC, SC, MP, CIS Controls |
| R-010 | Account takeover affecting customer accounts | Customer Account Security / Fraud Prevention | MFA, behavioral monitoring, anomaly detection, device recognition, login alerts, customer notification workflows | NIST CSF Protect & Detect, NIST 800-53 IA, AC, AU, SI |
| R-011 | Weak audit evidence management | Audit Readiness / Compliance Documentation | Evidence request tracker, control owners, standardized evidence collection, audit documentation repository | NIST CSF Govern, NIST 800-53 CA, AU, PM |
| R-012 | Regulatory or compliance exposure due to inadequate cybersecurity governance | Governance / Policy / Risk Management | Cybersecurity policies, control mapping, risk reporting, leadership oversight, regulatory review process | NIST CSF Govern, NIST 800-53 PM, PL, RA, CA |

## Control Themes

The control mapping highlights several recurring control themes:

1. Identity and access management  
2. Multi-factor authentication  
3. Privileged access monitoring  
4. Vendor risk management  
5. Cloud configuration management  
6. Data protection and encryption  
7. Logging and monitoring  
8. Incident response planning  
9. Audit evidence management  
10. Cybersecurity governance and policy documentation  

## Priority Control Recommendations

Based on the risk register and matrix, the following controls should be prioritized first:

| Priority | Control Recommendation | Reason |
|---|---|---|
| 1 | Strengthen MFA and access control enforcement | Reduces unauthorized access, account takeover, and credential compromise risk. |
| 2 | Implement recurring access reviews | Reduces excessive access and supports audit readiness. |
| 3 | Improve phishing defense and awareness training | Reduces likelihood of employee credential compromise. |
| 4 | Strengthen vendor risk management | Reduces third-party exposure and supports compliance oversight. |
| 5 | Improve security logging and monitoring | Supports detection, investigation, audit evidence, and incident response. |
| 6 | Formalize incident response testing | Improves readiness during a real cybersecurity event. |
| 7 | Standardize audit evidence collection | Improves compliance documentation and audit efficiency. |

## GRC Analyst Takeaway

This control mapping demonstrates how cybersecurity risks can be translated into practical safeguards and control categories.

From a GRC analyst perspective, this work supports:

- Risk mitigation planning
- Audit readiness
- Compliance documentation
- Security control ownership
- Executive reporting
- Cybersecurity governance maturity

The value of control mapping is that it connects business risk to concrete security actions.
