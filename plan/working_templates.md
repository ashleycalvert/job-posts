# Working Templates

Use the smallest artifact that improves a real decision, handoff, or operating outcome. Delete sections that are irrelevant. Keep each artifact with an owner and update trigger.

## 1. One-page outcome brief

```markdown
# [Initiative] outcome brief

Owner:
Sponsor / decision owner:
Date / status:

## Outcome
[Who] needs [capability/change] so that [business, user, or control outcome].

## Why now
[Current pain, risk, opportunity, deadline, or cost of delay.]

## Success measures
- Baseline:
- Target:
- Measurement owner/source:

## Scope and non-goals
- In:
- Out:

## Constraints and controls
[Deadline, platform, data classification, regulatory, budget, compatibility.]

## Key assumptions / unknowns
- [Assumption] — validate by [date/owner/method]

## Stakeholders and users
[Consumer, operator, source owner, product/business, architecture, security, governance.]

## Decision needed now
[Decision, owner, deadline.]
```

## 2. Architecture recommendation / ADR

```markdown
# Decision: [short title]

Status: Proposed | Accepted | Superseded
Owner / decision owner / date:

## Context and outcome
[What forces make a decision necessary?]

## Decision criteria
[Value, time, data trust, scale, reliability, security, compliance, cost,
operability, team capability, reversibility.]

## Options
1. [Option]: benefits, drawbacks, evidence, material risks.
2. [Option]: benefits, drawbacks, evidence, material risks.
3. [Simpler/staged option]: benefits, drawbacks, evidence, material risks.

## Recommendation
[Choice and decisive reasons.]

## Consequences
- Improves:
- Costs / constrains:
- Residual risks and owners:
- Migration / rollback / decommissioning:

## Production fitness
[Contracts/DQ, SLO/recovery, security/privacy, observability, scale/cost,
deployment, governance, support ownership.]

## Revisit when
[New scale, failure evidence, vendor/platform change, cost threshold, date.]
```

## 3. Option comparison

| Criterion | Evidence/importance | Option A | Option B | Staged option |
|---|---|---|---|---|
| Outcome fit |  |  |  |  |
| Delivery/time |  |  |  |  |
| Data trust/governance |  |  |  |  |
| Reliability/recovery |  |  |  |  |
| Security/privacy |  |  |  |  |
| Performance/scale |  |  |  |  |
| Cost |  |  |  |  |
| Operability/team capability |  |  |  |  |
| Reversibility |  |  |  |  |

End with a written judgment. A table assists reasoning; it does not make the decision.

## 4. RAID and decision log

### Risks, assumptions, issues, dependencies

| Type | Description and impact | Likelihood / severity | Owner | Response or validation | Due / trigger | State |
|---|---|---|---|---|---|---|
| Risk |  |  |  |  |  |  |

### Decisions

| Date | Decision | Owner | Evidence/trade-off | Affected parties | Revisit trigger | Link |
|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |

Escalate a risk when the response exceeds the owner’s authority, the decision date threatens the outcome, or exposure crosses the agreed tolerance. Escalate with recommendation and requested action.

## 5. Milestone plan

| Proof point / outcome | Owner | Dependencies | Acceptance evidence | Quality/controls | Target | State |
|---|---|---|---|---|---|---|
| Thin end-to-end slice |  |  | Working demonstration and measure | Contract, access, telemetry |  |  |

Prefer milestones that prove integrated behavior over milestones such as “development complete.” Include an owner for outcome and for service operation.

## 6. Weekly status update

```markdown
Status: Green | Yellow | Red — [one-sentence reason]

Outcome: [target and current evidence]
Changed: [material result or new information since last update]
Next proof point: [observable result and date]
Top risk/decision: [impact, owner, response/decision date]
Ask: [specific action, person, and needed-by date; or “none”]
```

Example:

> **Yellow — source corrections may miss the 07:00 freshness SLO.** The thin path processed representative volume within target, and reconciliation passed. Replay behavior for late corrections remains unproven. Data Source owns a representative sample by Tuesday; we will run the recovery test Wednesday. If it fails, I recommend staging correction support after initial launch. Decision needed from the sponsor Thursday.

