# FinServe Bank – Data Governance Capstone

**Enterprise Data Governance & Data Quality Capstone Project | Governance Lead | 2026**

## Project Overview

This capstone project demonstrates the design and operationalisation of an enterprise Data Governance framework for FinServe Bank, a banking case study undergoing digital transformation through the MBanking 2025 initiative and a planned merger.

The project began with a current-state assessment that identified significant governance, data quality and regulatory challenges, including:

- 18 regulatory findings, including 6 high-risk issues
- 35% duplicate customer records
- 28% incomplete customer records
- Lack of a formal enterprise Data Governance framework
- Unclear data ownership and accountability
- Inadequate protection and governance of sensitive customer data
- Limited governance and oversight of AI models

As **Governance Lead**, I led the Data Governance team and coordinated the development of the enterprise Data Governance programme across four project stages, from current-state assessment and governance framework design through operationalisation, monitoring, integration and value realisation.

I guided the development of the governance strategy and operating model, coordinated governance deliverables and stakeholder alignment, and supported the design and operationalisation of controls across Data Quality, metadata management, data classification, Critical Data Elements, privacy, data lifecycle, AI Governance, Responsible AI, issue management, monitoring and programme implementation.

The project progressed across four stages:

### 1. Assess & Design
Conducted a current-state governance assessment, stakeholder analysis and governance gap review. Developed the Data Governance Charter, Critical Data Inventory, prioritised quick wins and a 12-month implementation roadmap.

### 2. Govern & Control
Designed a federated Data Governance operating model with a Governance Council, Data Owners, Data Stewards and supporting IT/Data teams. Developed governance policies, RACI responsibilities, Data Quality controls, metadata standards, issue management processes and AI Governance requirements.

### 3. Operationalise & Monitor
Applied the governance framework through Data Quality profiling, root-cause analysis, issue management and monitoring. Developed governance artefacts covering metadata, data catalogue, data lineage, data domains, data classification, PII inventory, AI model cards and bias assessment.

### 4. Integrate & Realise Value
Extended the programme toward enterprise operationalisation through governance performance measurement, integration planning, change management, stakeholder communication, business-value assessment and executive-level decision support.

## Governance Objectives

The programme was designed to:

- Improve data quality and reliability
- Strengthen regulatory compliance
- Establish clear data ownership and accountability
- Improve governance of sensitive and critical data
- Establish sustainable governance policies and controls
- Strengthen AI governance and responsible use of AI
- Support MBanking 2025 digital transformation
- Enable effective merger data integration

## Data Governance Operating Model

A **federated Data Governance operating model** was designed to balance centralised governance oversight with business-unit ownership and execution.

The governance structure consists of:

| Governance Role | Key Responsibility |
|---|---|
| Data Governance Council | Governance oversight, policy approval, performance monitoring and resolution of escalated issues |
| Data Owners | Accountability for domain data, definitions, quality, access and key decisions |
| Data Stewards | Day-to-day Data Quality monitoring, standards implementation and issue management |
| IT / Data Team | Technical implementation of governance controls, systems and data integration |
| Compliance | Regulatory oversight and compliance monitoring |
| Data Analytics | Data usage, analytics and stakeholder communication |

Domain-based stewardship forums were also defined for key business areas to support collaboration and consistent application of governance standards.

### Governance Cadence

- **Data Governance Council:** Monthly
- **Stewardship Forums:** Bi-weekly
- **Data Quality Reviews:** Monthly

A **RACI matrix** was developed to establish clear accountability across activities including data standards, Data Quality monitoring, issue resolution, classification, access, privacy, retention, metadata management, AI Governance and governance performance monitoring.

## Governance Policies & Standards

Seven core governance policy areas were developed to translate the operating model into practical governance controls:

1. **Data Quality Policy** – Defines Data Quality dimensions, standards, rules, monitoring, reporting and accountability.
2. **Data Access & PII Protection Policy** – Establishes least privilege, role-based access control, need-to-know access, segregation of duties, access reviews and PII protection requirements.
3. **Data Classification Policy** – Establishes sensitivity-based classification and appropriate handling requirements.
4. **AI Governance Policy** – Establishes Responsible AI principles, AI risk classification, model governance, impact assessment, monitoring and accountability.
5. **Data Retention Policy** – Defines retention requirements, lifecycle management, secure storage and disposal.
6. **Data Sharing Policy** – Establishes controls for internal, external and cross-border data sharing.
7. **Metadata Management Policy** – Defines standards for business, technical and operational metadata and the management of metadata for Critical Data Elements.

## Data Quality Framework

A structured Data Quality Framework was developed to measure, monitor and improve the reliability of critical data.

### Data Quality Dimensions

- Accuracy
- Completeness
- Consistency
- Timeliness
- Validity

