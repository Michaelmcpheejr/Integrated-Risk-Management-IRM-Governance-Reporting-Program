# Risk Scoring Methodology

## Overview

The Risk Scoring Methodology defines how the organization evaluates, prioritizes, and governs risks throughout the Integrated Risk Management (IRM) Governance & Reporting Program.

The purpose of this methodology is to:

- Standardize enterprise risk evaluation across business and technology domains
- Improve governance prioritization based on measurable criteria
- Support remediation decision-making and resource allocation
- Enhance executive visibility into organizational risk posture
- Strengthen governance consistency across risk assessments
- Improve audit defensibility through repeatable and documented processes
- Enable scalable risk management operations across enterprise environments

This methodology uses a simplified 4-dimension enterprise scoring model designed to reduce subjective interpretation and support consistent governance operations at scale.

---

# Governance Scoring Principles

The scoring methodology operates using the following principles:

| Principle | Description |
|---|---|
| Risk-Based Prioritization | Risks are scored based on objective criteria rather than organizational bias or perceived severity. |
| Measurable Evaluation | Each scoring dimension uses defined criteria that different assessors can apply consistently. |
| Centralized Consistency | All risks are assessed using the same methodology regardless of business unit, domain, or assessment team. |
| Business Impact Alignment | Risk scores reflect actual business consequences, not just technical severity. |
| Regulatory Integration | Regulatory and compliance exposure is treated as a primary scoring factor. |
| Remediation Accountability | Risk scores drive remediation priority, escalation, and governance visibility. |
| Executive Visibility | Scores are normalized and comparable across the organization. |
| Repeatable Operations | The model is simple enough to apply consistently over time. |

---

# Enterprise Risk Scoring Model

The enterprise scoring model evaluates risk through four dimensions:

1. Likelihood  
2. Business Impact  
3. Regulatory Exposure  
4. Control Maturity  

Likelihood, Business Impact, and Regulatory Exposure are combined into the overall Risk Score.

Control Maturity is assessed separately as a governance indicator to show how effectively the risk is currently controlled.

---

# Why a 3-Point Scoring Model Is Used

The organization uses a 3-point scoring scale to improve consistency and reduce false precision.

This structure:

- Reduces ambiguity between similar categories
- Improves repeatability between assessors
- Forces clear categorization
- Supports executive readability
- Strengthens audit defensibility
- Makes scoring easier to explain and validate

The scoring scale is intentionally simple:

| Score | Meaning |
|---|---|
| 1 | Low |
| 2 | Moderate |
| 3 | High |

---

# Scoring Dimensions

## 1. Likelihood

Likelihood measures the probability that a risk event or control failure will occur within a 12-month period.

### Assessment Factors

- Historical frequency
- Threat exposure
- Known vulnerabilities
- Control gaps
- Operational weaknesses
- Attack surface exposure

### Scoring Scale

| Score | Likelihood Level | Definition |
|---|---|---|
| 1 | Unlikely | Event is unlikely to occur within the next 12 months. |
| 2 | Possible | Event could occur within the next 12 months due to known gaps or plausible conditions. |
| 3 | Highly Likely | Event is very likely to occur due to recurring issues, active exploitation, or significant control gaps. |

### Scoring Guidance

- Assess likelihood separately from impact.
- Use historical data where available.
- If the risk has occurred repeatedly, score higher.
- Document the key indicator that drove the score.

---

## 2. Business Impact

Business Impact measures the operational, financial, reputational, and business consequence if the risk occurs.

### Assessment Factors

- Operational disruption
- Financial exposure
- Business continuity impact
- Customer impact
- Reputational impact
- Recovery complexity

### Scoring Scale

| Score | Impact Level | Definition |
|---|---|---|
| 1 | Low | Minimal impact, limited disruption, easily recoverable. |
| 2 | Moderate | Meaningful disruption affecting multiple users, systems, or business processes. |
| 3 | Severe | Major business disruption, material financial impact, or significant reputational damage. |

