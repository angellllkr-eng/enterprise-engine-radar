# Scoring & Evidence — August 2026

Weights are fixed. Scores move only on public evidence (releases, compliance, acquisition risk, production signals).

| Dimension | Weight |
|-----------|--------|
| Enterprise readiness (RBAC, SSO/SAML, audit, SOC2/ISO, residency, VPC) | 30% |
| Registry + versioning + release management | 20% |
| Evaluation depth (offline/online, regression, CI gates, HITL) | 15% |
| Production observability + cost attribution | 15% |
| Non-technical collaboration | 10% |
| Multi-model / multi-agent support | 5% |
| Momentum & independence | 5% |

---

## Platform evidence (current)

### 1. Langfuse — 9.6
- **v4** (observations-first model) is GA; tables/dashboards up to 165× faster at scale.
- **v4.6.0** shipped 6 Aug 2026. Recent: Pulse (outlier detection), consistent evaluator sampling, boolean score alerts, Graph View modes, MCP surface (observations, metrics, scores, datasets, annotation queues).
- Gateway (virtual keys + access controls + direct cost tracking) is on the public roadmap.
- MIT core remains self-hostable post-ClickHouse acquisition. EE still gates advanced admin (SCIM, full audit policies).
- Public signal: 32.8k stars, daily-ish releases, official Helm.

### 2. LangSmith — 9.2
- **Fleet**: enterprise agent workspace (identity, sharing, permissions, inbox for HITL).
- **Engine**: clusters production failures, proposes fixes + evaluators, can open PRs.
- **SmithDB**: purpose-built store; reported ~15× faster core workloads (P50 trace tree ~92 ms).
- **LLM Gateway** (public beta): spend caps, rate limits, fallbacks, PII redaction (Enterprise).
- Self-host remains Enterprise-only. Pricing moved toward LCU/LSU meters; seat pricing still material.

### 3. PromptLayer — 8.7
- Registry-first product: visual editor, release labels, dynamic traffic-split labels, diffs.
- Aug 2026: AI-generated trace summaries, OpenRouter provider, request-volume analytics, MCP with 61 tools, prompt/workflow version tracking inside traces.
- Strongest non-engineer collaboration surface. Self-host only on Enterprise deals.

### 4. Braintrust — 8.6
- **Topics** now GA: continuous classification of production traces (task / issue / sentiment) into SQL-queryable signals.
- Behavior Specs (trajectory-level behavior contracts), pairwise scoring, experiment summary tables, group-scope online scoring.
- Enterprise: SSO (SAML/OIDC), audit logging, custom retention, BYOC / self-host options.

### 5. Arize Phoenix + AX — 9.0
- Phoenix **v19.21** (10 Aug): performance work, new instrumentors (AG2, Together, Cohere, Ollama).
- PXI agent skills (debug-trace, playground orchestration, evaluator authoring).
- AX carries the enterprise governance and continuous monitoring layer.

### 6–10
Portkey (gateway strength), Agenta (open MIT workbench), Confident AI (org-wide gates), MLflow (Databricks-native), Future AGI (self-host lifecycle claims, thinner independent production proof).

---

Scores are deliberately conservative. Marketing claims alone never raise a number.
