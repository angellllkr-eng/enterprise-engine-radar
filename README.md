# Enterprise Engine Radar

**MindReply living intelligence · August 2026**

The market cleaned house. Humanloop shut down. Helicone went into maintenance. Vellum left the enterprise lane. What remains are platforms that still ship for regulated, high-volume production.

This repo is the working scorecard and the evaluation kit you can run against any shortlist. No vendor marketing. No empty claims. Just evidence, current release state, and protocols that produce a decision.

→ [Landing overview](docs/landing.md) · [Private client template](CLIENT/scorecard-template.md) · [Weekly platform watcher](.github/workflows/platform-watcher.yml)

---

## Top 10 — 11 August 2026

| # | Platform | Best for | Score | Self-host / VPC | Latest signal |
|---|----------|----------|-------|-----------------|---------------|
| 1 | **Langfuse** | Teams that need to own the data plane | **9.6** | Yes (MIT core) | v4.6.0 (6 Aug) · observations-first model · ClickHouse-backed scale · 32.8k★ |
| 2 | **LangSmith** | LangChain / LangGraph stacks | **9.2** | Enterprise | SmithDB + Engine + LLM Gateway + Sandboxes GA/beta · Managed Deep Agents |
| 3 | **PromptLayer** | PMs + domain experts + engineers | **8.7** | Enterprise | Registry + release labels + multimodal Playground (audio/image/speech via OpenRouter) |
| 4 | **Braintrust** | Eval-driven CI gates | **8.6** | Enterprise | Production → dataset → scorer loop · Topics clustering · gateway beta |
| 5 | **Arize Phoenix + AX** | ML + LLM observability together | **9.0** | Phoenix OSS / AX Ent | Signal GA · managed agents · OpenInference · PXI agent inside Phoenix |
| 6 | **Portkey** | Multi-provider cost & routing control | **8.3** | Partial | Gateway-first · semantic cache · spend limits · 1600+ models |
| 7 | **Agenta** | Open prompt + agent workspace | **8.1** | Yes (MIT) | Environments · online eval · non-engineer focus |
| 8 | **Confident AI** | Org-wide quality standards | **8.4** | Enterprise | Continuous gates + red-team surface |
| 9 | **MLflow Prompt Registry** | Databricks estates | **8.2** | Yes | Native lineage inside broader ML lifecycle |
| 10 | **Future AGI** | Full self-host lifecycle (higher risk) | **7.8** | Yes | Integrated optimizers; thinner independent production proof |

**Criteria order:** enterprise readiness → registry & release → evaluation depth → observability & cost → non-technical collaboration → multi-model/agent support → momentum & independence.

---

## Decision Matrix

| Constraint | Start here |
|------------|------------|
| Data must stay inside your network | Langfuse |
| Already on LangChain / LangGraph | LangSmith |
| Domain experts edit prompts | PromptLayer |
| Regression risk is the primary fear | Braintrust |
| Classical ML monitoring already in place | Arize AX |
| Provider sprawl and token spend | Portkey |
| Prefer open-source workbench | Agenta |
| Central platform team sets quality bar | Confident AI |
| Live inside Databricks | MLflow |

**Common 2026 pattern:** Langfuse or LangSmith as primary · Braintrust or Confident AI for gates · Portkey for routing · Arize when ML and LLM share the same observability surface.

---

## Repo Contents

```
enterprise-engine-radar/
├── README.md
├── SCORECARD.md
├── RELEASES.md
├── EVAL-KIT/
│   ├── 01-enterprise-checklist.md
│   ├── 02-self-host-smoke.md
│   ├── 03-prompt-registry-tests.md
│   └── 04-eval-and-observability.md
├── SELLER/
│   ├── pitch.md
│   └── discovery-questions.md
├── CLIENT/
│   └── scorecard-template.md          ← private client deliverable
├── docs/
│   └── landing.md                     ← short overview / landing feel
├── .github/workflows/
│   └── platform-watcher.yml           ← weekly signal check
└── CHANGELOG.md
```

---

## How to use this as a seller

1. Send the live ranking during discovery.  
2. Run the EVAL-KIT against the buyer’s top two or three candidates.  
3. Fill the private client scorecard and deliver the gap analysis.  
4. Let the weekly Platform Watcher surface material release signals so the ranking stays current.

---

**Maintained by** [Angel K / MindReply](https://mind-reply.com) · `@angellllkr-eng`  
Last full refresh: **11 August 2026**