Example Data Quality rules included:

| Data Element | Data Quality Rule | Purpose |
|---|---|---|
| Customer_ID | Must be unique | Prevent duplicate customer records |
| Email | Must follow a valid format | Improve validity |
| KYC_Status | Must not be null | Ensure completeness |
| Date_of_Birth | Must contain a valid date | Improve accuracy |

The Data Quality lifecycle covers:

**Profiling → Rule Definition → Monitoring → Issue Identification → Root-Cause Analysis → Resolution → Reporting → Continuous Improvement**

### Profiling & Monitoring

Customer data profiling across CRM, Core Banking and Loan Systems identified:

- ~18% duplicate customer records
- ~22% missing mandatory fields, including KYC and income
- ~15% inconsistencies across systems
- ~20% outdated or stale records

Root-cause analysis identified contributing factors including unclear data ownership, manual data entry, weak validation controls and poor integration between CRM and Core Banking systems.

A monitoring approach was designed using validation rules, scheduled monitoring, thresholds, alerts, Data Steward assignment and escalation of critical issues to Data Owners and the Data Governance Council.

## Metadata Management, Data Catalogue & Lineage

A metadata and catalogue approach was designed to improve data discovery, understanding, ownership and traceability.

The catalogue design incorporates:

- Data assets
- Business glossary
- Business, technical and operational metadata
- Data ownership and stewardship information
- Data classification
- Data lineage and relationships
- Search and discovery
- Role-based access

Key data domains included **Customer, Product, Transaction, Risk and Finance**.

Critical data flows were documented across:

- Customer onboarding
- Credit underwriting
- Fraud detection
- KYC/AML processing
- Regulatory reporting

An example end-to-end flow documented in the capstone was:

**CRM → Core Banking → Data Warehouse → Reporting**

The lineage approach was designed to improve traceability, impact analysis, issue investigation, auditability and regulatory compliance.

## Data Classification & PII Governance

A structured classification approach was developed to ensure that data is protected according to its sensitivity, business impact and risk.

The classification framework covered:

- Public
- Internal
- Confidential
- Restricted
- Highly Restricted

Governance controls included:

- Role-based access control
- Encryption for sensitive data
- Data masking for PII
- Monitoring and audit logging
- Periodic classification review

A **PII Inventory** was also developed to identify where personal and sensitive information is stored across Core Banking, CRM, Loan, Document Management and file-based systems.

The inventory supported the identification of appropriate protection requirements and Privacy Impact Assessment considerations.

## AI Governance & Responsible AI

An AI Governance Framework was developed to establish governance, accountability and risk-based oversight for AI models.

### Responsible AI Principles

The framework incorporated:

- Fairness
- Transparency
- Accountability
- Privacy
- Reliability

### AI Risk Classification

AI models were classified across four risk tiers:

| Tier | Risk Level | Example |
|---|---|---|
| Tier 1 | Low | Internal Reporting Model |
| Tier 2 | Moderate | Customer Segmentation / Recommendation Models |
| Tier 3 | High | Fraud Detection Model |
| Tier 4 | Critical | Credit Scoring, Risk Rating and AML Monitoring Models |

Eight AI models were assessed within the risk-classification framework.

Higher-risk models required stronger governance controls including validation, documentation, approval, monitoring, bias testing and review.

### AI Impact Assessment

An AI Impact Assessment template was developed covering:

- Model purpose and intended use
- Data sources and Data Quality
- Data sensitivity and PII
- Business, regulatory and operational risk
- Fairness and bias
- Explainability and transparency
- Privacy
- Accountability and ownership
- Stakeholders
- Monitoring and ongoing validation

Model Cards were also developed for high-risk use cases to document model purpose, inputs, outputs, ownership, limitations, risk level and monitoring requirements.

## Data Issue Management

A structured issue-management lifecycle was designed:

**Identification → Logging → Triage → Assignment → Resolution → Closure → Reporting & Monitoring**

Issues were classified by severity:

- Low
- Medium
- High
- Critical

The escalation model established:

**Data Steward → Data Owner → Data Governance Council**

Issue-management metrics included resolution time, number of open issues, severity distribution and recurring issues.

Root-cause analysis and lessons learned were incorporated to support continuous Data Quality improvement.

## Governance Performance & Executive KPIs

An executive scorecard was designed to make governance performance measurable across Data Quality, governance, metadata, compliance, AI, operations, adoption and risk.

Selected KPIs included:

