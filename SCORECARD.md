# Full Scoring Rationale — Enterprise Engine Radar

**Version:** August 2026  
**Owner:** MindReply

## Scoring Dimensions (Weighted)

| Dimension | Weight | What we actually measure |
|-----------|--------|--------------------------|
| Enterprise readiness | 30% | RBAC granularity, SSO/SAML/SCIM, immutable audit logs, SOC 2 / ISO / HIPAA evidence, data residency options, true VPC / air-gapped path |
| Registry & release management | 20% | Version model, protected labels / environments, promotion workflows, diffs, rollback |
| Evaluation depth | 15% | Offline + online evals, regression suites, CI gates, human-in-the-loop queues, research-backed metrics |
| Production observability & cost | 15% | Trace fidelity, cost attribution per version / feature / tenant, latency, drift signals |
| Non-technical collaboration | 10% | Visual editors, role separation, domain-expert workflows without code |
| Multi-model / multi-agent | 5% | Framework agnosticism, agent trajectory support, context engineering primitives |
| Momentum & independence | 5% | Active shipping, acquisition risk, public production evidence, OSS health |

## Platform Notes (Key Evidence)

### 1. Langfuse — 9.6
- MIT core remains fully self-hostable after ClickHouse acquisition (Jan 2026).
- Protected prompt labels, datasets, LLM-as-judge, cost dashboards all present in core.
- Strongest public GitHub signal (32k+ stars, active k8s Helm, continuous releases).
- Risk: advanced admin (full audit/SCIM) still gated behind EE key.

### 2. LangSmith — 9.2
- Native LangGraph state visualization and Environments are unmatched for LangChain stacks.
- Enterprise SSO + regional hosting available.
- Risk: seat + usage pricing; value collapses outside LangChain ecosystem.

### 3. PromptLayer — 8.7
- Best pure registry product experience for mixed technical/non-technical teams.
- Dynamic release labels + traffic split are production-proven differentiators.
- Risk: closed-source; self-host only on larger deals.

### 4–10
See main README table and EVAL-KIT for operational test protocols.

## How Scores Are Updated

Scores move only when:
1. Public evidence changes (new compliance certs, self-host improvements, major feature launches).
2. Acquisition or pivot risk materializes.
3. Independent production references appear or disappear.

This is deliberately conservative. Marketing claims alone never raise a score.
