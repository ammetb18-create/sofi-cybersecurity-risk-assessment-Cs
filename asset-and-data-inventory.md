# Asset and Data Inventory

## Purpose

This section identifies the key business assets, technology systems, data types, and third-party dependencies that may be relevant to a cybersecurity risk assessment for SoFi Technologies, Inc.

From a GRC perspective, an asset and data inventory helps determine what needs to be protected, which systems may introduce risk, what data is sensitive, and where security controls should be prioritized.

## Key Business Assets

| Asset Category | Description | Security Relevance |
|---|---|---|
| Customer Accounts | Digital member accounts used to access financial products and services. | High-value target for account takeover, fraud, unauthorized access, and identity misuse. |
| Loan Application Platform | Systems used to collect and process personal loan, student loan, mortgage, or other lending-related applications. | Handles sensitive financial and identity data that must be protected against unauthorized access or exposure. |
| Banking and Financial Services Platform | Digital systems supporting banking, payments, account activity, and financial service operations. | Requires strong controls for confidentiality, integrity, availability, and transaction reliability. |
| Internal Administrative Systems | Internal tools used by employees to manage customer accounts, workflows, operations, support, and compliance activities. | Excessive privileges or weak access controls could create insider risk or unauthorized data access. |
| Customer Support Systems | Tools used to assist members with account, loan, banking, or financial service issues. | May expose customer data if access is not properly restricted, monitored, and logged. |
| Security Monitoring Systems | Systems used to detect suspicious activity, monitor events, and support cybersecurity operations. | Important for incident detection, investigation, and response readiness. |
| Compliance and Audit Documentation | Policies, procedures, control evidence, risk assessments, and audit records. | Needed to demonstrate security governance, regulatory readiness, and control effectiveness. |

## Key Data Types

| Data Type | Description | Potential Risk |
|---|---|---|
| Personal Identifiable Information | Names, addresses, contact information, dates of birth, and other identity-related data. | Unauthorized disclosure could lead to identity theft, fraud, legal exposure, and reputational harm. |
| Financial Information | Income details, account information, loan information, payment history, and financial activity. | Exposure or manipulation could affect customers, regulatory compliance, and business trust. |
| Authentication Data | Login credentials, authentication tokens, MFA settings, and session-related information. | Weak protection could lead to account takeover or unauthorized access. |
| Loan Application Data | Documents and information submitted during lending or financial product applications. | Sensitive data could be exposed through weak access controls, insecure storage, or misconfigured systems. |
| Transaction and Account Activity Data | Records of customer activity, account changes, payments, and platform usage. | Unauthorized modification or exposure could affect integrity, fraud detection, and customer trust. |
| Employee Access Data | User roles, permissions, login history, and administrative access activity. | Poor monitoring could make it harder to detect insider threats or excessive access privileges. |
| Vendor and Third-Party Data | Information shared with or processed by vendors, partners, identity verification services, payment processors, or cloud providers. | Third-party compromise could create indirect exposure or compliance risk. |
| Security Logs and Audit Records | Logs used to investigate events, detect anomalies, and support audit or compliance activities. | Missing or incomplete logs can weaken incident response and audit readiness. |

## Third-Party and Vendor Dependencies

Fintech companies often depend on third-party providers for identity verification, cloud infrastructure, payment processing, data analytics, customer support tools, cybersecurity tooling, and compliance-related services.

These dependencies can introduce risk if vendors do not maintain adequate security controls, if data-sharing arrangements are not properly governed, or if third-party incidents affect customer data or business operations.

Key vendor risk considerations include:

- Vendor access to sensitive customer or business data
- Contractual security and privacy requirements
- Third-party incident notification procedures
- Security review and due diligence processes
- Ongoing vendor monitoring
- Data retention and deletion practices
- Business continuity and service availability

## Criticality Assessment

| Asset / Data Area | Criticality | Reason |
|---|---|---|
| Customer personal and financial data | High | Core sensitive data requiring strong confidentiality, privacy, and regulatory protection. |
| Customer account access systems | High | Account compromise could lead to fraud, unauthorized activity, and loss of customer trust. |
| Loan application systems | High | Processes sensitive financial and identity data used in lending workflows. |
| Internal administrative access | High | Privileged access can create major risk if not properly controlled and monitored. |
| Third-party data processing | Medium to High | Vendor weaknesses may create indirect exposure or operational disruption. |
| Security logs and monitoring | High | Required for detection, investigation, audit evidence, and incident response. |
| Compliance documentation | Medium to High | Supports governance, audit readiness, and regulatory response. |

## GRC Takeaway

The highest-priority assets and data areas in this case study are customer personal information, financial data, account access systems, loan application workflows, privileged internal systems, third-party processing relationships, and security logs.

These assets should be prioritized in the risk register because they directly affect confidentiality, integrity, availability, customer trust, regulatory expectations, and business continuity.
