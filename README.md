# Enterprise Engine Radar

**MindReply · Production LLMOps intelligence**  
*Live ranking · Evaluation kit · Seller asset · 11 Aug 2026*

Half the “best tools” lists still name products that shut down or pivoted.  
This repo tracks only what is still shipping and fit for regulated production.

---

## Top 10 — August 2026

| # | Platform | Best for | Score | Self-host | Latest signal |
|---|----------|----------|-------|-----------|---------------|
| 1 | **Langfuse** | Own the stack, regulated data | **9.6** | Yes (MIT) | **v4.6** (6 Aug) · 165× faster tables · Pulse outliers · MCP tools · Gateway on roadmap |
| 2 | **LangSmith** | LangChain / LangGraph teams | **9.2** | Ent only | **Fleet** + **Engine** + **SmithDB** (15× faster) + **LLM Gateway** (spend caps, PII redact) |
| 3 | **PromptLayer** | PMs + domain experts edit prompts | **8.7** | Ent only | AI trace summaries · OpenRouter · dynamic release labels · MCP (61 tools) |
| 4 | **Braintrust** | Eval → production loop | **8.6** | Ent / BYOC | **Topics GA** · Behavior Specs · pairwise scoring · experiment summary tables |
| 5 | **Arize Phoenix + AX** | ML + LLM in one place | **9.0** | Phoenix yes | **v19.21** (10 Aug) · PXI agent skills · AG2 / Cohere / Ollama instrumentors |
| 6 | **Portkey** | Multi-model gateway + cost | **8.3** | Partial | Gateway + prompt versioning + spend controls |
| 7 | **Agenta** | Open-source prompt + agent workspace | **8.1** | Yes (MIT) | Environments · online eval · non-engineer focus |
| 8 | **Confident AI** | Org-wide quality gates | **8.4** | Ent | Red-team + continuous pre-ship / live enforcement |
| 9 | **MLflow Prompt Registry** | Databricks estates | **8.2** | Yes | Native lineage inside existing ML platform |
| 10 | **Future AGI** | Full self-host lifecycle (higher risk) | **7.8** | Yes | Optimizers + CI gates — thinner independent proof |

**Criteria order:** enterprise readiness → registry/release → eval depth → observability + cost → non-tech collaboration → multi-model/agent → momentum & independence.

---

## Decision shortcuts

| Need | Pick |
|------|------|
| Self-host + residency | Langfuse |
| Already on LangChain/LangGraph | LangSmith |
| Non-engineers own prompts | PromptLayer |
| Strict eval + CI gates | Braintrust |
| Classical ML + LLM together | Arize AX |
| Gateway + multi-provider cost | Portkey |
| Open-source workbench | Agenta |

**Typical large-enterprise pattern 2026**  
Primary: Langfuse (self-host) *or* LangSmith *or* PromptLayer.  
Add: Braintrust/Confident (gates) + Portkey (routing) + Arize when ML coexists.

---

## What’s in the repo

```
README.md                 ← ranking + latest signals
SCORECARD.md              ← weighted criteria + evidence
EVAL-KIT/                 ← 4 practical test protocols
SELLER/                   ← pitch + discovery questions
CHANGELOG.md
```

---

## How to use as a seller

1. Send this README in discovery.  
2. Run EVAL-KIT on the buyer’s shortlist.  
3. Deliver a private gap analysis as the next paid or high-trust step.  
4. Keep the ranking current — that is the product.

---

**MindReply / Angel K** · [mind-reply.com](https://mind-reply.com) · `@angellllkr-eng`  
Last refresh: **11 August 2026**
