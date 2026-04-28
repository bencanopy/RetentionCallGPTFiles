# Transcript Scoring Format v2

**Purpose:** Standard output template for scoring completed retention and expansion call transcripts.
**Use case:** Post-roleplay evaluation and real-call transcript scoring for customer retention, renewal, and ethical expansion conversations.
**Source rubric:** `RetentionExpansionCallRubric.md`

---

## Instructions for Evaluator

Use this format after a transcript or live roleplay has ended.

Guidelines:
- Score only what the rep actually said or did in the transcript.
- Do not assume intent, hidden actions, product facts, pricing, policy, or customer context that is not visible in the conversation.
- Score each rubric category from 1 to 5, then convert the raw score to weighted points.
- Always cite specific transcript evidence for category scores.
- If evidence is missing or the transcript is incomplete, say so and score based only on available evidence.
- Prioritize retention and expansion behaviors: upfront contract, business discovery, pain and consequence, value linkage, objection reframing, expansion qualification, decision process, and clear next steps.
- Do not reward generic pitching, premature discounting, unsupported ROI claims, pressure tactics, or expansion attempts that are not tied to discovered customer needs.
- Do not coach during the scorecard itself; provide coaching in the feedback and coaching priority sections.

---

## Scoring Scale

Each category receives a raw score from 1 to 5.

| Score | Meaning | Standard |
|---:|---|---|
| 5 | Excellent | Consistently demonstrated; clear, customer-specific, and commercially useful. |
| 4 | Strong | Mostly demonstrated with minor missed opportunities. |
| 3 | Adequate | Present but inconsistent, generic, or shallow. |
| 2 | Weak | Attempted but ineffective, unclear, or rep-centered. |
| 1 | Poor / Missing | Not demonstrated or actively harmful to the call objective. |

### Weighted Score Calculation

```text
Category Weighted Score = (Raw Score / 5) x Category Weight
Base Weighted Score = Sum of all category weighted scores
Final Score = Base Weighted Score + Positive Modifiers - Negative Modifiers
Maximum Final Score = 100
Minimum Final Score = 0
```

Round weighted category scores and final scores to one decimal place unless the score is a whole number.

---

## Rubric Categories and Weights

| Category | Weight |
|---|---:|
| Upfront Contract & Call Control | 15 |
| Discovery of Business Drivers & Current State | 15 |
| Pain Identification, Impact, and Consequence | 15 |
| Value Reinforcement & Customer-Specific ROI | 15 |
| Objection Handling & Reframing | 15 |
| Expansion Qualification & Value Creation | 15 |
| Commitment, Next Steps, and Closing Discipline | 10 |

---

## Outcome Bands

| Final Score | Rating | Interpretation |
|---:|---|---|
| 90-100 | Elite | Rep protects the relationship, creates value, handles objections effectively, and advances expansion naturally. |
| 80-89 | Strong | Rep performs well and creates a clear path forward, with some missed depth or precision. |
| 70-79 | Acceptable | Rep covers the basics but needs stronger discovery, value linkage, or commitment discipline. |
| 60-69 | At Risk | Rep is reactive, generic, or fails to create enough customer-specific value. |
| <60 | Unacceptable | Rep does not control the call, fails to address core objections, or damages retention or expansion likelihood. |

### Pass / Fail Standard

- **Pass:** Final score is 70 or higher and no automatic red flag materially undermines the call.
- **Fail:** Final score is below 70, or the rep commits a severe red flag such as misrepresentation, manipulative pressure, or ending without a next step after a clear save or expansion opportunity.

---

## Behavioral Modifiers

Apply modifiers after calculating the base weighted score.

### Positive Modifiers

Add up to **+5 points total**, without exceeding 100.

| Modifier | Adjustment |
|---|---:|
| Customer explicitly restates value in their own words | +2 |
| Customer agrees to a specific expansion evaluation | +2 |
| Customer moves from cancellation intent to renewal consideration | +3 |
| Rep uncovers a previously unknown business pain | +2 |
| Rep creates a multi-stakeholder next step | +2 |

### Negative Modifiers

Subtract all that apply.

| Modifier | Adjustment |
|---|---:|
| Rep offers discount before diagnosing value or pain | -5 |
| Rep argues with or talks over the customer | -5 |
| Rep makes unsupported ROI claims | -4 |
| Rep pushes expansion despite poor fit | -5 |
| Rep fails to ask any discovery questions | -8 |
| Rep ends without a next step | -6 |
| Rep misrepresents product capability, pricing, terms, or availability | -10 |
| Rep creates pressure, guilt, or manipulative urgency | -6 |

---

## Required Transcript Scoring Output

Use this exact structure when returning the score and feedback to the user.

````markdown
# Retention & Expansion Call Score

## 1. Executive Summary

- **Customer's stated concern:** [Briefly state what the customer said they were concerned about.]
- **Underlying business issue:** [State the deeper business issue if discovered. If not discovered, write "Not clearly discovered."]
- **Rep's strongest behavior:** [Name the strongest rubric-aligned behavior.]
- **Rep's biggest missed opportunity:** [Name the highest-impact gap.]
- **Likelihood of retention or expansion:** [High / Medium / Low, with one sentence of reasoning.]

## 2. Scorecard

