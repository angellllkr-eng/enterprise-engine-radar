# Scoring Rationale

**Version:** 11 August 2026  
**Owner:** MindReply

## Weights

| Dimension | Weight | What is measured |
|-----------|--------|------------------|
| Enterprise readiness | 30% | RBAC, SSO/SAML/SCIM, audit logs, SOC 2 / ISO / HIPAA evidence, residency, real VPC or air-gapped path |
| Registry & release | 20% | Version model, protected labels/environments, promotion, diffs, rollback without code redeploy |
| Evaluation depth | 15% | Offline + online, regression, CI gates, HITL, research-backed or custom scorers |
| Observability & cost | 15% | Trace fidelity, cost by version/feature/tenant, latency, drift |
| Non-technical collaboration | 10% | Visual editors, role separation, domain-expert workflows |
| Multi-model / multi-agent | 5% | Framework reach, agent trajectories, context engineering |
| Momentum & independence | 5% | Shipping cadence, acquisition risk, public production evidence, OSS health |

Scores move only on public evidence: new compliance statements, self-host improvements, major feature launches, or clear acquisition/pivot risk. Marketing claims alone never raise a score.

## Platform notes

**Langfuse — 9.6**  
MIT core remains self-hostable after the January 2026 ClickHouse acquisition. v4 observations-first model materially improved query performance at scale. Protected labels, datasets, LLM-as-judge, and cost dashboards ship in core. Advanced admin (full audit, SCIM) still sits behind the commercial key. Strongest public GitHub signal in the category.

**LangSmith — 9.2**  
SmithDB, Engine, LLM Gateway (beta), and Sandboxes moved the platform from pure tracing into agent lifecycle control. Deepest native fit for LangGraph. Self-host remains Enterprise. Pricing and value drop outside the LangChain ecosystem.

**PromptLayer — 8.7**  
Still the cleanest registry-first product for mixed technical and non-technical teams. Release labels and traffic-split remain the practical differentiators. Recent Playground work added OpenRouter audio, image, and speech models. Closed source; self-host only on larger contracts.

**Braintrust — 8.6**  
Production traces become datasets with minimal friction. Topics clustering and the gateway beta strengthen the loop. UI remains engineer-centric. Enterprise self-host only.

**Arize Phoenix + AX — 9.0**  
Phoenix stays the open observability surface (OpenInference). AX added Signal (GA) and managed agents for continuous issue detection and proposed fixes. Best when classical ML monitoring already exists. Full governance lives in AX.

**Portkey — 8.3**  
Gateway strengths (routing, fallbacks, semantic cache, spend limits) are the real product. Evaluation depth is lighter. Useful as a complementary layer rather than the sole engine.

**Agenta — 8.1**  
MIT self-host with explicit non-engineer collaboration and environments. Smaller team and less enterprise brand weight in large procurement cycles.

**Confident AI — 8.4**  
Evaluation and continuous enforcement are the core. Prompt registry polish is secondary. Fits central platform or risk teams.

**MLflow Prompt Registry — 8.2**  
Natural choice only when the broader Databricks/MLflow estate is already the system of record.

**Future AGI — 7.8**  
Claims a full self-host lifecycle including optimizers. Independent large-scale production evidence remains thinner than the leaders above. Higher vendor-risk score until more public references appear.
