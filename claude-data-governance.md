# Data Governance, Strategy & Privacy Planning

**Platform:** Claude (Sonnet 4.5 / Opus 4)

---

## Multi-Step Interactive Prompt

I need your help developing a comprehensive data governance framework for my product. Let's work through this systematically, covering data strategy, privacy considerations, security requirements, and AI implications. This will result in actionable templates for engaging data science teams and creating governance policies.

**About Data Governance:**
- **Data Strategy**: How data creates value and competitive advantage
- **Data Governance**: Policies, processes, and standards for data management
- **Data Privacy**: Protecting personal information and regulatory compliance
- **Data Security**: Technical controls and access management
- **AI Considerations**: Ethical use, model governance, and transparency

---

## Step 1: Product & Data Context Discovery

Let me understand your product, data landscape, and current maturity:

### Product & Business Context

**Product Information:**
- Product name: [Your product]
- Product description: [What it does]
- Industry/vertical: [Sector you operate in]
- Product stage: [Early / Growth / Scaling / Mature]
- Geography: [Where you operate - impacts regulations]

**Business Model:**
- How you create value: [Core value proposition]
- How you monetize: [Revenue model]
- Customer type: [B2B / B2C / B2B2C]
- Target customer segments: [Who uses your product]

### Data Landscape Assessment

**Data You Collect:**
- What types of data do you collect? (User behavior, transactions, content, etc.)
- What sensitive data do you handle? (PII, PHI, financial, biometric, etc.)
- What volume of data? (Records, users, events per day)
- What's the source of data? (Users, APIs, third-parties, sensors, etc.)

**Data Categories:**

For each major data type, describe:
- **Category**: [e.g., Customer Profile Data]
- **Examples**: [Specific fields: name, email, age, etc.]
- **Sensitivity**: [Public / Internal / Confidential / Restricted]
- **Collection method**: [How you get it]
- **Purpose**: [Why you collect it]
- **Retention**: [How long you keep it]

**Data Usage:**
- What do you do with this data? (Analytics, ML models, personalization, etc.)
- Who accesses the data internally? (Teams and roles)
- Do you share data with third parties? (Partners, vendors, processors)
- Do you sell or monetize data?
- What AI/ML models use this data?

### Current State Assessment

**Existing Practices:**
- What data governance processes exist today? (None / Informal / Formal)
- What documentation exists? (Data dictionary, lineage, policies)
- What tools do you use? (Databases, analytics platforms, data warehouses)
- Who's responsible for data? (Roles and ownership)

**Compliance & Regulations:**
- What regulations apply to you? (GDPR, CCPA, HIPAA, SOC 2, etc.)
- What's your current compliance status? (Compliant / Working toward / Unknown)
- Have you had any data incidents or breaches? (Yes / No / Details)
- What are your contractual obligations? (Customer agreements, vendor contracts)

**Pain Points:**
- What keeps you up at night regarding data?
- What data-related questions can't you answer?
- What governance gaps have you identified?
- What regulatory or customer concerns exist?

### AI & Machine Learning Context

**Current AI Usage:**
- Do you use AI/ML in your product? (Yes / No / Planning to)
- What AI capabilities? (Recommendations, predictions, generation, automation)
- What models or algorithms? (Proprietary, third-party, open-source)
- What data trains these models?

**AI Considerations:**
- How transparent are your AI decisions to users?
- Can users contest or appeal AI decisions?
- Do you use customer data to train models?
- Do you use third-party AI services? (OpenAI, Anthropic, AWS, etc.)
- What happens to data sent to AI providers?

---

## Step 2: Stakeholder & Requirement Analysis

Based on what you've shared, I'll help you understand stakeholder needs and requirements:

### Internal Stakeholders

**Who needs to be involved:**
- Data Science/Analytics team
- Engineering/Platform team
- Legal/Compliance team
- Security/InfoSec team
- Product leadership
- Customer Success/Support

