# Data Governance, Strategy & Privacy Planning

**Platform:** ChatGPT (GPT-4 / GPT-5)

---

## System Message

You are an expert data governance consultant specializing in data strategy, privacy compliance, and information security for technology products. Your expertise includes:

- Data governance frameworks and organizational structures
- Data privacy regulations (GDPR, CCPA, HIPAA, SOC 2, ISO 27001)
- Data security architecture and controls
- AI governance and ethical AI practices
- Data quality management and data lifecycle
- Stakeholder engagement and policy development
- Risk assessment and compliance management

You help product managers build comprehensive data governance programs that:
- Protect customer data and privacy
- Ensure regulatory compliance
- Enable data-driven decision making
- Support AI innovation responsibly
- Build customer trust
- Manage data as a strategic asset

Your approach is systematic, covering strategy, organizational design, policies, processes, and implementation roadmaps. You create actionable templates for engaging stakeholders and drafting formal governance policies.

---

## User Message

Help me develop a comprehensive data governance framework for my product through a structured, multi-step process.

**Data Governance Scope:**
- **Data Strategy**: Creating value from data
- **Data Governance**: Policies, processes, standards
- **Data Privacy**: Protecting personal information
- **Data Security**: Technical controls and access
- **AI Governance**: Ethical and responsible AI use

---

## Step 1: Product & Data Context

Please provide the following information systematically:

### Part A: Product Context

| Field | Your Answer |
|-------|-------------|
| **Product Name** | [Name] |
| **Description** | [What it does] |
| **Industry/Vertical** | [Healthcare / Finance / SaaS / E-commerce / etc.] |
| **Product Stage** | Early / Growth / Scaling / Mature |
| **Business Model** | B2B / B2C / B2B2C / Other |
| **Geography** | [Where you operate - affects regulations] |
| **Customer Segments** | [Who uses your product] |

### Part B: Data Landscape

**Data Collection:**

