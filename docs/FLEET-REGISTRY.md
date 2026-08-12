# MindReply Fleet Registry — SRE War-Room view
**Generated:** 2026-08-12 02:40 EEST  
**Source:** Vercel team `angelk` + GitHub `angellllkr-eng`  
**Principle:** paste-first evidence · no invented health 

## Clusters (logical)

| Cluster | Role | Blast radius if down |
|---------|------|----------------------|
| **CORE** | Canonical product + control | Whole estate identity |
| **RADAR** | SIntelligence / seller surface | Opportunity + ranking only |
| **GATEWAY** | LLM routing | All agents using /api/llm |
| **VOICE** | a11-k multiverse realtime | Voice demos only |
| **RESELLER** | ResellerPro copies | Commerce experiments |
| **NOISE** | Scaffolds / duplicates | None — archive |

---

## CORE — keep, protect main

| Asset | Evidence | Gate |
|-------|----------|------|
| mind-reply-core (GitHub) | Canonical monorepo + packages/llm-gateway | Branch-protect main |
| agent-control-plane (GitHub) | Agent mesh · 75 open issues | Branch-protect main |
| nexus-core (GitHub + Vercel) | Owner command plane | Branch-protect main |
| saas-starter (GitHub + Vercel prj_rQzTP9kRu09asrrnzcrham7oi3zw) | /api/llm route live in code | Env: ANTHROPIC_API_KEY, OPENAI_API_KEY then redeploy |
| mindreply (Vercel prj_C1cMWS3hIZkZarqpCf5Xbmjujquq) | Brand surface | — |
| a11-k-core / a11-k-primary (Vercel) | Live 200 surfaces (prior decision-log) | — |

## RADAR — keep

| Asset | Evidence | Gate |
|-------|----------|------|
| enterprise-engine-radar (GitHub + Vercel prj_QoKbfB28dkOTwdgLWfxobkKF9WUO) | https://enterprise-engine-radar-bgh14wkti-angelk.vercel.app READY | — |
| opportunity-radar (GitHub) | Python opportunity track | — |

## GATEWAY — keep

| Asset | Evidence | Gate |
|-------|----------|------|
| packages/llm-gateway in radar + mind-reply-core | model-tiering.json + gateway.js | Keys on saas-starter |
| saas-starter `/api/llm` | Route committed | Redeploy after env |

## VOICE — gated

| Asset | Evidence | Gate |
|-------|----------|------|
| a11-k-multiverse (Vercel prj_FMXa3IdiAQaX60hq9YTJUUsEiOf8) | https://a11-k-multiverse.vercel.app | **AI_GATEWAY_API_KEY** on Production + redeploy |

## RESELLER — consolidate

Multiple Vercel projects share the name family. Treat as one product line; pick a single canonical deploy and freeze the rest.

| Project | Note |
|---------|------|
| resellerpro-platform | Likely canonical name |
| resellerpro-platform-8psz / -u16a / -fqnz / -original / 11 | Copies — freeze or delete after confirming no unique traffic |

## NOISE — archive (GitHub ARCHIVE.md already present)

a11k-surface · EPHEMERAL · source1 · source2 · Own1 · nextjs1 · nextjs-boilerplate · eve-chat-1 · eve-chat-template · express-js-on-vercel · unapolagetic-cosmetics

Matching Vercel projects (nextjs1, eve-chat-*, express-js-on-vercel, unapolagetic_cosmetics, ephemeral) can be deleted after GitHub archive.

---

## Rollback selector (estate-level)

| Failure | Action |
|---------|--------|
| Bad radar deploy | Vercel → enterprise-engine-radar → previous READY deployment rollback |
| Broken /api/llm | Revert saas-starter `src/app/api/llm/route.ts` or unset keys to fail closed |
| Voice outage | Confirm AI_GATEWAY_API_KEY; if missing, surface stays static — no emergency |
| Accidental delete of core repo | GitHub does not hard-delete immediately; contact support / restore from fork if any |

## Human gates remaining (cannot be automated by tools)

1. Archive 11 GitHub repos (Settings → Archive)
2. Branch-protect main on CORE five
3. Set ANTHROPIC_API_KEY + OPENAI_API_KEY on saas-starter
4. Set AI_GATEWAY_API_KEY on a11-k-multiverse if voice is priority

## Citation

- Vercel list_projects team_0plIJmQLgZC1wVv9zI2eVf3B — 2026-08-12
- GitHub search user:angellllkr-eng — 2026-08-12
- PINS asset-map + decision-log — 2026-08-12