**Questions I'll help you answer:**
- What does each stakeholder need from data governance?
- What concerns or blockers do they have?
- What decision rights should each have?
- How will roles and responsibilities be defined?

### External Factors

**Regulatory Requirements:**
- What specific regulations apply and what do they require?
- What are the penalties for non-compliance?
- What evidence/documentation is needed?
- What deadlines or timelines exist?

**Customer Expectations:**
- What data rights do customers expect? (Access, deletion, portability)
- What transparency do they demand?
- What security standards do they require?
- What audit capabilities do they need?

**Competitive Landscape:**
- What are competitors doing for data governance?
- What are industry best practices?
- What certifications matter in your market?
- What creates competitive advantage?

---

## Step 3: Data Governance Framework Design

Now I'll help you design a comprehensive framework covering:

### Data Strategy Components

**Strategic Objectives:**
- How does data create competitive advantage?
- What data capabilities should you build?
- What data products or services could you offer?
- How does data support business goals?

**Data Principles:**
Core principles that guide all data decisions:
- Data as an asset (owned, managed, valued)
- Quality over quantity
- Privacy by design
- Security first
- Transparency and trust
- Ethical use

**Data Architecture:**
- Data collection and ingestion
- Storage and data warehousing
- Processing and transformation
- Access and consumption
- Retention and deletion

### Governance Structure

**Roles & Responsibilities:**

For each role, I'll define:
- **Data Owner**: Business accountability for data domain
- **Data Steward**: Tactical responsibility for data quality
- **Data Custodian**: Technical responsibility for data systems
- **Data Consumer**: Authorized users of data
- **Data Protection Officer**: Privacy and compliance oversight

**Decision Rights:**
- Who can collect new data?
- Who can access sensitive data?
- Who can share data externally?
- Who can change retention policies?
- Who approves AI use cases?

**Governance Bodies:**
- Data Governance Council (strategic oversight)
- Data Review Board (tactical decisions)
- Incident Response Team (breach handling)

### Data Policies & Standards

I'll help you develop policies for:

**Data Classification:**
- Public / Internal / Confidential / Restricted
- Labeling and handling requirements
- Access controls by classification

**Data Quality:**
- Accuracy requirements
- Completeness standards
- Timeliness expectations
- Consistency rules
- Validation processes

**Data Lifecycle:**
- Collection minimization
- Retention schedules
- Archival procedures
- Deletion processes
- Backup and recovery

**Data Access:**
- Authentication requirements
- Authorization models (RBAC, ABAC)
- Least privilege principle
- Access request process
- Access reviews and recertification

**Data Privacy:**
- Consent management
- Purpose limitation
- Data minimization
- User rights (access, deletion, portability)
- Privacy impact assessments

**Data Security:**
- Encryption (at rest, in transit, in use)
- Network security
- Application security
- Monitoring and logging
- Incident response

### AI Governance Considerations

**AI-Specific Policies:**

**Model Governance:**
- Model approval process
- Training data requirements
- Bias testing and mitigation
- Performance monitoring
- Model versioning and documentation

**Ethical AI:**
- Transparency requirements
- Explainability standards
- Fairness criteria
- Human oversight
- Right to appeal AI decisions

**Third-Party AI:**
- Vendor evaluation criteria
- Data sharing agreements
- Model auditing requirements
- Fallback plans

**AI Data Rights:**
- Training data ownership
- Model output ownership
- User data in prompts
- Retention of AI interactions

---

## Step 4: Stakeholder Engagement Templates

I'll create templates for engaging key stakeholders:

### Template 1: Data Science Team Engagement

**Meeting Agenda:**
- Current data usage and needs
- Proposed governance framework
- Impact on workflows
- Data quality requirements
- Access control changes
- AI governance implications

**Discussion Guide:**
- What data do you need for analytics/ML?
- What data quality issues exist?
- What access problems do you face?
- What governance helps vs. hinders?
- What AI use cases are planned?
- What tools and platforms do you need?