| Category | Weight | Raw Score 1-5 | Weighted Score | Notes |
|---|---:|---:|---:|---|
| Upfront Contract & Call Control | 10 | [ ] | [ ] | [Brief evidence-based note.] |
| Discovery of Business Drivers & Current State | 15 | [ ] | [ ] | [Brief evidence-based note.] |
| Pain Identification, Impact, and Consequence | 15 | [ ] | [ ] | [Brief evidence-based note.] |
| Value Reinforcement & Customer-Specific ROI | 15 | [ ] | [ ] | [Brief evidence-based note.] |
| Objection Handling & Reframing | 15 | [ ] | [ ] | [Brief evidence-based note.] |
| Expansion Qualification & Value Creation | 10 | [ ] | [ ] | [Brief evidence-based note.] |
| Decision Process, Budget, Authority, and Mutual Qualification | 10 | [ ] | [ ] | [Brief evidence-based note.] |
| Commitment, Next Steps, and Closing Discipline | 10 | [ ] | [ ] | [Brief evidence-based note.] |

## 3. Final Score

```text
Base Weighted Score: [ ] / 100
Positive Modifiers: [List each modifier and points, or "None"]
Negative Modifiers: [List each modifier and points, or "None"]
Final Score: [ ] / 100
Outcome Band: [Elite / Strong / Acceptable / At Risk / Unacceptable]
Pass / Fail: [Pass / Fail]
Confidence in Score: [High / Medium / Low]
```

## 4. Evidence-Based Feedback

### Upfront Contract & Call Control
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger line the rep could have used.]"

### Discovery of Business Drivers & Current State
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger question the rep could have asked.]"

### Pain Identification, Impact, and Consequence
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger pain or consequence question.]"

### Value Reinforcement & Customer-Specific ROI
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger value or ROI framing.]"

### Objection Handling & Reframing
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger objection clarification or reframe.]"

### Expansion Qualification & Value Creation
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger expansion qualification question, or state that expansion was not appropriate.]"

### Decision Process, Budget, Authority, and Mutual Qualification
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger decision-process or qualification question.]"

### Commitment, Next Steps, and Closing Discipline
- **Transcript evidence:** [Quote or paraphrase the clearest evidence.]
- **What the rep did well:** [Specific behavior, or "Not demonstrated."]
- **What the rep missed:** [Specific gap, or "No major miss."]
- **Better alternative phrasing:** "[A stronger closing or next-step statement.]"

## 5. What the Rep Did Well

- [Specific strength tied to the rubric.]
- [Specific strength tied to the rubric.]
- [Specific strength tied to the rubric.]

## 6. What the Rep Missed

- [Specific miss tied to the rubric.]
- [Specific miss tied to the rubric.]
- [Specific miss tied to the rubric.]

## 7. Coaching Priorities

1. **Highest-impact behavior to improve:** [Priority with brief explanation.]
2. **Second-highest-impact behavior to improve:** [Priority with brief explanation.]
3. **Behavior to preserve:** [A strength the rep should keep using.]

## 8. Stronger Questions or Phrases

- "[Better upfront contract, discovery question, objection reframe, or closing line.]"
- "[Better upfront contract, discovery question, objection reframe, or closing line.]"
- "[Better upfront contract, discovery question, objection reframe, or closing line.]"

## 9. Expansion Readiness Assessment

- **Readiness:** [Not Ready / Early Signal / Qualified Opportunity / Expansion Recommended]
- **Reasoning:** [Explain based on discovered pain, value gap, stakeholder interest, business case, and next step.]

## 10. Coaching Recommendation

[One concise paragraph focused on the highest-value next improvement.]
````

---

## Expansion Readiness Definitions

| Readiness | Definition |
|---|---|
| Not Ready | Retention or trust problem must be solved before expansion. |
| Early Signal | Some pain or need exists, but not enough qualification yet. |
| Qualified Opportunity | Clear pain, value gap, stakeholder interest, and plausible business case. |
| Expansion Recommended | Strong fit, measurable business case, and agreed next step. |

---

## Short Manager Version

Use this shorter format only when the user explicitly asks for a quick score.

```markdown
## Quick Retention & Expansion Score

- **Final Score:** [ ] / 100
- **Outcome Band:** [Elite / Strong / Acceptable / At Risk / Unacceptable]
- **Pass / Fail:** [Pass / Fail]
- **Top Strength:** [Most important strength.]
- **Top Gap:** [Most important miss.]
- **Primary Customer Concern:** [Stated concern.]
- **Underlying Business Issue:** [Discovered issue, or "Not clearly discovered."]
- **Expansion Readiness:** [Not Ready / Early Signal / Qualified Opportunity / Expansion Recommended]
- **Next Skill to Practice:** [One rubric category.]

### Quick Coaching Note

[Two to four sentences with the highest-impact coaching recommendation.]
```

---

## Scoring Reminders

- Do not over-score a friendly rep with weak discovery.
- Do not under-score a direct rep if the conversation was respectful and commercially effective.
- Separate politeness from actual retention and expansion skill.
- Reward customer-specific value, quantified impact, and clear next steps.
- Penalize premature discounting, generic feature pitching, unsupported ROI, pressure tactics, and unclear commitments.
- Expansion should be treated as appropriate only when the rep earns it through discovery, value creation, and qualification.
- If the rep did not have a realistic opportunity to discuss expansion, score the expansion category based on whether they appropriately recognized fit and timing, not simply whether they pitched an upsell.

---

## Versioning

- **Version:** 2.0
- **Owner:** [Team Name]
- **Last Updated:** 2026-04-27
- **Notes:** Updated transcript scoring output to match the weighted Customer Retention & Expansion Call Scoring Rubric.