| Governance Area | KPI | Target |
|---|---|---:|
| Data Quality | Completeness | ≥85% |
| Data Quality | Accuracy | ≥90% |
| Data Quality | Duplicate Rate | <5% |
| Governance | Ownership Coverage | 100% |
| Governance | Policy Compliance | ≥95% |
| Metadata | Catalogue Coverage | ≥90% |
| Metadata | Lineage Coverage | ≥80% |
| Compliance | KYC Completion | ≥95% |
| AI | Bias Gap | <10% |
| AI | Model Monitoring | 100% |
| Adoption | Training Completion | ≥90% |
| Risk | Data Incidents | 0 |

The wider executive framework contained **16 governance KPIs**, with operational monitoring, leadership reporting, threshold-based escalation and assigned KPI ownership.

Dashboard designs were developed for:

- Governance
- Data Quality
- AI Monitoring
- Compliance

## Strategic Roadmap & Value Realisation

The capstone progressed from immediate governance remediation into a longer-term strategy for embedding governance across the organisation.

### 3-Year Data Strategy

| Year | Focus | Key Activities | Strategic Impact |
|---|---|---|---|
| Year 1 | Foundation | Governance setup and Data Quality remediation | Risk reduction |
| Year 2 | Expansion | Metadata, catalogue and lineage | Improved data visibility |
| Year 3 | Optimisation | AI Governance and automation | Advanced analytics and sustainable governance |

The strategy focused investment across **People, Process and Technology**, connecting governance implementation with measurable business outcomes.

Expected value included:

- Reduced manual data correction and reconciliation
- Reduced reporting errors and rework
- Improved operational efficiency
- Improved decision-making
- Stronger regulatory compliance
- Reduced data and AI risk
- Increased accountability
- Improved organisational trust in data

## Key Capstone Deliverables

Across the four project stages, the team developed governance artefacts including:

- Current-State Data Governance Assessment
- Stakeholder Analysis and Matrix
- Data Governance Charter
- Critical Data Inventory
- Governance Quick Wins
- Implementation Roadmap
- Federated Data Governance Operating Model
- Data Governance Council and Stewardship Structure
- RACI Matrix
- Seven Core Governance Policies
- Data Quality Framework
- Data Quality Rules and Scorecards
- Data Quality Profiling and Root-Cause Analysis
- Data Issue Management Process
- Metadata Management Framework
- Data Catalogue Design
- Data Lineage Documentation
- Data Classification Framework
- PII Inventory
- Privacy Impact Assessment
- AI Governance Framework
- AI Risk Classification
- AI Impact Assessment
- AI Model Cards
- AI Bias Assessment
- Executive Governance Scorecard
- Governance Dashboard Designs
- Business Value Assessment
- 3-Year Data Strategy

## Skills Demonstrated

**Data Governance | Data Quality | Governance Operating Models | Data Ownership | Data Stewardship | RACI | Critical Data Elements | Metadata Management | Data Cataloguing | Business Glossary | Data Lineage | Data Classification | PII Governance | Data Lifecycle Management | Data Retention | Access Governance | Data Quality Rules | Data Quality Monitoring | Root-Cause Analysis | Issue Management | AI Governance | Responsible AI | Model Risk | Governance KPIs | Stakeholder Engagement | Regulatory Compliance**

## From Governance Design to Technical Implementation

This capstone demonstrates my ability to **design and operationalise a Data Governance programme**.

I subsequently extended the FinServe portfolio by implementing governance hands-on in a real Microsoft Azure environment using **Microsoft Purview, Azure Data Lake Storage Gen2 and Azure Data Factory**.

That implementation covers data cataloguing, metadata management, Data Quality profiling and rules, classification, a governed data product and end-to-end technical lineage.

➡️ **Microsoft Purview Implementation:**  
https://github.com/OluwasolaSobola/finserve-microsoft-purview-governance

## Project Context

FinServe Bank provides the banking case-study context used for this capstone project. The governance frameworks, assessments, policies, controls, artefacts and recommendations in this repository were developed as part of a structured Data Governance capstone.

The separate Microsoft Purview repository demonstrates the subsequent hands-on implementation of governance concepts in a real Microsoft Azure and Microsoft Purview environment.

## My Role – Governance Lead

As **Governance Lead**, I led and coordinated the Data Governance team across the four-stage FinServe Bank capstone.

My responsibilities included:

- Leading the Data Governance workstream
- Coordinating governance deliverables across the project team
- Guiding the Data Governance strategy and operating model
- Supporting stakeholder engagement and governance alignment
- Coordinating the development of governance policies, standards and controls
- Supporting Data Quality, metadata, classification and Critical Data Element governance
- Supporting AI Governance and Responsible AI activities
- Contributing to governance implementation, monitoring and executive reporting

## Author

**Oluwasola Sobola**  
Data Governance | Data Quality | Data Management | Responsible AI

LinkedIn: https://www.linkedin.com/in/oluwasolasobola  
GitHub: https://github.com/OluwasolaSobola
