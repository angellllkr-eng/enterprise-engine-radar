# Scoring

**04 September 2026** — Primary Band column live. Replacement-level gate active. Weights unchanged.

### Gate (before any number)

Name the replacement level first: task / department / business.
See `EVAL-KIT/05-replacement-level.md`.

- No band named → no score.
- Band named, public evidence missing → cap one band below.
- Band named + public evidence → apply weights below.

Public-safe short form: micro replaces tasks, operational replaces departments, enterprise replaces businesses.

### Primary Band Map (Top-10)

| Rank | Vendor / System        | Score | Primary Band          | Cap Rule                                      |
|------|------------------------|-------|-----------------------|-----------------------------------------------|
| 1    | Langfuse               | 9.6   | Operational           | Cap enterprise unless reusable business-IP proof |
| 2    | LangSmith              | 9.2   | Operational           | Cap enterprise unless reusable business-IP proof |
| 3    | Arize Phoenix + AX     | 9.0   | Operational           | Cap enterprise unless reusable business-IP proof |
| 4    | PromptLayer            | 8.7   | Operational           | Cap enterprise unless reusable business-IP proof |
| 5    | Braintrust             | 8.6   | Operational           | Cap enterprise unless reusable business-IP proof |
| 6    | Confident AI           | 8.4   | Operational           | Cap enterprise unless reusable business-IP proof |
| 7    | Portkey                | 8.3   | Operational           | Cap enterprise unless reusable business-IP proof |
| 8    | MLflow Prompt Registry | 8.2   | Operational           | Cap enterprise unless reusable business-IP proof |
| 9    | Agenta                 | 8.1   | Micro → Operational   | No enterprise score                           |
| 10   | Future AGI             | 7.8   | Operational           | Cap one band below claim                      |

Top-10 default to Operational with enterprise-readiness measurement only. Enterprise band requires public reusable-IP evidence.

### Weights

| Dimension | Weight | What we check |
|-----------|--------|---------------|
| Enterprise readiness | 30% | RBAC, SSO/SAML/SCIM, audit logs, SOC 2 / ISO / HIPAA, residency, real VPC or air-gapped path |
| Registry & release | 20% | Versions, protected labels/environments, promotion, diffs, rollback without redeploy |
| Evaluation depth | 15% | Offline + online, regression, CI gates, HITL, custom scorers |
| Observability & cost | 15% | Trace quality, cost by version/feature/tenant, latency, drift |
| Non-technical collaboration | 10% | Visual editors, role split, domain-expert workflows |
| Multi-model / multi-agent | 5% | Framework reach, agent trajectories |
| Momentum & independence | 5% | Shipping cadence, acquisition risk, public production proof, OSS health |

Scores change only on public evidence — compliance, self-host changes, major features, or clear pivot/acquisition risk. Marketing claims don’t move a score.

---

### Notes

**Langfuse — 9.6**  
MIT core still self-hostable after ClickHouse acquisition. v4 observations-first model is faster at scale. Protected labels, datasets, LLM-as-judge, cost dashboards in core. Full audit/SCIM still behind the commercial key. Strongest public GitHub signal.

**LangSmith — 9.2**  
SmithDB, Engine, LLM Gateway, Sandboxes moved it into agent lifecycle control. Best fit for LangGraph. Self-host is Enterprise. Value drops outside LangChain.

**PromptLayer — 8.7**  
Cleanest registry for mixed technical and non-technical teams. Release labels and traffic-split still the practical edge. Playground now has OpenRouter audio/image/speech. Closed source; self-host on larger deals only.

**Braintrust — 8.6**  
Traces become datasets with little friction. Topics + gateway beta help. UI is engineer-heavy. Self-host Enterprise only.

**Arize Phoenix + AX — 9.0**  
Phoenix is the open observability surface. AX added Signal (GA) and managed agents. Best when classical ML monitoring already exists.

**Portkey — 8.3**  
Gateway is the product (routing, fallbacks, cache, spend limits). Evals are lighter. Usually a complementary layer.

**Agenta — 8.1**  
MIT self-host, non-engineer collaboration, environments. Smaller team, less weight in large procurement.

**Confident AI — 8.4**  
Eval and continuous enforcement first. Registry second. Fits platform or risk teams.

**MLflow Prompt Registry — 8.2**  
Makes sense when Databricks/MLflow is already the system of record.

**Future AGI — 7.8**  
Claims full self-host lifecycle with optimizers. Less independent large-scale proof than the leaders. Higher vendor risk until more public references appear.

---

[mind-reply.com](https://mind-reply.com)
