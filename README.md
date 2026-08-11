# Enterprise Engine Radar

**MindReply · Living intelligence for production LLMOps**  
*August 2026 · Seller-ready · E2E evaluation kit*

> The market consolidated hard in 2025–2026.  
> Humanloop is gone. Helicone is in maintenance. Vellum pivoted.  
> Only a handful of platforms remain serious for regulated, large-scale production.

This repository is the **canonical, continuously updated scorecard** and the practical evaluation kit you can run against any shortlist.

---

## Top 10 Enterprise Engines — August 2026

| Rank | Platform | Best For | Enterprise Score | Self-host / VPC | Standout |
|------|----------|----------|------------------|-----------------|----------|
| **1** | **Langfuse** | Regulated + platform teams that want to own the stack | **9.6** | Yes (MIT core) | 32.8k★ · ClickHouse-backed · protected labels · full self-host |
| **2** | **LangSmith** | LangChain / LangGraph native orgs | **9.2** | Enterprise only | Deepest multi-agent tracing + Environments |
| **3** | **PromptLayer** | Cross-functional (PM + domain experts + eng) | **8.7** | Enterprise only | True registry-first + traffic-split labels |
| **4** | **Braintrust** | Eval-first teams with CI gates | **8.6** | Enterprise only | Production traces → living datasets |
| **5** | **Arize (Phoenix + AX)** | ML + LLM observability coexistence | **9.0** | Yes (Phoenix) | OTel-native · enterprise monitors |
| **6** | **Portkey** | Multi-provider gateway + cost control | **8.3** | Partial / Ent | Routing · fallbacks · attribution |
| **7** | **Agenta** | Open-source prompt + agent workbench | **8.1** | Yes (MIT) | Non-engineer collaboration + evaluators |
| **8** | **Confident AI** | Org-wide quality standards & gates | **8.4** | Enterprise | Red-team + continuous enforcement |
| **9** | **MLflow Prompt Registry** | Databricks / MLflow estates | **8.2** | Yes | Native lineage inside broader ML lifecycle |
| **10** | **Future AGI** | Full self-host lifecycle (higher vendor risk) | **7.8** | Yes | Integrated optimizers + CI gates |

**Primary ranking criteria (in order):**  
1. True enterprise readiness (RBAC, SSO/SAML, audit, SOC2/ISO, residency, VPC)  
2. Prompt/skill registry + versioning + release management  
3. Evaluation depth (auto + regression + CI gates + HITL)  
4. Production observability + cost attribution  
5. Non-technical collaboration  
6. Multi-model / multi-agent + context engineering  
7. Market momentum + independence + production evidence

---

## Quick Decision Matrix

| If you need… | Choose |
|--------------|--------|
| Maximum self-host + data residency | **Langfuse** |
| Deepest LangChain/LangGraph native | **LangSmith** |
| Non-technical domain experts own prompts | **PromptLayer** |
| Strongest eval → production loop | **Braintrust** |
| Unified ML + LLM observability | **Arize AX** |
| Multi-provider gateway + cost | **Portkey** |
| Open-source prompt-centric workbench | **Agenta** |
| Org-wide quality gates | **Confident AI** |
| Existing Databricks estate | **MLflow** |

---

## Stack Pattern Most Large Enterprises Actually Run (2026)

**Primary engine** → Langfuse (self-host preferred) *or* LangSmith (if LangChain-heavy) *or* PromptLayer (cross-functional).  
**Complementary** → Braintrust / Confident AI (evals + gates) + Portkey (gateway) + Arize AX (when classical ML coexists).

---

## What’s Inside This Repo

```
enterprise-engine-radar/
├── README.md                          ← you are here
├── SCORECARD.md                       ← full criteria + scoring rationale
├── EVAL-KIT/
│   ├── 01-enterprise-checklist.md     ← RBAC / SSO / audit / residency tests
│   ├── 02-self-host-smoke.md          ← time-to-first-trace protocol
│   ├── 03-prompt-registry-tests.md    ← versioning + labels + promotion
│   └── 04-eval-and-observability.md   ← regression + cost attribution
├── SELLER/
│   ├── pitch.md                       ← ready-to-send positioning
│   └── discovery-questions.md         ← buyer qualification questions
└── CHANGELOG.md
```

---

## How to Use This as a Seller

1. Share the live scorecard (this README) during discovery.  
2. Run the EVAL-KIT against the buyer’s shortlist in a throwaway environment.  
3. Deliver a private scorecard + gap analysis as the paid or high-trust next step.  
4. Position MindReply as the independent intelligence layer that keeps the ranking current.

---

## License & Attribution

MindReply intelligence.  
Free to use for evaluation and internal decision-making.  
Commercial redistribution or white-label requires attribution and/or license.

---

**Maintained by** [Angel K / MindReply](https://mind-reply.com) · `@angellllkr-eng`  
Last major refresh: **11 August 2026**