| Data Category | Examples | Sensitivity Level | Collection Method | Volume | Purpose |
|---------------|----------|-------------------|-------------------|--------|---------|
| User Identity | Name, email, phone | High | Registration | [#] | Account management |
| Behavioral | Clicks, views, time | Medium | Analytics | [#] | Product improvement |
| Transaction | Purchases, payments | High | Commerce | [#] | Business operations |
| [Add more] | | | | | |

**Sensitivity Levels:**
- **Public**: No privacy concern (public content)
- **Internal**: Internal use only (aggregated data)
- **Confidential**: Requires protection (PII)
- **Restricted**: Highly sensitive (financial, health)

**Data Sources:**

| Source Type | Examples | Volume | Reliability |
|-------------|----------|--------|-------------|
| Direct User Input | Forms, uploads | [#/day] | High / Medium / Low |
| Behavioral Tracking | Analytics, logs | [#/day] | High / Medium / Low |
| Third-Party APIs | Integrations | [#/day] | High / Medium / Low |
| Generated/Derived | ML outputs | [#/day] | High / Medium / Low |

**Data Usage:**

| Use Case | Data Used | Purpose | Who Accesses | Tools/Systems |
|----------|-----------|---------|--------------|---------------|
| Product Analytics | Behavioral data | Feature optimization | Product team | Mixpanel, Amplitude |
| ML Models | User/behavior data | Recommendations | Data Science | Internal models |
| Customer Support | Profile + activity | Issue resolution | Support team | Zendesk |
| [Add more] | | | | |

**Data Sharing:**

| Recipient | Data Shared | Purpose | Legal Basis | Safeguards |
|-----------|-------------|---------|-------------|------------|
| [Partner/Vendor] | [What data] | [Why] | Contract / Consent | DPA, Encryption |

### Part C: Current Governance State

**Existing Practices:**

| Area | Current State | Maturity Level | Gaps Identified |
|------|---------------|----------------|-----------------|
| **Data Strategy** | [Description] | None / Ad-hoc / Defined / Managed | [Gaps] |
| **Policies** | [What exists] | None / Ad-hoc / Defined / Managed | [Gaps] |
| **Data Ownership** | [Who owns what] | None / Ad-hoc / Defined / Managed | [Gaps] |
| **Data Quality** | [How managed] | None / Ad-hoc / Defined / Managed | [Gaps] |
| **Access Controls** | [Current system] | None / Ad-hoc / Defined / Managed | [Gaps] |
| **Documentation** | [What exists] | None / Ad-hoc / Defined / Managed | [Gaps] |

**Available Resources:**

| Resource Type | Current State |
|---------------|---------------|
| **Data Catalog** | Yes / No / Partial |
| **Data Lineage** | Yes / No / Partial |
| **Data Dictionary** | Yes / No / Partial |
| **Privacy Policies** | Yes / No / Partial |
| **Security Policies** | Yes / No / Partial |
| **Incident Response Plan** | Yes / No / Partial |

### Part D: Compliance & Regulations

**Regulatory Requirements:**

| Regulation | Applies? | Compliance Status | Gaps | Deadline |
|------------|---------|-------------------|------|----------|
| **GDPR** | Yes / No / Partial | Compliant / In Progress / Not Started | [List] | [Date] |
| **CCPA/CPRA** | Yes / No / Partial | Compliant / In Progress / Not Started | [List] | [Date] |
| **HIPAA** | Yes / No / Partial | Compliant / In Progress / Not Started | [List] | [Date] |
| **SOC 2** | Yes / No / Partial | Compliant / In Progress / Not Started | [List] | [Date] |
| **ISO 27001** | Yes / No / Partial | Compliant / In Progress / Not Started | [List] | [Date] |
| **Other** | Yes / No / Partial | Compliant / In Progress / Not Started | [List] | [Date] |

**Compliance History:**

| Item | Details |
|------|---------|
| **Past Incidents** | Yes / No - [Details if yes] |
| **Breaches** | Yes / No - [Details if yes] |
| **Regulatory Actions** | Yes / No - [Details if yes] |
| **Customer Audits** | Frequency, findings |
| **Certifications** | Current certifications |

### Part E: AI & Machine Learning

**AI Usage:**

| AI Capability | Purpose | Model Type | Data Used | Third-Party Service? |
|---------------|---------|------------|-----------|---------------------|
| [e.g., Recommendations] | [Personalization] | [Proprietary/Vendor] | [User behavior] | Yes: [OpenAI/AWS] / No |

**AI Governance Considerations:**

| Question | Answer |
|----------|--------|
| **Do you use AI/ML?** | Yes / No / Planning |
| **AI Use Cases** | [List all uses of AI] |
| **Training Data** | [What data trains models] |
| **User Data in AI** | [Is customer data used for training?] |
| **Third-Party AI** | [Which providers: OpenAI, Anthropic, etc.] |
| **Data Sent to AI** | [What data goes to external services] |
| **AI Transparency** | [Can users see why decisions made?] |
| **User Control** | [Can users opt-out or appeal?] |
| **Bias Testing** | [Do you test for bias?] |
| **Model Monitoring** | [How do you monitor performance?] |

### Part F: Stakeholders & Pain Points

**Key Stakeholders:**

| Stakeholder | Role | Data Governance Interest | Current Pain Points |
|-------------|------|-------------------------|-------------------|
| Data Science Team | Analytics/ML | Data access, quality | [Issues] |
| Engineering Team | Platform | Security, performance | [Issues] |
| Legal/Compliance | Risk management | Regulatory compliance | [Issues] |
| Security/InfoSec | Protection | Threat mitigation | [Issues] |
| Product Leadership | Strategy | Data-driven decisions | [Issues] |
| Customer Success | Support | Customer trust | [Issues] |

**Critical Questions:**

| Question | Current Answer | Desired State |
|----------|----------------|---------------|
| Where is all our data? | [Current visibility] | [Target] |
| Who can access what? | [Current knowledge] | [Target] |
| How is data protected? | [Current state] | [Target] |
| Are we compliant? | [Current status] | [Target] |
| What data quality issues exist? | [Known problems] | [Target] |
| How do we handle user rights? | [Current process] | [Target] |

**Top Concerns:**

1. [Biggest worry about data governance]
2. [Second concern]
3. [Third concern]

---

## Step 2: Requirements & Stakeholder Analysis

After you provide Step 1 information, I'll analyze:

**Internal Requirements:**
- Data Science team needs and workflows
- Engineering platform requirements
- Legal and compliance mandates
- Security and risk requirements
- Business stakeholder needs

**External Requirements:**
- Regulatory compliance obligations
- Customer contractual requirements
- Industry standards and certifications
- Competitive benchmarks
- Customer expectations for privacy and security

**Analysis Outputs:**
- Stakeholder requirement matrix
- Regulatory compliance mapping
- Gap analysis summary
- Priority recommendations

---

## Step 3: Data Governance Framework Design

I'll design a comprehensive framework with these components:

### Framework Components

**1. Data Strategy**

| Element | Description |
|---------|-------------|
| **Strategic Objectives** | How data creates competitive advantage |
| **Data Principles** | Guiding principles for all data decisions |
| **Data Architecture** | Technical foundation and infrastructure |
| **Capability Roadmap** | Data capabilities to build over time |
| **Investment Plan** | Resources required for data initiatives |

**2. Governance Structure**

| Role | Responsibilities | Decision Rights | Accountability |
|------|-----------------|-----------------|----------------|
| **Chief Data Officer** | Overall data strategy | Strategic direction | Board/CEO |
| **Data Governance Council** | Policy oversight | Policy approval | CDO |
| **Data Owners** | Domain accountability | Business rules | Council |
| **Data Stewards** | Tactical management | Quality standards | Data Owner |
| **Data Custodians** | Technical execution | System operations | Data Steward |

**3. Policy Framework**

Core policies to develop:
- Data Classification Policy
- Data Quality Policy
- Data Access Policy
- Data Privacy Policy
- Data Security Policy
- Data Retention Policy
- AI Governance Policy
- Third-Party Data Sharing Policy

**4. Process Framework**

Key processes:
- Data lifecycle management
- Access request and provisioning
- Data quality monitoring
- Privacy impact assessments
- Security incident response
- AI use case approval
- Policy exception handling

---

## Step 4: Stakeholder Engagement Templates

I'll create these ready-to-use templates:

### Template 1: Data Science Team Engagement

**Meeting Agenda & Discussion Guide:**

| Topic | Questions | Desired Outcomes |
|-------|-----------|------------------|
| Current Data Usage | What data do you need? What blockers exist? | Understand requirements |
| Data Quality | What quality issues impact your work? | Identify quality priorities |
| Access Needs | What access do you need? What's the approval process? | Define access model |
| AI Governance | What AI use cases exist/planned? What data is used? | Establish AI governance |
| Tools & Platform | What tools do you need? What's missing? | Platform requirements |

**Collaboration Framework:**

| Process | SLA | Owner | Notes |
|---------|-----|-------|-------|
| Data Access Request | [X days] | [Role] | [Process] |
| Quality Issue Report | [X days] | [Role] | [Process] |
| Model Approval | [X days] | [Role] | [Process] |
| Data Request | [X days] | [Role] | [Process] |

### Template 2: Data Owner Engagement

**Data Inventory Template:**

| Field | Description | Example |
|-------|-------------|---------|
| **Data Domain** | Business area | Customer Data |
| **Data Sets** | Specific tables/files | customer_profile, customer_activity |
| **Data Owner** | Accountable person | VP Customer Success |
| **Data Steward** | Day-to-day manager | Customer Data Analyst |
| **Systems** | Where data lives | PostgreSQL, S3, Redshift |
| **Collection Method** | How acquired | User registration, behavioral tracking |
| **Business Purpose** | Why collected | Account management, personalization |
| **Sensitivity** | Classification level | Confidential (contains PII) |
| **Retention Period** | How long kept | 7 years for accounts, 2 years post-close |
| **Regulatory Requirements** | Applicable rules | GDPR, CCPA |
| **Quality Metrics** | How measured | Completeness >95%, accuracy >98% |
| **Known Issues** | Current problems | Duplicate records, missing emails |
| **Access Patterns** | Who uses it | Product, Support, Marketing teams |

**Responsibility Matrix (RACI):**

| Activity | Data Owner | Data Steward | Data Custodian | Consumer |
|----------|-----------|--------------|----------------|----------|
| Define business rules | A | R | C | I |
| Approve data access | A | C | R | - |
| Monitor data quality | A | R | C | I |
| Resolve quality issues | A | R | C | - |
| Approve retention changes | A | C | R | - |

### Template 3: Security & Legal Alignment

**Security Requirements Checklist:**

| Control Category | Requirement | Current State | Gap | Priority |
|-----------------|-------------|---------------|-----|----------|
| **Access Controls** | MFA for sensitive data | Yes / No / Partial | [Gap] | H/M/L |
| **Encryption** | Data at rest encrypted | Yes / No / Partial | [Gap] | H/M/L |
| **Network Security** | Segmentation implemented | Yes / No / Partial | [Gap] | H/M/L |
| **Monitoring** | Access logging enabled | Yes / No / Partial | [Gap] | H/M/L |
| **Incident Response** | Plan documented | Yes / No / Partial | [Gap] | H/M/L |

**Legal & Compliance Mapping:**

| Requirement | Source | Implementation | Evidence | Owner | Status |
|-------------|--------|----------------|----------|-------|--------|
| Right to Access | GDPR Art. 15 | Self-service portal | Portal + logs | [Name] | ✓ / In Progress |
| Right to Deletion | GDPR Art. 17 | Automated deletion | Process doc | [Name] | ✓ / In Progress |
| Consent Management | GDPR Art. 7 | Consent platform | Consent records | [Name] | ✓ / In Progress |

### Template 4: Executive Briefing

**One-Page Summary Format:**

**SITUATION**
- Current data governance maturity: [Assessment]
- Key risks if not addressed: [Top 3 risks]
- Regulatory/customer pressure: [Context]

**RECOMMENDATION**
- Proposed governance approach: [Summary]
- Expected timeline: [Phases and dates]
- Resource requirements: [People, budget, tools]

**BENEFITS**
- Risk reduction: [Quantified if possible]
- Compliance achievement: [Certifications/status]
- Business enablement: [Data-driven capabilities]
- Competitive advantage: [Market position]

**NEXT STEPS**
1. [Immediate action]
2. [Near-term priority]
3. [Key decision needed]

---

## Step 5: Data Governance Policy Document

I'll help you draft a comprehensive, formal policy document:

### Policy Document Structure

**SECTION 1: EXECUTIVE SUMMARY**

| Element | Content |
|---------|---------|
| **Purpose** | Why this policy exists |
| **Scope** | What/who it covers |
| **Principles** | Core guiding principles |
| **Governance Model** | Organization structure |
| **Key Roles** | Responsibilities summary |

**SECTION 2: DATA STRATEGY**

**Strategic Objectives:**
1. [Objective 1]: [Description and success criteria]
2. [Objective 2]: [Description and success criteria]
3. [Objective 3]: [Description and success criteria]

**Data Principles:**

| Principle | Description | Implications |
|-----------|-------------|--------------|
| **Data as Asset** | Data has value and requires management | Ownership, valuation, investment |
| **Privacy by Design** | Privacy embedded from start | PIA process, minimization |
| **Security First** | Security non-negotiable | Encryption, access controls |
| **Quality Matters** | Data must be fit for purpose | Quality standards, monitoring |
| **Transparency** | Open about data practices | User notices, explainability |
| **Ethical Use** | Responsible and fair practices | Ethics review, bias testing |

**SECTION 3: GOVERNANCE ORGANIZATION**

**Governance Bodies:**

| Body | Mandate | Membership | Meeting Cadence | Decision Authority |
|------|---------|------------|-----------------|-------------------|
| **Data Governance Council** | Strategic oversight | C-suite, VPs | Quarterly | Policy approval |
| **Data Review Board** | Tactical decisions | Directors, Managers | Monthly | Access, quality, exceptions |
| **AI Ethics Board** | AI oversight | Cross-functional | Bi-monthly | AI use case approval |
| **Incident Response Team** | Security incidents | Security, Legal, PR | As needed | Incident response |

**Roles & Responsibilities:**

| Role | Accountabilities | Key Decisions | Reports To |
|------|------------------|---------------|------------|
| **Chief Data Officer** | Data strategy, governance program | Strategic direction | CEO |
| **Data Owner** | Business accountability for domain | Business rules, access policies | CDO |
| **Data Steward** | Tactical data management | Quality standards, issue resolution | Data Owner |
| **Data Custodian** | Technical system operation | Implementation, maintenance | Data Steward |
| **Data Protection Officer** | Privacy compliance | Privacy assessments, breach notification | CEO/Legal |

**SECTION 4: DATA CLASSIFICATION POLICY**

**Classification Scheme:**

| Level | Definition | Examples | Handling Requirements |
|-------|------------|----------|---------------------|
| **Restricted** | Highly sensitive, severe impact if disclosed | SSN, financial account numbers, health records | Encryption required, minimal access, audit all activity |
| **Confidential** | Sensitive, significant impact if disclosed | PII, business plans, customer lists | Encryption recommended, role-based access, regular reviews |
| **Internal** | Internal only, moderate impact | Employee data, internal reports | Standard security, authenticated access |
| **Public** | No restrictions | Marketing content, public docs | No restrictions |

**Classification Process:**
1. Data owner assigns classification based on sensitivity
2. Data steward applies appropriate controls
3. Classification reviewed annually or upon significant change

**SECTION 5: DATA QUALITY POLICY**

**Quality Dimensions & Standards:**

| Dimension | Definition | Standard | Measurement | Owner |
|-----------|------------|----------|-------------|-------|
| **Accuracy** | Data is correct | >98% | Validation checks, audits | Data Steward |
| **Completeness** | No missing values | >95% | Null checks | Data Steward |
| **Consistency** | Same across systems | >99% | Cross-system reconciliation | Data Custodian |
| **Timeliness** | Current and up-to-date | <24h lag | Freshness checks | Data Custodian |
| **Validity** | Conforms to business rules | 100% | Rule validation | Data Steward |
| **Uniqueness** | No duplicates | >99% | Deduplication checks | Data Custodian |

**Quality Processes:**
- Profiling: Assess data quality baseline
- Validation: Check conformance to rules
- Monitoring: Track quality metrics
- Remediation: Fix quality issues
- Reporting: Dashboard and alerts

**SECTION 6: DATA ACCESS POLICY**

**Access Principles:**
- Least privilege (minimum necessary)
- Need-to-know (business justification required)
- Segregation of duties (no single person has all access)
- Time-bound (access expires, requires renewal)

**Access Control Model:**

| Access Type | Requirements | Approval | Review Frequency |
|-------------|--------------|----------|------------------|
| **Read - Public Data** | Employee status | Manager | Annual |
| **Read - Internal Data** | Business justification | Data Owner | Quarterly |
| **Read - Confidential** | Explicit need, training | Data Owner + Security | Monthly |
| **Read - Restricted** | Exceptional justification | Data Owner + Legal + Security | Weekly |
| **Write - Any Level** | Explicit need, training | Data Owner + Security | Monthly |
| **Admin - Any System** | Critical need, training | CTO + CISO | Weekly |

**Access Request Process:**
1. Requester submits business justification
2. Manager approves business need
3. Data Owner approves data access
4. Security approves technical access
5. Access provisioned with expiration
6. Regular review and recertification

**SECTION 7: DATA PRIVACY POLICY**

**Privacy Principles:**

| Principle | Commitment | Implementation |
|-----------|------------|----------------|
| **Transparency** | Clear notice of data practices | Privacy policy, in-product notices |
| **Consent & Choice** | User control over data | Granular consent, opt-out options |
| **Data Minimization** | Collect only what's needed | Purpose limitation, collection review |
| **Purpose Limitation** | Use only for stated purpose | Usage audits, secondary use review |
| **Access & Correction** | Users can access and fix data | Self-service portal |
| **Security** | Protect personal data | Encryption, access controls |
| **Retention Limits** | Keep only as long as needed | Retention schedules, auto-deletion |

**User Rights Management:**

| Right | Requirement | Process | SLA | Owner |
|-------|-------------|---------|-----|-------|
| **Right to Access** | Provide copy of data | Self-service portal or email request | 30 days | Data Steward |
| **Right to Rectification** | Fix incorrect data | Self-service or support ticket | 15 days | Data Steward |
| **Right to Deletion** | Delete upon request | Automated deletion + manual verification | 30 days | Data Custodian |
| **Right to Portability** | Export data in standard format | Automated export | 30 days | Data Custodian |
| **Right to Object** | Opt-out of processing | Preference center | Immediate | Engineering |
| **Right to Restrict** | Limit processing | Flagging system | Immediate | Engineering |

**Privacy Impact Assessment (PIA):**

Required when:
- New data collection initiated
- Significant change to data use
- New technology processing personal data
- High risk to individual rights
- AI/automated decision-making introduced

PIA Process:
1. Identify privacy risks
2. Assess impact and likelihood
3. Identify mitigation measures
4. Document assessment
5. DPO review and approval
6. Regular reassessment

**SECTION 8: DATA SECURITY POLICY**

**Security Standards:**

**Access Controls:**
- Multi-factor authentication (MFA) required for all access
- Single sign-on (SSO) for identity management
- Role-based access control (RBAC) for authorization
- Privileged access management (PAM) for admin rights
- Just-in-time (JIT) access for temporary elevated rights

**Encryption:**
- All data at rest encrypted (AES-256 minimum)
- All data in transit encrypted (TLS 1.2+ minimum)
- End-to-end encryption for highly sensitive data
- Key management via dedicated KMS
- Regular key rotation

**Network Security:**
- Network segmentation by data sensitivity
- Firewall rules limiting access
- VPN required for remote access
- DDoS protection
- Intrusion detection/prevention systems

**Application Security:**
- Secure development lifecycle (SSDLC)
- Code review and static analysis
- Dynamic application security testing (DAST)
- Penetration testing annually
- Bug bounty program

**Monitoring & Logging:**

| Activity | Logged | Retention | Review Frequency |
|----------|--------|-----------|------------------|
| Data access (read) | Yes | 1 year | Weekly (automated alerts) |
| Data modification | Yes | 3 years | Daily (automated alerts) |
| Data export | Yes | 3 years | Daily (manual review) |
| Permission changes | Yes | 5 years | Daily (manual review) |
| Authentication events | Yes | 1 year | Real-time (automated alerts) |
| Admin actions | Yes | 5 years | Daily (manual review) |

**Incident Response:**

**Incident Classification:**
- **Critical**: Confirmed breach of restricted data
- **High**: Suspected breach or confidential data compromise
- **Medium**: Security control failure
- **Low**: Potential vulnerability

**Response Procedures:**

| Phase | Activities | Timeline | Owner |
|-------|-----------|----------|-------|
| **Detection** | Identify and triage | Immediate | Security Team |
| **Containment** | Limit damage, preserve evidence | 1 hour | Security Team |
| **Investigation** | Root cause analysis | 24 hours | Security + Legal |
| **Notification** | Internal, regulatory, customer | 72 hours | Legal + PR |
| **Remediation** | Fix root cause | Varies | Engineering |
| **Review** | Post-incident analysis | 1 week | Security + Leadership |

**SECTION 9: AI GOVERNANCE POLICY**

**AI Governance Principles:**

| Principle | Description | Requirements |
|-----------|-------------|--------------|
| **Transparency** | Clear about AI use | Disclose AI involvement |
| **Explainability** | Understandable decisions | Document decision logic |
| **Fairness** | No discriminatory outcomes | Bias testing required |
| **Accountability** | Human oversight | Human-in-the-loop for critical |
| **Privacy** | Protect user data | Privacy-preserving techniques |
| **Safety** | Safe and reliable | Testing, monitoring, fail-safes |

**AI Use Case Approval Process:**

| Step | Activity | Approval Required | Documentation |
|------|----------|-------------------|---------------|
| 1 | Business case | Product Leader | Use case description |
| 2 | Privacy assessment | DPO | Privacy Impact Assessment |
| 3 | Fairness review | AI Ethics Board | Bias testing plan & results |
| 4 | Security review | CISO | Security controls |
| 5 | Risk assessment | Risk Committee | Risk analysis & mitigation |
| 6 | Final approval | Data Governance Council | Complete package |

**Model Governance:**

**Model Development Standards:**
- Training data documented (sources, lineage, quality)
- Model architecture documented
- Hyperparameters and training process documented
- Performance metrics defined and measured
- Bias and fairness testing completed
- Security testing completed
- Model card created

**Model Monitoring:**
- Performance tracking (accuracy, latency)
- Drift detection (data drift, concept drift)
- Fairness monitoring (disparate impact)
- Error analysis and debugging
- User feedback collection
- Regular retraining and updates

**Model Versioning:**
- Version control for all models
- Change log documenting updates
- Rollback capability
- A/B testing for model changes
- Deprecation and sunsetting process

**Third-Party AI Services:**

**Vendor Evaluation:**

| Criteria | Required | Validation |
|----------|----------|------------|
| **Privacy commitment** | Data not used for training | Contract terms |
| **Security standards** | SOC 2 Type II minimum | Audit report |
| **Data residency** | Compliance with requirements | Architecture review |
| **Subprocessor list** | Disclosed and approved | Contract + monitoring |
| **Audit rights** | Right to audit | Contract terms |
| **Exit strategy** | Data return/deletion | Contract terms |

**Data Sharing Agreements:**
- Purpose limitation (specific use case only)
- Retention limits (delete after processing)
- Security requirements (encryption, access controls)
- Subprocessor restrictions (prior approval)
- Liability and indemnification
- Termination and data return

**AI-Specific User Rights:**
- Notification of AI involvement
- Explanation of AI decisions (when requested)
- Opt-out option (human alternative)
- Contestability (appeal process)
- Consent for AI training (if applicable)

**SECTION 10: DATA RETENTION & DELETION POLICY**

**Retention Principles:**
- Keep data only as long as needed for purpose
- Legal and regulatory requirements override business need
- Secure deletion when retention period expires
- Regular review and update of retention schedules

**Retention Schedule:**

| Data Category | Retention Period | Trigger | Deletion Method | Legal Basis |
|---------------|------------------|---------|-----------------|-------------|
| Customer Account Data | Active + 7 years | Account closure | Secure deletion | Legal requirement |
| Behavioral Data | Active + 2 years | Last activity | Anonymization | Business need |
| Transaction Records | Active + 10 years | Transaction date | Archive then delete | Tax law |
| Support Tickets | Active + 3 years | Ticket close | Secure deletion | Business need |
| Access Logs | 1 year | Creation date | Automated deletion | Security policy |
| AI Training Data | Model lifetime | Model decommission | Secure deletion | Business need |

**Deletion Process:**
1. Identify data past retention period (automated)
2. Verify no legal hold or dispute (manual check)
3. Execute deletion (automated with logging)
4. Verify deletion complete (validation check)
5. Document deletion (audit trail)

**Legal Holds:**
- Legal team can place hold on data
- Hold prevents automated deletion
- Hold tracked and reviewed monthly
- Hold released when matter resolved

**SECTION 11: IMPLEMENTATION ROADMAP**

**Phase 1: Foundation (Months 1-3)**

| Milestone | Activities | Deliverables | Owner |
|-----------|-----------|--------------|-------|
| Governance Setup | Form council, define roles, charter | Governance charter, RACI | CDO |
| Data Inventory | Catalog all data, classify sensitivity | Data inventory, classification | Data Owners |
| Gap Assessment | Audit current vs. required state | Gap analysis report | Compliance |
| Quick Wins | Fix critical gaps, low-hanging fruit | Remediation list | All |

**Phase 2: Core Policies (Months 4-6)**

| Milestone | Activities | Deliverables | Owner |
|-----------|-----------|--------------|-------|
| Policy Development | Draft and approve policies | Policy suite | CDO + Council |
| Access Control | Implement RBAC, review processes | Access control system | Security |
| Privacy Compliance | Implement user rights, consent | Privacy portal | Engineering |
| Training Program | Develop and deliver training | Training materials | HR + CDO |

**Phase 3: Operationalization (Months 7-9)**

| Milestone | Activities | Deliverables | Owner |
|-----------|-----------|--------------|-------|
| Quality Program | Deploy monitoring, remediation | Quality dashboard | Data Stewards |
| Security Hardening | Encryption, monitoring, logging | Security controls | Security |
| AI Governance | Implement approval, monitoring | AI governance system | AI Ethics Board |
| Tooling | Deploy governance platform | Governance tools | IT |

**Phase 4: Optimization (Months 10-12)**

| Milestone | Activities | Deliverables | Owner |
|-----------|-----------|--------------|-------|
| Automation | Automate manual processes | Workflow automation | Engineering |
| Certification | Achieve SOC 2, ISO, etc. | Certifications | Compliance |
| Maturity | Measure and improve processes | Maturity assessment | CDO |
| Continuous Improvement | Establish ongoing optimization | Improvement plan | Council |

**SECTION 12: ROLES & RESPONSIBILITIES (RACI)**

**RACI Matrix for Key Activities:**

| Activity | CDO | Data Owner | Data Steward | Data Custodian | Security | Legal | DPO |
|----------|-----|-----------|--------------|----------------|----------|-------|-----|
| **Strategy Development** | A | C | I | I | C | C | C |
| **Policy Approval** | A/R | C | C | I | C | C | C |
| **Data Classification** | I | A | R | C | C | C | C |
| **Access Provisioning** | I | A | C | R | C | I | I |
| **Quality Monitoring** | I | A | R | C | I | I | I |
| **Privacy Assessment** | C | C | C | I | C | C | A/R |
| **Security Incident** | I | I | I | C | A/R | C | C |
| **AI Use Case Approval** | A | C | C | I | C | C | C |
| **Compliance Reporting** | R | C | C | I | C | A | R |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (decision authority)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

**SECTION 13: COMPLIANCE & AUDIT**

**Compliance Monitoring:**

| Metric | Target | Frequency | Owner | Escalation |
|--------|--------|-----------|-------|------------|
| Policy adherence | 100% | Monthly | Compliance | Council |
| Access reviews completed | 100% | Quarterly | Security | CISO |
| Training completion | 100% | Annual | HR | CDO |
| Privacy requests responded | 100% within SLA | Weekly | Data Stewards | DPO |
| Data quality scores | >95% | Weekly | Data Stewards | Data Owner |
| Security incidents | 0 critical | Real-time | Security | CISO |

**Audit Program:**

| Audit Type | Frequency | Scope | Auditor | Findings Review |
|------------|-----------|-------|---------|-----------------|
| **Internal Data Audit** | Quarterly | Sample of data domains | Internal Audit | Governance Council |
| **Security Audit** | Semi-annual | Technical controls | Security Team | CISO + Council |
| **Compliance Audit** | Annual | Regulatory requirements | External Auditor | Board |
| **AI Ethics Audit** | Semi-annual | AI use cases and models | AI Ethics Board | Council |

**SECTION 14: TRAINING & AWARENESS**

**Training Programs:**

| Audience | Program | Frequency | Content | Duration |
|----------|---------|-----------|---------|----------|
| **All Employees** | Data Governance 101 | Onboarding + Annual | Policies, responsibilities, basics | 30 min |
| **Data Owners** | Data Ownership | Onboarding + Annual | Ownership duties, decisions | 2 hours |
| **Data Stewards** | Data Stewardship | Onboarding + Quarterly | Quality, metadata, issues | 4 hours |
| **Data Consumers** | Responsible Data Use | Annual | Access, usage, ethics | 1 hour |
| **Developers** | Secure Coding & Privacy | Onboarding + Annual | SSDLC, privacy by design | 3 hours |
| **Data Scientists** | AI Ethics & Governance | Onboarding + Annual | Bias, fairness, responsible AI | 2 hours |
| **Leadership** | Governance Strategy | Annual | Strategy, risks, value | 1 hour |

**SECTION 15: CONTINUOUS IMPROVEMENT**

**Review Cadence:**

| Review Type | Frequency | Participants | Focus | Output |
|-------------|-----------|--------------|-------|--------|
| **Metrics Review** | Monthly | Governance Council | KPIs, trends, issues | Action items |
| **Policy Review** | Semi-annual | Council + stakeholders | Policy effectiveness | Updates |
| **Comprehensive Review** | Annual | All stakeholders | End-to-end assessment | Strategic plan |
| **Incident Review** | As needed | Incident team | Lessons learned | Improvements |

**Improvement Process:**
1. Identify gap or opportunity
2. Document improvement proposal
3. Assess impact and effort
4. Council approval
5. Implementation
6. Effectiveness measurement

**SECTION 16: APPENDICES**

**A. Glossary**
- Definitions of key terms

**B. Regulatory Summary**
- Requirements from each applicable regulation

**C. Data Classification Guide**
- Detailed guidance on classifying data

**D. Privacy Notice Templates**
- Standard templates for user-facing notices

**E. Consent Form Templates**
- Templates for collecting consent

**F. Data Processing Agreements**
- Standard DPA templates

**G. Incident Response Playbooks**
- Step-by-step procedures for incidents

**H. AI Model Card Template**
- Template for documenting models

**I. Privacy Impact Assessment Template**
- PIA questionnaire and process

**J. Access Request Form**
- Standard form for requesting data access

---

## Getting Started

**Please provide the information from Step 1: Product & Data Context.**

Complete the tables with as much detail as possible. The more context you provide, the more tailored and actionable your data governance framework will be.

**Minimum Required:**
- Product description and industry
- Main categories of data collected
- Sensitive data types (PII, financial, health)
- Applicable regulations
- Current governance maturity
- AI usage (if any)
- Top 1-2 concerns

**Comprehensive Preferred:**
- All Step 1 tables completed
- Specific data volumes and sources
- Detailed stakeholder information
- Known gaps and issues
- Compliance status

---

**Ready? Please share your product and data context from Step 1!**
