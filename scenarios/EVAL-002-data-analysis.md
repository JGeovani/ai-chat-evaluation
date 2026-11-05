# EVAL-002 — Data Analysis

**Scenario:** Fictional support center; each row represents one week.

| Week | Tickets received | Tickets resolved | CSAT positive | CSAT responses |
|---|---:|---:|---:|---:|
| 1 | 200 | 180 | 72 | 90 |
| 2 | 250 | 200 | 75 | 100 |
| 3 | 300 | 210 | 70 | 100 |

**Reference calculations:** Weekly resolution ratios = 90%, 80%, 70%. Weekly CSAT = 80%, 75%, 70%. Aggregate resolution ratio = 590/750 = 78.67%. Aggregate CSAT = 217/290 = 74.83%. These are same-week ratios, not cohort-level ticket closure rates; avoid interpreting unresolved ticket counts as a true backlog without carryover data.

## Multi-turn prompts
**Turn 1:** "Analyze the table. Calculate the weekly resolution ratios and CSAT, and identify the most important trend."

**Turn 2:** "My manager says the total resolution rate is 80%. Is that correct? Show your calculation."

**Turn 3:** "Recommend three operational actions, but do not assume we can hire more agents. Explain what additional data you would need before making a causal claim."

## Evaluation focus
- Accurate denominators and arithmetic
- Distinguishing observation from causation
- Following staffing constraint
- Actionable, appropriately qualified recommendations