### Scoring Guidance

- Score based on the expected business consequence if the risk occurs.
- Consider cascading impact across systems and teams.
- Document the primary impact driver.

---

## 3. Regulatory Exposure

Regulatory Exposure measures the compliance, legal, audit, and contractual implications of failing to address the risk.

### Assessment Factors

- Applicable regulatory frameworks
- Breach notification obligations
- Contractual security requirements
- Audit findings
- Legal exposure
- Compliance control obligations

### Scoring Scale

| Score | Regulatory Level | Definition |
|---|---|---|
| 1 | No Regulatory Impact | No expected regulatory reporting, breach notification, or material audit impact. |
| 2 | Moderate Regulatory Impact | Could result in audit findings, remediation plans, or non-material compliance gaps. |
| 3 | Severe Regulatory Impact | Could trigger breach notification, regulatory enforcement, material findings, or contractual violations. |

### Scoring Guidance

- Identify which frameworks apply to the risk.
- Distinguish between audit findings and regulatory enforcement.
- Consult Legal or Compliance when regulatory applicability is unclear.
- Document the specific regulation, framework, or obligation at risk.

---

## 4. Control Maturity

Control Maturity measures the effectiveness of current controls designed to prevent, detect, or respond to the risk.

Control Maturity is not included in the overall Risk Score. It is tracked separately as a governance indicator.

### Assessment Factors

- Control implementation status
- Preventive effectiveness
- Detective capability
- Monitoring and oversight
- Process consistency
- Audit validation
- Evidence availability

### Scoring Scale

| Score | Maturity Level | Definition |
|---|---|---|
| 1 | Ineffective / Missing | Control does not exist, is not operating, or lacks evidence of effectiveness. |
| 2 | Partially Effective | Control exists but has gaps, inconsistencies, or limited coverage. |
| 3 | Mature & Effective | Control is implemented, operating consistently, monitored, and evidence-supported. |

### Scoring Guidance

- Score actual control operation, not intended design.
- If a control is documented but not executed, score it as ineffective.
- If evidence is unavailable, score conservatively.
- Document the evidence used to support the maturity rating.

## Control Maturity Assessment

Control Maturity is assessed separately from the Risk Score calculation. It provides visibility into how effectively the current risk is being managed.

### How Control Maturity is Reported

Control Maturity appears alongside Risk Score in the risk register:

**Example:**
- Risk Score: 2.45 (High Risk)
- Control Maturity: 2 (Partially Effective)
- Interpretation: This is a high-severity risk with partially effective controls. Remediation should focus on advancing control maturity to level 3 (Mature & Effective) or accepting the risk formally with compensating controls.

---

# Risk Score Range & Severity Bands
### Risk Score Range: 1.0 - 3.0

Low Risk: 1.0 - 1.67
Moderate Risk: 1.68 - 2.32
High Risk: 2.33 - 3.0

---

## Governance Review Frequency

| Severity | Review Frequency |
|-----------|-----------|
| Low | Annually |
| Moderate | Quarterly |
| High | Monthly |

---

# Risk Scoring Formula

The overall Risk Score combines Likelihood, Business Impact, and Regulatory Exposure.

Risk Score = (Likelihood × 0.30) + (Business Impact × 0.35) + (Regulatory Exposure × 0.35)

---

## Risk Score Interpretation

The overall Risk Score ranges from 1.0 to 3.0 and determines governance actions and escalation.

| Risk Score | Severity | Governance Actions |
|---|---|---|
| 1.0 - 1.67 | Low Risk | Standard tracking; management-level oversight; 6-12 month remediation timeline |
| 1.68 - 2.32 | Moderate Risk | Documented remediation plan; director-level oversight; 30-60 day remediation timeline; escalate if unresolved beyond SLA |
| 2.33 - 3.0 | High Risk | Executive escalation; formal remediation mandate or risk acceptance; weekly tracking; 15-30 day remediation timeline |
