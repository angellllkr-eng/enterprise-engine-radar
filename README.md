<div align="center">

# Enterprise Engine Radar

**MindReply**

[mind-reply.com](https://mind-reply.com) · August 2026

</div>

---

Humanloop is gone. Helicone is in maintenance. Vellum left the enterprise lane.  
These are the platforms that still hold up for regulated, large-scale production.

Scorecard + evaluation kit. Run it against any shortlist.

**Start** → [docs/START-HERE.md](docs/START-HERE.md)

---

## Top 10 — 11 August 2026

| # | Platform | Best for | Score | Self-host / VPC | Latest signal |
|---|----------|----------|-------|-----------------|---------------|
| **1** | **Langfuse** | Own the data plane | **9.6** | Yes (MIT core) | v4.6.0 · observations-first · ClickHouse · 32.8k★ |
| **2** | **LangSmith** | LangChain / LangGraph | **9.2** | Enterprise | SmithDB · Engine · Gateway · Sandboxes · Managed Deep Agents |
| **3** | **PromptLayer** | PMs + domain experts + eng | **8.7** | Enterprise | Registry · release labels · multimodal Playground |
| **4** | **Braintrust** | Eval + CI gates | **8.6** | Enterprise | Trace → dataset → scorer · Topics · gateway beta |
| **5** | **Arize Phoenix + AX** | ML + LLM together | **9.0** | Phoenix OSS / AX Ent | Signal GA · managed agents · OpenInference |
| **6** | **Portkey** | Multi-provider routing + cost | **8.3** | Partial | Gateway · semantic cache · spend limits |
| **7** | **Agenta** | Open prompt workspace | **8.1** | Yes (MIT) | Environments · online eval |
| **8** | **Confident AI** | Org-wide quality bar | **8.4** | Enterprise | Continuous gates · red-team |
| **9** | **MLflow Prompt Registry** | Databricks estates | **8.2** | Yes | Native lineage in ML lifecycle |
| **10** | **Future AGI** | Full self-host lifecycle | **7.8** | Yes | Optimizers · thinner public proof |

**How we rank**  
1. Enterprise readiness  
2. Registry + release management  
3. Evaluation depth  
4. Observability + cost  
5. Non-technical collaboration  
6. Multi-model / multi-agent  
7. Momentum + independence

---

## Decision matrix

| If this is true | Start here |
|-----------------|------------|
| Data stays inside your network | **Langfuse** |
| Already on LangChain / LangGraph | **LangSmith** |
| Domain experts edit prompts | **PromptLayer** |
| Regression is the main risk | **Braintrust** |
| Classical ML monitoring already there | **Arize AX** |
| Provider sprawl and token spend | **Portkey** |
| Want open-source workbench | **Agenta** |
| Central team sets the quality bar | **Confident AI** |
| Live inside Databricks | **MLflow** |

**Usual stack in 2026**  
Langfuse or LangSmith as primary · Braintrust or Confident AI for gates · Portkey for routing · Arize when ML and LLM share one observability surface.

---

## What’s here

| Path | What it is |
|------|------------|
| [SCORECARD.md](SCORECARD.md) | Weights + why each score |
| [RELEASES.md](RELEASES.md) | Recent material releases |
| [EVAL-KIT/](EVAL-KIT/) | Four checklists to run |
| [SELLER/](SELLER/) | Pitch + discovery questions |
| [CLIENT/scorecard-template.md](CLIENT/scorecard-template.md) | Private client deliverable |
| [docs/START-HERE.md](docs/START-HERE.md) | Three paths |
| [.github/workflows/platform-watcher.yml](.github/workflows/platform-watcher.yml) | Monday signal check |

---

## Seller flow

1. Send the ranking.  
2. Run the EVAL-KIT on their top 2–3.  
3. Fill the client scorecard and hand over the gaps.  
4. Watcher posts weekly; update RELEASES.md when something real ships.

---

<div align="center">

**MindReply**  
[mind-reply.com](https://mind-reply.com) · `@angellllkr-eng`

</div>
