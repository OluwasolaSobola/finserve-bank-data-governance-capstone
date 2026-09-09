# FinServe Bank – Data Quality Framework

## Purpose

The Data Quality Framework establishes a structured approach for defining, measuring, monitoring and improving the quality of critical FinServe Bank data.

The framework supports trusted decision-making, regulatory compliance, operational efficiency and effective Data Governance.

## Data Quality Dimensions

Five core Data Quality dimensions were defined:

### Accuracy
Data should correctly represent the real-world information it describes.

### Completeness
Required data should be populated and available.

### Consistency
Data should be represented consistently across systems and processes.

### Timeliness
Data should be sufficiently current and available when required.

### Validity
Data should conform to defined formats, standards and business rules.

## Example Data Quality Rules

| Data Element | Data Quality Rule | Dimension |
|---|---|---|
| Customer_ID | Must be unique | Consistency / Validity |
| Email | Must follow an approved email format | Validity |
| KYC_Status | Must not be null | Completeness |
| Date_of_Birth | Must contain a valid date | Accuracy / Validity |

## Data Quality Lifecycle

The framework follows a continuous improvement lifecycle:

**Profiling → Rule Definition → Monitoring → Issue Identification → Root-Cause Analysis → Resolution → Reporting → Continuous Improvement**

## Data Profiling

Profiling of customer data across CRM, Core Banking and Loan Systems identified:

- Approximately 18% duplicate customer records
- Approximately 22% missing mandatory fields, including KYC and income
- Approximately 15% inconsistencies across systems
- Approximately 20% outdated or stale records

These profiling results provided a basis for prioritising Data Quality remediation and governance controls.

## Root-Cause Analysis

Key contributing factors included:

- Unclear data ownership and accountability
- Manual data entry
- Weak validation controls
- Poor integration between CRM and Core Banking systems

The framework therefore addresses both the symptoms of poor Data Quality and the underlying governance and process causes.

## Data Quality Monitoring

The monitoring approach includes:

- Data validation rules
- Scheduled monitoring
- Data Quality thresholds
- Alerts
- Data Steward assignment
- Root-cause analysis
- Remediation tracking
- Escalation of significant issues

## Example Monitoring Thresholds

| Dimension | Target |
|---|---:|
| Accuracy | ≥90% |
| Completeness | ≥85% |
| Consistency | ≥90% |
| Timeliness | ≥95% |

Threshold breaches trigger review and appropriate remediation.

## Data Quality Issue Management

Issues follow the governance workflow:

**Identification → Logging → Triage → Assignment → Resolution → Closure → Reporting & Monitoring**

Issues are classified as:

- Low
- Medium
- High
- Critical

Escalation follows:

**Data Steward → Data Owner → Data Governance Council**

## Roles & Accountability

### Data Owners

Accountable for Data Quality within their domains and significant remediation decisions.

### Data Stewards

Responsible for operational monitoring, issue identification, coordination and escalation.

### Data Governance Council

Provides oversight and resolves significant or cross-domain issues.

### Governance Lead

Coordinates the overall governance framework and ensures Data Quality activities align with the wider Data Governance programme.

## Continuous Improvement

Data Quality performance should be reviewed regularly to identify:

- Recurring issues
- Root causes
- Control weaknesses
- Remediation progress
- Trends in Data Quality performance
- Opportunities for preventive controls

The objective is to move Data Quality management from reactive correction toward sustainable prevention and continuous improvement.
