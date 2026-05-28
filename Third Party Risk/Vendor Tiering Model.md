# Vendor Tiering Model

## Overview

The Vendor Tiering Model establishes the governance framework used to classify third-party vendors based on business criticality, data exposure, regulatory impact, and organizational dependency.

The purpose of vendor tiering is to:

- Standardize vendor classification
- Improve third-party governance consistency
- Align assessment effort with vendor risk
- Support risk-based decision making
- Strengthen regulatory compliance
- Improve executive visibility into third-party exposure
- Optimize governance resources

Vendor tiering serves as the foundation for all third-party risk management activities.

---

# Governance Philosophy

Not all vendors present the same level of risk.

Examples:

- Office supply vendor
- Payroll provider
- Cloud hosting provider
- Managed security service provider

Each introduces significantly different levels of organizational exposure.

The Vendor Tiering Model ensures governance activities are proportional to actual risk.

Higher-risk vendors receive:

- More rigorous assessments
- More frequent reviews
- Increased executive oversight
- Enhanced monitoring requirements

Lower-risk vendors receive governance activities appropriate to their risk profile.

---

# Tiering Objectives

The Vendor Tiering Model seeks to:

- Prioritize governance resources
- Improve risk visibility
- Support regulatory compliance
- Strengthen vendor oversight
- Improve reporting consistency
- Reduce supply chain risk exposure

---

# Vendor Classification Factors

Every vendor should be evaluated across four primary dimensions.

## Business Criticality

Measures how important the vendor is to organizational operations.

Questions:

- Would operations stop if the vendor became unavailable?
- Does the vendor support a critical business process?
- Would downtime significantly impact revenue or operations?

---

## Data Exposure

Measures the sensitivity of information accessed, processed, transmitted, or stored by the vendor.

Examples:

- Public information
- Internal business information
- Personally Identifiable Information (PII)
- Protected Health Information (PHI)
- Financial data
- Intellectual property

---

## Regulatory Impact

Measures how significantly the vendor affects compliance obligations.

Examples:

- HIPAA
- SOX
- PCI DSS
- ISO 27001
- NIST-based programs
- Customer contractual requirements

---

## System Access

Measures the level of technical access granted to the vendor.

Examples:

- No system access
- Limited application access
- Network connectivity
- Administrative privileges
- Production environment access

---

# Vendor Tier Structure

The organization utilizes a four-tier vendor classification model.

---

# Tier 1: Critical Vendors

## Definition

Vendors whose failure would significantly disrupt business operations, regulatory compliance, or security posture.

## Characteristics

- Supports mission-critical business functions
- Processes highly sensitive data
- Maintains privileged system access
- Significant regulatory impact
- High organizational dependency

## Examples

- Cloud hosting providers
- Payroll providers
- Identity providers
- Managed security providers
- Critical SaaS platforms

## Governance Requirements

| Requirement | Frequency |
|---|---|
| Risk Assessment | Annual |
| Security Assessment | Annual |
| Executive Review | Quarterly |
| Monitoring | Continuous |
| Risk Reporting | Quarterly |

---

# Tier 2: High-Risk Vendors

## Definition

Vendors supporting important business functions with meaningful access to systems or sensitive data.

## Characteristics

- Supports important business operations
- Accesses sensitive business information
- Moderate regulatory impact
- Moderate operational dependency

## Examples

- HR systems
- Business software providers
- Data processing vendors
- Professional service providers

## Governance Requirements

| Requirement | Frequency |
|---|---|
| Risk Assessment | Annual |
| Security Assessment | Annual |
| Monitoring | Quarterly |
| Risk Reporting | Semi-Annual |

---

# Tier 3: Moderate-Risk Vendors

## Definition

Vendors supporting business operations with limited access to sensitive information or systems.

## Characteristics

- Limited operational dependency
- Limited data exposure
- Low regulatory impact
- Restricted access privileges

## Examples

- Training providers
- Marketing vendors
- Consulting firms
- Operational support vendors

## Governance Requirements

| Requirement | Frequency |
|---|---|
| Risk Assessment | Every 2 Years |
| Monitoring | Annual |
| Risk Reporting | Annual |

---

# Tier 4: Low-Risk Vendors

## Definition

Vendors presenting minimal operational, security, compliance, or regulatory exposure.

## Characteristics

- No sensitive data access
- No system access
- Minimal operational dependency
- Minimal regulatory impact

## Examples

- Office supply vendors
- Event vendors
- General service providers
- Commodity suppliers

## Governance Requirements

| Requirement | Frequency |
|---|---|
| Initial Review | Upon Onboarding |
| Monitoring | As Needed |
| Risk Reporting | As Needed |

---

# Vendor Tiering Matrix

| Factor | Tier 1 | Tier 2 | Tier 3 | Tier 4 |
|---|---|---|---|---|
| Business Criticality | High | Moderate-High | Moderate | Low |
| Data Sensitivity | Highly Sensitive | Sensitive | Internal | Public |
| Regulatory Impact | High | Moderate | Low | Minimal |
| System Access | Privileged | Significant | Limited | None |
| Operational Dependency | High | Moderate | Low | Minimal |

---

# Tier Assignment Process

Vendor tiering should occur during onboarding.

The process includes:

1. Vendor Identification
2. Data Collection
3. Risk Evaluation
4. Tier Determination
5. Governance Approval
6. Vendor Registration

Tier assignments should be documented within the Vendor Risk Register.

---

# Tier Review Requirements

Vendor classifications should be reassessed when:

- Services change
- System access changes
- Regulatory requirements change
- Security incidents occur
- Business dependency increases
- Contracts are renewed

Tier changes should be documented and approved.

---

# Escalation Criteria

Vendor tier reassessment should occur immediately when:

- Significant security incident occurs
- Vendor acquires sensitive data access
- Vendor receives privileged access
- Regulatory obligations increase
- Critical business dependency emerges

Escalation should follow the Escalation Procedures Framework.

---

# Governance Reporting

Reporting should provide visibility into:

- Vendors by tier
- Tier distribution trends
- Critical vendor inventory
- High-risk vendor inventory
- Tier reassignment activity
- Assessment completion status

---

# Executive Visibility

Executive reporting should focus on:

- Tier 1 Vendors
- Tier 2 Vendors with open findings
- Critical vendor remediation efforts
- Vendor risk acceptance decisions
- Significant vendor incidents

---

# Audit Readiness Considerations

Documentation should demonstrate:

- Vendor classification methodology
- Tier assignment decisions
- Risk assessments
- Governance approvals
- Reassessment activities
- Monitoring activities

All records should be retained according to organizational retention requirements.

---

# Framework Alignment

This model supports:

- NIST Cybersecurity Framework
- NIST SP 800-53
- NIST SP 800-171
- ISO/IEC 27001
- HIPAA Security Rule
- SOX ITGC
- Third-Party Risk Management (TPRM)
- ServiceNow Vendor Risk Management Concepts

---

# Summary

The Vendor Tiering Model establishes a consistent and risk-based approach for classifying third-party vendors according to business criticality, data exposure, regulatory impact, and system access.

By aligning governance requirements with vendor risk levels, the organization improves oversight, strengthens compliance, optimizes governance resources, and enhances enterprise risk management maturity.
