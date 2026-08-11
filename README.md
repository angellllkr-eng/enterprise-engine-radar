<div align="center">

# Enterprise Engine Radar

**MindReply · living intelligence**

*Polite & persuasive decision systems for production LLMOps*

[mind-reply.com](https://mind-reply.com) · August 2026

</div>

---

The market cleaned house.  
Humanloop shut down. Helicone went into maintenance. Vellum left the enterprise lane.  
What remains are the platforms that still ship for regulated, high-volume production.

This repository is the working scorecard and the evaluation kit you can run against any shortlist.  
Evidence over claims. Protocols that produce a clear next action.

**Start** → [Landing](docs/landing.md) · [Private client template](CLIENT/scorecard-template.md) · [Seller kit](SELLER/)

---

## Top 10 — 11 August 2026

| # | Platform | Best for | Score | Self-host / VPC | Latest signal |
|---|----------|----------|-------|-----------------|---------------|
| **1** | **Langfuse** | Own the data plane | **9.6** | Yes (MIT core) | v4.6.0 · observations-first · ClickHouse scale · 32.8k★ |
| **2** | **LangSmith** | LangChain / LangGraph stacks | **9.2** | Enterprise | SmithDB · Engine · Gateway · Sandboxes · Managed Deep Agents |
| **3** | **PromptLayer** | PMs + domain experts + eng | **8.7** | Enterprise | Registry · release labels · multimodal Playground |
| **4** | **Braintrust** | Eval-driven CI gates | **8.6** | Enterprise | Trace → dataset → scorer · Topics · gateway beta |
| **5** | **Arize Phoenix + AX** | ML + LLM together | **9.0** | Phoenix OSS / AX Ent | Signal GA · managed agents · OpenInference |
| **6** | **Portkey** | Multi-provider cost & routing | **8.3** | Partial | Gateway · semantic cache · spend limits |
| **7** | **Agenta** | Open prompt workspace | **8.1** | Yes (MIT) | Environments · online eval · non-engineer focus |
| **8** | **Confident AI** | Org-wide quality bar | **8.4** | Enterprise | Continuous gates · red-team surface |
| **9** | **MLflow Prompt Registry** | Databricks estates | **8.2** | Yes | Native lineage in the ML lifecycle |
| **10** | **Future AGI** | Full self-host lifecycle | **7.8** | Yes | Optimizers present · thinner independent proof |

**Criteria order**  
Enterprise readiness → registry & release → evaluation depth → observability & cost → non-technical collaboration → multi-model / multi-agent → momentum & independence.

---

## Decision matrix

| If this is true | Start here |
|-----------------|------------|
| Data must stay inside your network | **Langfuse** |
| Already on LangChain / LangGraph | **LangSmith** |
| Domain experts edit prompts | **PromptLayer** |
| Regression is the primary risk | **Braintrust** |
| Classical ML monitoring already exists | **Arize AX** |
| Provider sprawl and token spend | **Portkey** |
| Prefer an open-source workbench | **Agenta** |
| Central platform sets the quality bar | **Confident AI** |
| Live inside Databricks | **MLflow** |

**Common 2026 pattern**  
Langfuse *or* LangSmith as primary · Braintrust *or* Confident AI for gates · Portkey for routing · Arize when ML and LLM share one observability surface.

---

## What’s in the repo

| Path | Purpose |
|------|---------|
| [SCORECARD.md](SCORECARD.md) | Weighted criteria + evidence notes |
| [RELEASES.md](RELEASES.md) | Current material release signals |
| [EVAL-KIT/](EVAL-KIT/) | Four complete protocols you can run |
| [SELLER/](SELLER/) | Pitch + discovery questions |
| [CLIENT/scorecard-template.md](CLIENT/scorecard-template.md) | Private client deliverable |
| [docs/landing.md](docs/landing.md) | Short overview |
| [.github/workflows/platform-watcher.yml](.github/workflows/platform-watcher.yml) | Weekly signal check |

---

## How to use this as a seller

1. Share the live ranking in discovery.  
2. Run the EVAL-KIT against the buyer’s top two or three candidates.  
3. Complete the private client scorecard and deliver the gap analysis.  
4. Let the weekly watcher surface material changes so the ranking stays current.

---

<div align="center">

**MindReply**  
*One calm operating layer*

[mind-reply.com](https://mind-reply.com) · Angel K · `@angellllkr-eng`

*Last full refresh · 11 August 2026*

</div>
