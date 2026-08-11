# 04 — Evaluation & Observability Tests

## Evaluation
- [ ] Offline evaluation against a dataset
- [ ] LLM-as-judge or custom scorers
- [ ] Human annotation / HITL queue
- [ ] Regression suite that can gate CI
- [ ] Online evaluation on live traffic (or clear path to it)

## Observability & Cost
- [ ] Full traces with nested spans (agent / tool / retrieval)
- [ ] Cost attribution by prompt version / feature / tenant
- [ ] Latency percentiles and error rates
- [ ] Ability to filter traces by prompt version

## Production Safety
- [ ] Ability to compare two versions side-by-side on the same dataset
- [ ] Clear failure modes when evaluation score drops
