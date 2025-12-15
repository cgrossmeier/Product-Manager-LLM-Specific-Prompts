# KPI Development - Simplified

**Platform:** ChatGPT (GPT-4 / GPT-5)

---

## System Message

You are an expert product analytics consultant specializing in KPI (Key Performance Indicator) development. You help product managers establish the right metrics to monitor business health and performance.

Your process:
1. Gather product and business context efficiently
2. Ask targeted questions about priorities and data
3. Recommend appropriate KPI framework
4. Identify 15-20 relevant KPIs across categories
5. Help prioritize into primary and secondary metrics
6. Create comprehensive KPI Reference Document

You ensure KPIs are:
- **Measurable**: Clear calculation methods
- **Actionable**: Can be influenced by team actions
- **Relevant**: Tied to business health and strategy
- **Timely**: Updated frequently enough to be useful
- **Accurate**: Reliable data sources

---

## User Message

Help me establish KPIs to monitor my product's health through a step-by-step process.

**KPI Definition:**
- **Purpose**: Monitor ongoing business performance
- **Nature**: Specific metrics (e.g., "Monthly Churn Rate", "DAU/MAU Ratio")
- **Focus**: Current state and historical trends
- **Tracking**: Continuous monitoring, regular reporting

---

## Step 1: Product & Business Context

Please provide the following information:

### Product Information

| Field | Your Answer |
|-------|-------------|
| **Product Name** | [Name] |
| **Description** | [What it does in 1 sentence] |
| **Product Type** | SaaS / Marketplace / E-commerce / Mobile / Other |
| **Stage** | Early / Growth / Scaling / Mature |

### Business Model

| Field | Your Answer |
|-------|-------------|
| **Revenue Model** | [How you make money] |
| **Primary Revenue Stream** | [Main revenue source] |
| **Pricing Structure** | Subscription / Usage / Transaction / Freemium |
| **Current Revenue** | [MRR/ARR or "Pre-revenue"] |

### Customer Information

| Field | Your Answer |
|-------|-------------|
| **Primary Customer** | [Role, company type] |
| **Customer Count** | [Approximate number] |
| **Average Contract Value** | [$ amount or range] |
| **Main Acquisition Channel** | [How they find you] |
| **Typical Customer Lifetime** | [Months/years they stay] |

### Product Usage

| Field | Your Answer |
|-------|-------------|
| **Primary Use Case** | [Main way customers use product] |
| **Active User Definition** | [What makes someone "active"] |
| **Usage Frequency** | Daily / Weekly / Monthly |
| **Current Active Users** | [MAU, DAU, or similar] |
| **Retention Pattern** | [% who return Day 7, Day 30] |

### Current Tracking

| Field | Your Answer |
|-------|-------------|
| **Metrics Tracked Now** | [What you currently monitor] |
| **Analytics Tools** | [Google Analytics, Mixpanel, etc.] |
| **Data Sources** | [Databases, systems available] |
| **Reporting To** | [Who needs these metrics] |

### Strategic Context

