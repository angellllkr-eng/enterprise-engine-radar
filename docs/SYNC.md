# Sync map — Personal ↔ Org

**Owner:** Angel K (`angellllkr-eng`)  
**Brand / public face:** Mind-Reply org

## Source of truth (personal)

| Asset | Repo | Notes |
|-------|------|-------|
| Enterprise ranking + EVAL-KIT + NEWS | `angellllkr-eng/enterprise-engine-radar` | Public seller/intel surface |
| LLM Gateway (tiering + router) | `angellllkr-eng/mind-reply-core/packages/llm-gateway` **and** copy here | Canonical code lives in core |
| Opportunity engine (30 classes) | `angellllkr-eng/opportunity-radar` | Separate, stricter evidence rules |
| Agent control plane | `angellllkr-eng/agent-control-plane` | Ops mesh |
| Isolation / hygiene plan | `docs/14-DAY-ISOLATION.md` (this repo) | Execute on personal mains first |

## Public org surfaces (Mind-Reply)

| Surface | Repo | Role |
|---------|------|------|
| A11-K brand | `Mind-Reply/A11-K` | Product identity + pages |
| Aurel | `Mind-Reply/Aurel` | Connectivity brand |
| own-core | `Mind-Reply/own-core` | Public templates / security guides |
| mindreply-org-site | `Mind-Reply/mindreply-org-site` | Landing |

## Rules
1. Proprietary routing, prompts, and isolation plans stay under personal control first.
2. Org repos stay clean brand / public templates — no secrets, no private engine guts.
3. When a module is ready for shared use, promote a clean copy into `mind-reply-core` (already done for llm-gateway).
4. Do not mirror the full radar or isolation plan into public org repos until there is real achievement to show.

Last sync: 2026-08-12
