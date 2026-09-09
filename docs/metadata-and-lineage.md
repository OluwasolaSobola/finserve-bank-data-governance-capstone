# FinServe Bank – Metadata Management, Data Catalogue & Lineage Framework

## Purpose

The Metadata Management, Data Catalogue and Lineage Framework establishes a structured approach for managing information about FinServe Bank's data assets.

The framework was designed to improve data discovery, understanding, ownership, traceability, impact analysis and regulatory compliance.

## Metadata Management Approach

FinServe Bank's metadata framework covers three categories of metadata:

### Business Metadata

Business metadata provides business context and meaning for data.

Examples include:

- Business definitions
- Business terms
- Data domains
- Data ownership
- Data stewardship
- Critical Data Element status
- Data classification
- Data Quality requirements

### Technical Metadata

Technical metadata describes the structure and technical characteristics of data.

Examples include:

- Database and system names
- Tables
- Columns
- Data types
- File structures
- Source and target systems
- Technical relationships

### Operational Metadata

Operational metadata describes how data is created, processed, moved and monitored.

Examples include:

- Data refresh frequency
- Processing timestamps
- Data Quality results
- Transformation processes
- System interfaces
- Operational status

## Data Catalogue

A Data Catalogue approach was designed to provide a central mechanism for discovering and understanding governed data assets.

The catalogue design incorporates:

- Data assets
- Business glossary terms
- Business metadata
- Technical metadata
- Operational metadata
- Data ownership
- Data stewardship
- Data classification
- Critical Data Elements
- Data lineage and relationships
- Search and discovery
- Role-based access information

## Data Domains

Key enterprise data domains identified within the governance framework include:

- Customer
- Product
- Transaction
- Risk
- Finance

Domain-based governance supports clear accountability by assigning Data Owners and Data Stewards to important business data.

## Critical Data Elements

Critical Data Elements are prioritised according to their business, regulatory, operational and risk importance.

CDE governance includes:

- Business definition
- Data domain
- Source system
- Data Owner
- Data Steward
- Classification
- Data Quality requirements
- Regulatory or business importance

The detailed Critical Data Element inventory is maintained in:

`registers/critical-data-inventory.csv`

## Business Glossary

The Business Glossary provides agreed business definitions for important data concepts.

The glossary is designed to:

- Establish consistent terminology
- Reduce ambiguity
- Support common understanding across business and technical teams
- Improve Data Quality rule interpretation
- Support Data Catalogue discovery
- Strengthen ownership and stewardship

## Data Lineage

Data lineage documents how data moves between source systems, processing environments and downstream consumers.

The lineage framework was designed to support:

- End-to-end traceability
- Impact analysis
- Root-cause analysis
- Data Quality investigation
- Change management
- Auditability
- Regulatory compliance

## Critical Data Flows

Priority data flows identified for governance included:

- Customer onboarding
- Credit underwriting
- Fraud detection
- KYC / AML processing
- Regulatory reporting

An example end-to-end lineage documented during the capstone was:

**CRM → Core Banking → Data Warehouse → Reporting**

This illustrates how customer data can move from its originating business system through operational processing into downstream reporting.

## Ownership & Stewardship

### Data Owners

Data Owners are accountable for:

- Business definitions
- Data Quality expectations
- Access decisions
- Classification
- Critical Data Elements
- Domain-level governance decisions

### Data Stewards

Data Stewards support day-to-day governance by:

- Maintaining metadata
- Supporting business definitions
- Monitoring Data Quality
- Maintaining governance standards
- Coordinating issue remediation
- Supporting classification and CDE governance

## Metadata Quality

Metadata should be:

- Complete
- Accurate
- Consistent
- Current
- Clearly owned
- Understandable to relevant users

Metadata quality should be reviewed as part of ongoing governance monitoring.

## Governance Controls

Key controls include:

- Mandatory ownership for priority data assets
- Standard business definitions
- Classification of sensitive data
- CDE identification
- Data Quality requirements
- Periodic metadata review
- Documentation of critical lineage
- Controlled access to sensitive information
- Governance escalation for unresolved metadata issues

## Governance Monitoring

Metadata and lineage performance is incorporated into the executive governance KPI framework.

Key targets include:

- **Catalogue Coverage: ≥90%**
- **Lineage Coverage: ≥80%**
- **Ownership Coverage: 100%**

These measures support ongoing monitoring of governance adoption and maturity.

## Governance Lead

**Oluwasola Sobola – Governance Lead**

As Governance Lead, I led the Data Governance team and coordinated the development of the wider governance programme, including the approach to metadata management, data ownership and stewardship, Critical Data Elements, catalogue design and data lineage.