| Field | Your Answer |
|-------|-------------|
| **Top Business Priority** | [Main focus right now] |
| **Biggest Unknown** | [What you can't answer] |
| **Key Question** | [What you need to understand] |
| **Decision Blockers** | [What data would help decisions] |

---

## Step 2: Clarifying Questions

After you provide Step 1 info, I'll ask 3-5 focused questions about:
- Areas needing most visibility
- Data availability and accuracy
- Reporting cadence preferences
- Audience needs (team, exec, board)

---

## Step 3: Framework Recommendation

I'll recommend the best KPI framework for your situation:

### Framework Options

| Framework | Best For | Structure |
|-----------|----------|-----------|
| **AARRR (Pirate Metrics)** | Growth-focused products | Acquisition → Activation → Retention → Revenue → Referral |
| **North Star Framework** | Alignment and focus | 1 North Star + Input Metrics + Health Metrics |
| **Business Health Dashboard** | Comprehensive monitoring | Growth / Engagement / Revenue / Efficiency |
| **Dave McClure's 5 Metrics** | SaaS products | ARR, MRR, Churn, CAC, LTV |

**Recommendation:**
I'll suggest the best framework for your product type, stage, and priorities with rationale.

---

## Step 4: KPI Identification

I'll provide 15-20 relevant KPIs organized by category:

### KPI Format

| KPI | Definition | Formula | Target | Frequency | Priority |
|-----|------------|---------|--------|-----------|----------|
| [Metric Name] | [What it measures] | [Calculation] | [Goal] | D/W/M | Primary/Secondary |

### Categories

**Primary KPIs (5-7)**
Your core dashboard - monitor daily/weekly

**Growth Metrics**
- User signups
- Conversion rate
- Growth rate (MoM/QoQ)
- Traffic sources

**Engagement Metrics**
- Daily Active Users (DAU)
- Monthly Active Users (MAU)
- DAU/MAU ratio (stickiness)
- Session frequency
- Feature adoption rate

**Retention Metrics**
- Day 1, Day 7, Day 30 retention
- Cohort retention curves
- Churn rate (user and revenue)
- Logo retention

**Revenue Metrics**
- Monthly Recurring Revenue (MRR)
- Annual Recurring Revenue (ARR)
- Average Revenue Per User (ARPU)
- Revenue growth rate
- Contraction vs. expansion

**Unit Economics**
- Customer Acquisition Cost (CAC)
- Lifetime Value (LTV)
- LTV:CAC ratio
- Payback period
- Gross margin

**Product Health**
- System uptime
- Error rate
- Page load time
- Bug count
- Support ticket volume

**Customer Success**
- Net Promoter Score (NPS)
- Customer Satisfaction (CSAT)
- Support resolution time
- Time to value
- Feature request volume

---

## Step 5: Prioritization

I'll help you categorize KPIs:

### Primary KPIs (5-7 metrics)

| KPI | Why Primary | Check Frequency | Owner |
|-----|-------------|-----------------|-------|
| [Metric] | [Critical to business health] | Daily/Weekly | [Person] |

**Criteria for Primary:**
- Strategic importance (ties to key goals)
- Actionability (you can influence it)
- Leading indicator (predicts future)
- Executive visibility (leadership cares)

### Secondary KPIs (10-15 metrics)

| KPI | Purpose | Check Frequency | Use Case |
|-----|---------|-----------------|----------|
| [Metric] | [What it reveals] | Weekly/Monthly | [When to check] |

### Diagnostic Metrics

When primary KPIs change, investigate these:
- [Segmentation metrics]
- [Drill-down metrics]
- [Root cause indicators]

---

## Step 6: KPI Reference Document

I'll create a comprehensive reference document:

### Document Structure

**1. Executive Dashboard**

**Primary KPIs at a Glance:**

| KPI | Current | Target | Last Period | Trend | Status |
|-----|---------|--------|-------------|-------|--------|
| [KPI 1] | [Value] | [Goal] | [Previous] | ↑↓→ | 🟢🟡🔴 |

**Status Guide:**
- 🟢 Green: On target or improving
- 🟡 Yellow: Caution, slowing
- 🔴 Red: Below threshold, action needed

**2. Complete KPI Catalog**

For each KPI:

| Element | Details |
|---------|---------|
| **KPI Name** | [Clear, descriptive name] |
| **Definition** | [What this measures in plain language] |
| **Formula** | [Exact calculation with example] |
| **Data Source** | [System/tool where data lives] |
| **Owner** | [Person responsible for this metric] |
| **Category** | Growth / Engagement / Revenue / Health |
| **Update Frequency** | Daily / Weekly / Monthly |
| **Current Baseline** | [Where you are today] |
| **Target** | [Where you want to be] |
| **Industry Benchmark** | [Typical for your stage/type] |
| **Why It Matters** | [Business impact] |
| **What Influences It** | [Levers you can pull] |
| **Good Looks Like** | [Success indicators] |
| **Bad Looks Like** | [Warning signs] |
| **Related Metrics** | [What else to check] |

**3. Measurement Framework**

**Data Collection:**

| KPI | Source System | Extraction Method | Calculation Steps | Validation |
|-----|---------------|-------------------|-------------------|------------|
| [KPI] | [Tool/DB] | [API/Manual/Auto] | [1. 2. 3.] | [Check method] |

**Automation Status:**

| KPI | Automated? | Tool/Script | Update Cadence | Manual Steps |
|-----|-----------|-------------|----------------|--------------|
| [KPI] | Yes/No/Partial | [Technology] | [Frequency] | [If needed] |

**4. Dashboard Templates**

**Daily Operations Dashboard:**
- Critical health metrics (3-5)
- 5-minute morning check format
- Red flag alerts

**Weekly Team Dashboard:**
- Key metrics for team review
- Progress vs. targets
- Trend indicators
- Action items

**Monthly Business Review:**
- Comprehensive metric set
- MoM comparison
- Quarterly trend
- Strategic insights

**Quarterly Board Metrics:**
- High-level KPIs only
- Strategic context
- Competitive benchmarks
- Forward guidance

**5. Best Practices for Your Product**

**Industry Benchmarks:**

| Product Type | Stage | Key Metrics | Typical Range |
|--------------|-------|-------------|---------------|
| [Your type] | [Your stage] | [Metric] | [Benchmark] |

**Interpretation Guide:**

| Metric | Good Trend | Warning Sign | Critical Alert |
|--------|-----------|--------------|----------------|
| [KPI] | [Pattern] | [Pattern] | [Pattern] |

**Common Pitfalls:**
- **Vanity Metrics**: [Metrics that look good but don't drive decisions]
- **Gaming Risks**: [How metrics can be manipulated]
- **Data Quality**: [Known accuracy issues]
- **Misinterpretation**: [Common mistakes reading data]

**Segmentation Strategy:**
- Customer segments to track separately
- Key cohorts to analyze
- When to aggregate vs. drill down

**6. Action Playbooks**

For each primary KPI:

**[KPI Name] Playbook:**

**If Trending Up ↑:**
- **Meaning**: [What this indicates]
- **Investigate**: [What to check next]
- **Action**: [What to do]
- **Share With**: [Who needs to know]

**If Trending Down ↓:**
- **Root Causes**: [Common reasons]
- **Diagnose With**: [Metrics to check]
- **Corrective Actions**: [What to try]
- **Escalation**: [When to alert leadership]

**If Flat/Stagnant →:**
- **Possible Reasons**: [Why stuck]
- **Experiments**: [What to test]
- **Alternative Levers**: [Different approaches]

**7. Review Cadences**

**Daily Check (5 min):**
```
Priority: Critical health metrics
Format: Dashboard glance
Actions: Flag anomalies only
```

**Weekly Team Review (30 min):**
```
Agenda:
1. Primary KPI status (10 min)
2. Trend analysis (10 min)
3. Action items (10 min)

Decision Template:
- What's working? Keep doing
- What's not? Adjust
- What's missing? Investigate
```

**Monthly Business Review (60 min):**
```
Structure:
1. Executive summary (5 min)
2. Deep dive on changes (20 min)
3. Segment/cohort analysis (15 min)
4. Strategic adjustments (20 min)

Outputs:
- Metric trends and insights
- Resource reallocation decisions
- Priorities for next month
```

**Quarterly KPI Review:**
```
Purpose: Evaluate KPI effectiveness
Questions:
- Are we tracking the right things?
- Are targets still appropriate?
- Are metrics actionable?
- What should we add/remove?
```

**8. Continuous Improvement**

**When to Add KPIs:**
- New strategic priority emerges
- Blind spot discovered
- New capability launched
- Market conditions change

**When to Remove KPIs:**
- No longer actionable
- Becomes vanity metric
- Data not reliable
- Not influencing decisions

**KPI Evolution Roadmap:**
- Near-term additions (next quarter)
- Measurement improvements needed
- Automation opportunities
- Advanced analytics to build

---

## Getting Started

**Please provide the information requested in Step 1.**

**Minimum to Begin:**
- Product description
- Business model
- Current scale (users/revenue)
- Top monitoring priority

**Full Context Preferred:**
- Complete tables from Step 1
- Specific numbers where possible
- Current metrics tracked
- Key questions to answer

---

## Quick Start Example

For rapid setup, use this format:

```
Product: [Name] - [brief description]
Model: [How you make money]
Scale: [Users and revenue]
Priority: [What matters most to track]
Unknown: [Biggest data gap]
```

**Sample:**
```
Product: InboxAI - email productivity assistant for sales reps
Model: SaaS at $15/mo per user, freemium with 14-day trial
Scale: 5,000 users, $48K MRR, 18% monthly growth
Priority: Understanding what drives conversion from trial to paid
Unknown: Why some power users don't convert despite high engagement
```

From this, I'll identify the most critical KPIs and build your monitoring framework!

---

**Ready? Please share your product information from Step 1!**
