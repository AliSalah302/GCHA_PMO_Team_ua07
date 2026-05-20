## Security Documentation Decision

Decision: Reject the vendor offer.

Justification:
Skipping security documentation increases residual risk and weakens administrative performance quality.
Without documentation, compliance verification and audit tracing become impossible in case of a security breach.
Long-term regulatory and financial risks outweigh the short-term schedule benefit.

---
Chapter 2: Buy vs Build Decision Log

 Decision 002: Cairo Infrastructure Strategy

Date: [Today's Date]

Decision Maker: Team XX London PMO

Context:
Cairo data center cannot support the AI engine computational load.

---

 Options Analyzed

 Option 1: Build (Upgrade Cairo Servers)

Upfront Cost: $2,000,000

Ongoing Cost: $0

Delay: 6 months for procurement and installation

---

 Option 2: Buy (Cloud Provider)

Upfront Cost: $0

Ongoing Cost: $500,000 per year

Available immediately

---

 Decision

Option 1: Build (Upgrade Cairo Servers)

---

 Justification

We choose the Build option because Egyptian data sovereignty laws require sensitive medical data to remain inside the country. Building local infrastructure ensures compliance and provides full control over the data. In the long term, the total cost of Build is also lower than cloud subscription services.

---

 Risk Mitigation

- Allocate additional budget for infrastructure upgrade
- Ensure proper server capacity planning
- Implement backup systems for reliability

---

Approved by: Team XX

Next Review: [Date]


---

# Decisions Log - GCHA Project

## Decision: CEO Acceleration Request - AI Model Training (Berlin)
**Date:** 2026-05-07
**Trigger:** CEO requests 1-week compression of Berlin Critical Path task

**Options Considered:**
1. Crashing (Berlin overtime)
2. Fast-Tracking (Bangalore starts at 80% AI completion)

**Decision:** Crashing

**Justification:**
We chose Crashing over Fast-Tracking because authorizing overtime for the existing Berlin team avoids the rework risk of fast-tracking. Per Brooks's Law, adding new developers at this stage would increase communication overhead and likely delay the task further.

---

## CCB Meeting - GDPR 2.0 Response
[cite_start]**Date:** 2026-05-07 [cite: 283]
**Trigger:** EU announces GDPR 2.0. [cite_start]Berlin database architecture is non-compliant. [cite: 284]
[cite_start]**Risk ID:** RISK-D (RE = $50,000 pre-event; now Probability = 100%) [cite: 284]

### Options Considered
| Option | Cost | Delay | Risk |
| :--- | :--- | :--- | :--- |
| Full Redesign | $200,000 | 4 weeks | Safe - 100% compliant |
| Patch Fix | $500,000 | 1 week | [cite_start]30% chance of failing legal audit | [cite: 286, 287, 288]

### [cite_start]Decision: Approved [cite: 289]
[cite_start]**Selected Option:** Full Redesign [cite: 290]

### Justification
Approved. The Risk Exposure of a $50M regulatory fine (RE = $50M x 100% = $50M) far exceeds the $200,000 cost of full redesign and the 4-week schedule delay. [cite_start]Per the CCB Impact Analysis, the schedule delay is absorbable using existing float and Contingency Buffer, making the Full Redesign the only financially rational choice. [cite: 294]

---

## Conflict Resolution Case #1
 ## Chapter 7 **Date:** 2026-05-07
: Documentation Standard War
**Participants:** Berlin Lead, Cairo Lead, PM/Mediator

**The Conflict:**
Berlin refuses to use the Cairo documentation template. Cairo requires a standardized format for GDPR compliance audits.

**Leadership Style Used:** Facilitator

**The Resolution:**
We agreed to adopt a hybrid template: Cairo's compliance fields (Risk ID, Data Classification, Audit Trail) are required for all documents. Berlin may add their technical precision fields as optional appendices.

**The New SOP:**
All GCHA deliverable documents must use the GCHA-Standard-Template-v2.md, located in the Strategic_Artifacts folder. Effective from: 2026-05-07. No exceptions without a formal Change Request.

**Tuckman Stage Outcome:**
This resolution moves the team from Storming -> Norming. The SOP prevents this same conflict from recurring.
---
## Decision Log: The Berlin AI Pivot
## Chapter 8 | Date: 2026-05-07 | Decision-Maker: London PMO

### The Situation
Berlin's AI module has a CPI of 0.50, meaning $2M has been spent to deliver only $1M of value. [cite_start]An external vendor has offered to complete the module for $600,000 fixed-price. [cite: 163, 164]

### Options Considered
| Option | Description | Projected Cost to Complete |
| :--- | :--- | :--- |
| A: Continue Internal | Berlin team continues with current approach | ~$1,000,000 |
| B: Outsource to Vendor | External Health-AI firm completes the module | $600,000 |
| C: Descope | Remove AI module from Phase 1 entirely | $0 |

### Decision: OPTION B Outsource to External Vendor
**Reasoning:**
We are choosing Option B: outsource the Berlin AI module to the external Health-AI vendor for $600,000. This decision saves approximately $400,000 compared to continuing with the internal team at their current CPI of 0.50. [cite_start]The vendor carries significantly lower execution risk. [cite: 174]

### Why the $2M Already Spent Does NOT Factor Into This Decision
**The Sunk Cost Principle:**
[cite_start]The $2,000,000 already spent on the Berlin AI module is a Sunk Cost; it has been paid and cannot be recovered regardless of which option we choose. [cite: 177, 178]
* **Correct reasoning:** The $2M is irrelevant to this decision. It is gone either way. [cite_start]The only relevant question is: which option produces the best outcome from this moment forward? [cite: 182, 183]

### Impact on Project Baseline
* [cite_start]**ETC revised:** Internal $1M -> Vendor $600K = saving of $400,000 [cite: 188]
* [cite_start]**Revised EAC:** $14,270,000 [cite: 190]
* [cite_start]**Berlin RAG Status:** Moving from RED to AMBER (vendor onboarding phase) [cite: 191, 192]

### Tuckman Note
This pivot will create a Storming-equivalent disruption in Berlin. [cite_start]The PM must communicate this change directly and professionally. [cite: 195, 196]

---

## APQ Review - Sprint 4
## Date: [May 21, 2026] | Reviewed by: London PMO

### Velocity Observation
**Bangalore Velocity Trend (last 4 sprints):**
**Bangalore Velocity Trend (last 4 sprints):**
Sprint 1: 45 points | Sprint 2: 42 points | Sprint 3: 46 points | Sprint 4: 44 points

**Trend:** Stable

**Root Cause Analysis:**
Bangalore's velocity has remained stable across 4 sprints, indicating that the current administrative structure – regular standups, clear sprint goals, and Cairo's 48-hour response improvement – is supporting consistent productive output.

### Burnout Risk Assessment
**Current Overtime Status:**
* **Average Overtime:** [e.g., 3 hours] hours per developer per week (from Jira logged hours).
* **APQ Standard:** < 5 hours overtime per week per developer.
* **Status:** 🟢 Green (≤ 5 hrs)

---

### Corrective Actions to Reduce Burnout While Maintaining Quality for Berlin Summit
* **Action 1:** Introduce "no-meeting blocks" and move non-critical documentation tasks to the next sprint to reduce cognitive load on the team.
* **Action 2:** Automate the test coverage check so developers don't spend time writing reports manually, utilizing a shared test script library to save individual test writing time.

---

### Link Between APQ and Product Quality
**The Critical Insight:**
When Administrative Performance Quality (APQ) degrades — through burnout, Requirement Volatility, or communication latency — the Defect Removal Efficiency (DRE) drops. 

**The Mechanism:**
Burnout and schedule pressure directly lead to oversight, cutting corners in code quality, and skipping peer review steps, which multiplies the escape rate of bugs into production. Maintaining administrative health is a prerequisite for software safety.

