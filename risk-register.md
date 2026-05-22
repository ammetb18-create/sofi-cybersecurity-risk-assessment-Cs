# Cybersecurity Risk Register

## Purpose

This risk register identifies key cybersecurity and GRC risk areas relevant to SoFi Technologies, Inc. based on the company’s fintech business model, public cybersecurity disclosures, and common risk considerations for digital financial services organizations.

The purpose of this register is to organize risks by likelihood, impact, risk rating, affected assets, and recommended remediation actions from a GRC analyst perspective.

## Risk Rating Methodology

This case study uses a simple qualitative risk rating model:

| Likelihood | Description |
|---|---|
| Low | The risk is possible but less likely based on the available context. |
| Medium | The risk is reasonably possible and should be actively managed. |
| High | The risk is likely or highly relevant due to the nature of the business, data, or operating environment. |

| Impact | Description |
|---|---|
| Low | Limited business, operational, customer, or compliance impact. |
| Medium | Moderate business, operational, customer, or compliance impact. |
| High | Significant business, operational, customer, regulatory, financial, or reputational impact. |

| Risk Rating | Criteria |
|---|---|
| Low | Low likelihood and/or limited impact. |
| Medium | Moderate likelihood or moderate impact. |
| High | High likelihood and/or high impact. |
| Critical | High likelihood combined with high business, customer, regulatory, or operational impact. |

## Risk Register

| Risk ID | Risk Description | Affected Asset / Data Area | Likelihood | Impact | Risk Rating | Recommended Controls | Priority |
|---|---|---|---|---|---|---|---|
| R-001 | Unauthorized access to customer personal or financial data | Customer accounts, personal data, financial data | High | High | Critical | Enforce MFA, least privilege access, privileged access reviews, continuous monitoring, and strong authentication controls. | High |
| R-002 | Phishing attack targeting employees or administrative users | Employee email, internal systems, administrative access | High | High | Critical | Conduct phishing awareness training, email filtering, MFA, suspicious login monitoring, and incident escalation procedures. | High |
| R-003 | Excessive employee access privileges | Internal administrative systems, customer support systems, employee access data | Medium | High | High | Implement role-based access control, quarterly access reviews, approval workflows, and privileged access management. | High |
| R-004 | Weak offboarding process for terminated employees or contractors | Internal systems, administrative accounts, vendor tools | Medium | High | High | Create formal offboarding checklist, disable access immediately, review shared accounts, and audit terminated-user activity. | High |
| R-005 | Third-party vendor security weakness or data breach | Vendor systems, identity verification providers, payment processors, customer data | Medium | High | High | Perform vendor due diligence, require security questionnaires, review SOC 2 reports, define breach notification terms, and monitor vendor risk. | High |
| R-006 | Misconfigured cloud storage exposing sensitive files | Cloud storage, loan documents, customer records, compliance documentation | Medium | High | High | Use cloud configuration monitoring, encryption, access restrictions, data classification, and periodic cloud security reviews. | High |
| R-007 | Incomplete security logging or monitoring | Security logs, audit records, customer account activity, administrative activity | Medium | High | High | Centralize logs, monitor privileged activity, define alert thresholds, retain logs, and review audit trail completeness. | Medium to High |
| R-008 | Incomplete incident response documentation or testing | Incident response plans, escalation procedures, security operations | Medium | High | High | Maintain incident response plan, define roles, conduct tabletop exercises, document lessons learned, and test escalation procedures. | Medium to High |
| R-009 | Insecure handling of loan application documents | Loan application platform, document storage, customer-submitted files | Medium | High | High | Encrypt documents, restrict access, classify sensitive files, define retention periods, and monitor document access. | Medium to High |
| R-010 | Account takeover affecting customer accounts | Customer accounts, authentication data, transaction activity | High | High | Critical | Require MFA, behavioral monitoring, anomaly detection, login alerts, device recognition, and customer notification workflows. | High |
| R-011 | Weak audit evidence management | Compliance documentation, control evidence, audit records | Medium | Medium | Medium | Create evidence request tracker, assign control owners, standardize evidence collection, and maintain audit-ready documentation. | Medium |
| R-012 | Regulatory or compliance exposure due to inadequate cybersecurity governance | Policies, procedures, risk documentation, customer data, financial operations | Medium | High | High | Maintain cybersecurity governance documentation, map controls to frameworks, review regulatory expectations, and report risk to leadership. | High |

## Highest Priority Risks

The highest priority risks in this case study are:

1. Unauthorized access to customer personal or financial data  
2. Phishing attacks targeting employees or administrative users  
3. Account takeover affecting customer accounts  
4. Third-party vendor security weakness or data breach  
5. Misconfigured cloud storage exposing sensitive files  

These risks are prioritized because they directly affect customer trust, sensitive financial information, regulatory exposure, business continuity, and the confidentiality, integrity, and availability of digital financial services.

## GRC Analyst Takeaway

From a GRC perspective, the risk register shows how cybersecurity risks can be translated into business-readable findings, control recommendations, and remediation priorities.

This type of documentation supports audit readiness, compliance reporting, risk ownership, executive communication, and security program maturity.
