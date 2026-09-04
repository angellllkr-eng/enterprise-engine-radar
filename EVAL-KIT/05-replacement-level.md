# EVAL-KIT / 05 — Replacement Level Gate
**Hard rule for every scored system**

## Public-safe language only
micro replaces tasks · operational replaces departments · enterprise replaces businesses

## Gate Logic (executable)

```text
IF primary_band is missing or null:
    RETURN score = null
    REJECT entry from public SCORECARD

IF primary_band == "Enterprise":
    REQUIRE public reusable-IP evidence
    (product architecture + pricing model + onboarding flows + go-to-market plan as reusable assets)
    ELSE:
        FORCE primary_band = "Operational"
        APPLY cap rule: one band below any marketing claim

IF primary_band == "Operational":
    ALLOW enterprise-readiness sub-score
    FORBID full "replace business unit" claim without IP proof

IF primary_band == "Micro":
    ALLOW task / 1-2 person replacement only
    FORBID department or business-unit claims
```

## Qualifier (must answer first)

1. What is being replaced: a task, a department, or a business unit?
2. What does the buyer pay for: immediate revenue / hours saved, recurring labor cut + consistency, or exclusivity / scale / licensing?
3. Is there public evidence the stack can support that level, or only marketing language?

If the buyer cannot name the level, do not score. Discovery is incomplete.

## Band Definitions (compressed)

| Band              | Replaces              | Buyer pays for                          |
|-------------------|-----------------------|-----------------------------------------|
| Micro-product     | Tasks / 1-2 people    | Immediate revenue or hours saved        |
| Operational       | Departments           | Recurring labor cut + consistency       |
| Enterprise engine | Business units        | Scarcity, scalability, licensing IP     |

## Band fit checks (public evidence only)

| Level | Must show | Fail if |
|-------|-----------|---------|
| Task | Turnkey output path (funnel, sequence, module factory) with hours or revenue proof | Feature list with no shipped output |
| Department | Repeatable workflow with roles, escalation or SLA, consistent voice/output | Chatbot demo with no ops contract |
| Business | Reusable IP: architecture + pricing + onboarding + GTM, or document-to-decision system | One-off build sold as a platform |

## Enforcement
- SCORECARD.md must contain a Primary Band column.
- No score is published without a named primary band.
- Cap rules are applied automatically.

Stamped: 2026-09-04