## 7. Design-review agenda

Send the recommendation before the meeting. Use meeting time for unresolved trade-offs.

1. Decision and outcome (2 minutes)
2. Material constraints and assumptions (3 minutes)
3. Recommendation and rejected options (5 minutes)
4. Highest-risk failure, control, cost, or migration questions (15 minutes)
5. Decision, dissent, actions, owners, dates (5 minutes)

Review prompts:

- Are outcome and non-goals clear?
- Which assumption could invalidate the design?
- Are contracts, ownership, and failure boundaries explicit?
- How are correctness, replay/idempotency, and schema evolution handled?
- What are SLOs, capacity, recovery, and operational signals?
- Are access, privacy, retention, lineage, and audit evidence covered?
- What drives cost and how will it be bounded?
- How is rollout, rollback, migration, and decommissioning handled?
- Which specialist must review a high-consequence area?
- What would make us revisit the decision?

## 8. Production-readiness checklist

Use “not applicable + reason” rather than silently skipping an area.

- Business/user acceptance measure has an owner.
- Data contracts, DQ rules, reconciliation, lineage, and correction process are defined.
- Load/capacity evidence covers representative scale and skew.
- SLI/SLO, dashboards, actionable alerts, and escalation are in place.
- Retry, timeout, idempotency, replay/backfill, and partial-failure behavior are tested.
- RPO/RTO and recovery/restore are defined and tested where required.
- Authentication, authorization, secrets, encryption, PII, retention, and audit controls are reviewed.
- CI/CD, automated tests, versioned artifacts, promotion, rollback, and change ownership work.
- Cost drivers, budgets/alerts, and capacity owner are known.
- Runbook, dependency map, on-call/support owner, and known limitations are current.
- Rollout, user communication, adoption measurement, and rollback decision owner are set.
- Residual risks are explicitly accepted by the right owner.

## 9. Incident update and review

### Live update

```markdown
Impact: [users/data/services, start time, severity]
Known facts: [observed evidence only]
Mitigation/current state: [what changed and result]
Unknowns: [active hypotheses clearly labeled]
Owners: Incident lead [x], technical lead [y], communications [z]
Next update: [time]
```

### Blameless review

```markdown
## Impact and detection
## Timeline of events and decisions
## Expected versus actual system behavior
## Contributing technical and organizational conditions
## What reduced or increased impact
## Root causes supported by evidence
## Actions
| Systemic action | Outcome/measure | Owner | Due |
## Reusable learning and follow-up verification
```

Avoid stopping at “engineer error.” Ask which interface, test, guardrail, ownership, or context made the error possible and hard to detect.

## 10. Delegation brief

```markdown
Outcome and why it matters:
Owner and decision authority:
Constraints / non-negotiables:
Interfaces and people to involve:
Acceptance and production-quality evidence:
Risks that require escalation:
Check-in points (not constant supervision):
What I will provide:
```

At review, ask the owner to explain options, assumptions, and failure modes. Do not substitute your implementation unless the risk demands intervention.

## 11. Feedback format

```markdown
Observation: In [specific situation], I observed [behavior/evidence].
Impact: This caused or risked [outcome].
Expected bar: At this scope, I expect [specific behavior].
Next experiment: On [next situation], try [action].
Support: I can [review/pair/provide context].
Follow-up: We will check [evidence] on [date].
```

Ask for similarly specific feedback: “In today’s design review, where did my reasoning or facilitation fall below the Lead bar?”

## 12. Evidence narrative for a review

```markdown
Situation/stakes: [Why this mattered; scale, business/control consequence.]
Ambiguity: [What was unknown or conflicted.]
My role: [Authority and exact contribution.]
Reasoning: [Options, trade-offs, decision, and experts involved.]
Execution: [How I aligned, delivered, controlled risk, and stayed hands-on.]
Leverage: [Who became more capable or what mechanism was adopted.]
Outcome: [Measured result and stakeholder evidence.]
Learning: [What changed in my approach and remaining gap.]
```

Use “I” for your decisions/actions and “we” for team delivery. Strong presentation is precise attribution plus evidence, not inflated ownership.