**Collaboration Framework:**
- Data request process
- Quality feedback loop
- Access provisioning SLA
- Documentation standards
- Model approval workflow

### Template 2: Data Owner Engagement

**Data Inventory Template:**

For each data domain:
- Data category and description
- Systems and storage locations
- Data owner and stewards
- Collection sources and methods
- Business purpose and usage
- Sensitivity classification
- Regulatory requirements
- Retention requirements
- Quality metrics
- Known issues

**Responsibility Matrix:**
- What decisions does data owner make?
- What processes must they follow?
- What documentation must they maintain?
- What reviews must they conduct?
- What training do they need?

### Template 3: Security & Legal Alignment

**Security Requirements:**
- Access control requirements
- Encryption standards
- Network segmentation
- Monitoring and alerting
- Incident response
- Audit logging

**Legal & Compliance Checklist:**
- Regulatory mapping (which laws apply)
- Compliance gaps and remediation
- Privacy notices and consent
- Data processing agreements
- Vendor contracts and DPAs
- Documentation requirements
- Audit and certification needs

### Template 4: Executive Briefing

**One-Page Summary:**
- Why this matters (business risk and opportunity)
- Current state and gaps
- Proposed approach
- Resource requirements
- Timeline and milestones
- Risk if not addressed
- Expected benefits

---

## Step 5: Data Governance Policy Document

Finally, I'll help you draft a comprehensive Data Governance Policy:

### Policy Document Structure

**1. Executive Summary**
- Purpose and scope
- Key principles
- Governance model
- Roles and responsibilities

**2. Data Strategy**
- Strategic objectives
- Data principles
- Success metrics
- Investment priorities

**3. Governance Framework**

**Organizational Structure:**
- Governance bodies and charters
- Roles and responsibilities (RACI matrix)
- Decision rights and escalation
- Communication and reporting

**Policy Domains:**
- Data classification policy
- Data quality policy
- Data access policy
- Data privacy policy
- Data security policy
- Data retention policy
- AI governance policy

**4. Data Lifecycle Management**

For each phase:
- **Collection**: What can be collected, consent, minimization
- **Storage**: Where, how, encryption, backup
- **Processing**: Allowed transformations, quality checks
- **Access**: Who, how, logging, monitoring
- **Sharing**: Internal and external, agreements, controls
- **Retention**: How long, archival, legal holds
- **Deletion**: When, how, verification

**5. Data Privacy Program**

**Privacy Principles:**
- Transparency and notice
- Consent and choice
- Data minimization
- Purpose limitation
- Access and correction
- Security safeguards

**Privacy Processes:**
- Privacy impact assessments (when required)
- Data mapping and inventory
- Consent management
- User rights handling (access, deletion, portability)
- Breach notification
- Privacy by design

**Regulatory Compliance:**

For each applicable regulation:
- Key requirements
- Implementation approach
- Evidence and documentation
- Responsible parties
- Compliance monitoring

**6. Data Security Standards**

**Access Controls:**
- Authentication methods (MFA, SSO)
- Authorization models (RBAC)
- Least privilege principle
- Access request and approval
- Access reviews (quarterly/annual)
- Privileged access management

**Technical Controls:**
- Encryption standards (at rest, in transit)
- Network security (segmentation, firewalls)
- Application security (secure coding, testing)
- Database security (hardening, monitoring)
- Cloud security (configuration, compliance)

**Monitoring & Logging:**
- What to log (access, changes, exports)
- Log retention and protection
- Security monitoring and alerts
- Anomaly detection
- Regular reviews

**Incident Response:**
- Incident classification
- Response procedures
- Notification requirements (internal, regulatory, customers)
- Investigation and remediation
- Post-incident review

**7. AI Governance Framework**

**AI Use Case Approval:**
- Business case and justification
- Data requirements and sources
- Privacy impact assessment
- Bias and fairness review
- Risk assessment
- Approval criteria and process

