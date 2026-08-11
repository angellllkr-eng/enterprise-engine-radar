# 04 — Evaluation & Observability Tests

## Evaluation
- [ ] Offline evaluation against a dataset
- [ ] LLM-as-judge or custom scorers
- [ ] Human annotation / HITL queue
- [ ] Regression suite that can gate CI
- [ ] Online evaluation on live traffic (or a clear, documented path to it)

## Observability & cost
- [ ] Full traces with nested spans (agent / tool / retrieval)
- [ ] Cost attribution by prompt version, feature, or tenant
- [ ] Latency percentiles and error rates
- [ ] Ability to filter traces by prompt version

## Production safety
- [ ] Side-by-side comparison of two versions on the same dataset
- [ ] Clear failure signal when evaluation scores drop
