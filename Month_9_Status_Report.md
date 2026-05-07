# GCHA Month 9 Status Report
## Prepared by: London PMO | Date: 2026-05-07
## Reporting Period: Project Month 9 of 18
## OVERALL PROJECT STATUS: RED

## Section 1: The Numbers (EVM Dashboard)
| Metric | Value | Interpretation |
| :--- | :--- | :--- |
| Budget at Completion (BAC) | $12,000,000 | Approved budget |
| Planned Value (PV) | $6,000,000 | Work planned by Month 9 |
| Earned Value (EV) | $4,500,000 | Work actually completed |
| Actual Cost (AC) | $5,500,000 | Money spent to date |
| Schedule Variance (SV) | -$1,500,000 | Behind schedule |
| Cost Variance (CV) | -$1,000,000 | Over budget |
| SPI | 0.75 | 75% of planned speed achieved |
| CPI | 0.818 | 82 cents of value per $1 spent |
| Critical Ratio | 0.614 | CRISIS (below 0.9 threshold) |
| EAC (Steady Trend) | $14,670,000 | Projected final cost |
| VAC | -$2,670,000 | Projected budget overrun |
| ETC | $9,170,000 | Cash still required to finish |
| TCPI | 1.15 | Efficiency required to recover |

## Section 2: RAG Status Assignment
[cite_start]**Overall Status: RED** [cite: 86]
**Justification:**
The project's Critical Ratio of 0.614 is far below the 0.9 intervention threshold. [cite_start]Both SPI (0.75) and CPI (0.818) are below 1.0 simultaneously, indicating a dual crisis: the team is behind schedule AND over budget. [cite: 88, 89]

**Site-Level RAG:**
| Site | SPI | CPI | RAG Status |
| :--- | :--- | :--- | :--- |
| Berlin | 0.50 | 0.833 | RED (severely behind schedule) |
| Bangalore | 1.25 | 0.714 | AMBER (fast but wasteful) |
| Cairo | 1.00 | 1.00 | GREEN (baseline performance) |

## Section 3: Root Cause Analysis
**Primary Cause Berlin AI Module (Requirement Gap):**
The Berlin AI team's original requirements significantly underestimated the complexity of training the diagnostic model on real patient data from multiple hospital systems with inconsistent data formats. The team discovered in Month 5 that the Cairo data required an additional pre-processing layer not included in the original WBS, adding 40+ hours of unplanned work per training cycle. [cite_start]This requirement gap, combined with the experimental nature of the AI architecture, has produced a CPI of 0.50 on the Berlin site. [cite: 102]

## Section 4: The Pivot Corrective Administrative Actions
**Action 1: Fast-Track Bangalore UI in parallel with Berlin AI**
* [cite_start]**Description:** Bring forward Bangalore's offline-sync feature development to run in parallel with Berlin's AI corrections. [cite: 106]
* [cite_start]**Budget Impact:** +$80,000 (overtime authorization for Bangalore senior devs). [cite: 108]
* [cite_start]**Schedule Impact:** Recovers approximately 3 weeks of end-date slippage. [cite: 108]

**Action 2: Descope the Real-Time Chatbot feature**
* **Description:** Remove the AI-powered chatbot from Phase 1 scope. [cite_start]This feature is classified as "Should Have" in the MOSCOW analysis. [cite: 109, 110]
* [cite_start]**Budget Impact:** -$350,000 saved from remaining scope. [cite: 112]
* [cite_start]**Schedule Impact:** Frees 2 Berlin AI specialists for the core diagnostic module. [cite: 113]

**Budget After Actions:**
* [cite_start]**Revised EAC:** $14,400,000 [cite: 118]
* [cite_start]**Remaining Gap to BAC:** -$2,400,000 (requires Board budget revision). [cite: 119]