**Model Governance:**
- Model development standards
- Training data requirements
- Testing and validation
- Documentation requirements
- Performance monitoring
- Model versioning and updates
- Decommissioning

**Ethical AI Principles:**
- Transparency (how decisions are made)
- Explainability (why decisions are made)
- Fairness (no discriminatory outcomes)
- Accountability (human oversight)
- Privacy (data protection)
- Safety (fail-safes and limits)

**Third-Party AI Services:**
- Vendor evaluation criteria
- Data sharing agreements
- Subprocessor management
- Audit rights
- Exit strategy

**AI-Specific Controls:**
- User consent for AI processing
- Opt-out mechanisms
- Human review of critical decisions
- Contestability (appeal process)
- Transparency disclosures
- Training data governance
- Prompt injection prevention
- Output monitoring and filtering

**8. Data Quality Management**

**Quality Dimensions:**
- Accuracy (correct and reliable)
- Completeness (no missing values)
- Consistency (same across systems)
- Timeliness (current and up-to-date)
- Validity (conforms to rules)
- Uniqueness (no duplicates)

**Quality Processes:**
- Data profiling and assessment
- Quality rules and validation
- Issue identification and tracking
- Remediation and correction
- Quality metrics and reporting
- Continuous improvement

**9. Implementation Roadmap**

**Phase 1 (Months 1-3): Foundation**
- Establish governance structure
- Conduct data inventory
- Document current state
- Identify critical gaps
- Secure executive sponsorship

**Phase 2 (Months 4-6): Core Policies**
- Define and approve policies
- Implement classification scheme
- Deploy access controls
- Establish data owner model
- Begin training program

**Phase 3 (Months 7-9): Operationalization**
- Implement tooling and automation
- Roll out data quality program
- Execute privacy compliance
- Conduct security hardening
- Establish metrics and reporting

**Phase 4 (Months 10-12): Optimization**
- Mature AI governance
- Achieve certifications
- Optimize processes
- Scale across organization
- Continuous improvement

**10. Roles & Responsibilities (RACI)**

For each governance activity:
- **Responsible**: Who does the work
- **Accountable**: Who has decision authority
- **Consulted**: Who provides input
- **Informed**: Who needs to know

**11. Compliance & Audit**

**Compliance Monitoring:**
- Policy adherence metrics
- Access review completion
- Training completion rates
- Incident response times
- Quality scores

**Audit Readiness:**
- Documentation requirements
- Evidence collection
- Internal audit schedule
- External audit preparation
- Continuous compliance

**12. Training & Awareness**

**Training Programs:**
- New employee onboarding
- Role-specific training (owners, stewards, consumers)
- Annual refresher training
- Specialized training (privacy, security, AI ethics)

**Awareness:**
- Regular communications
- Best practice sharing
- Incident learnings
- Policy updates

**13. Continuous Improvement**

**Review Cadence:**
- Quarterly: Metrics and KPIs
- Semi-annual: Policy effectiveness
- Annual: Comprehensive review
- Ad-hoc: Incident-driven, regulatory changes

**Improvement Process:**
- Identify gaps and opportunities
- Propose changes
- Stakeholder review
- Approval and communication
- Implementation and monitoring

**14. Appendices**

- Glossary of terms
- Regulatory requirements summary
- Data classification guide
- Privacy notice templates
- Consent form templates
- Data processing agreements
- Incident response playbooks
- AI model card template

---

## Let's Begin!

**Please provide the information from Step 1: Product & Data Context Discovery.**

The more detail you provide, the more tailored and practical your data governance framework will be.

---

## Quick Start Option

**For faster initial draft, provide this essential context:**

```
Product: [Name and what it does]
Industry: [Sector]
Data types: [Main categories of data collected]
Sensitive data: [PII, financial, health, etc.]
Regulations: [GDPR, CCPA, HIPAA, etc.]
AI usage: [Yes/No - what for]
Current state: [None / Informal / Basic]
Top concern: [Biggest data governance worry]
```

I can start with this and iterate to add depth and detail!
