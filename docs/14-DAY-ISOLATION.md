# 14-Day Engine Isolation & Hygiene Plan
**For Angel K / Mind-Reply — August 2026**

Goal: Make the digital estate quiet, compartmentalized, and production-clean so the physical / Apple-adjacent moves can compound without noise.

## Phase 1 — Lockdown (Days 1–3)
- [ ] Day 1: Protect every important `main` branch (require PR, status checks, linear history). No direct pushes.
- [ ] Day 2: Delete or fully archive the 11+ dead / merged repos that still show up. Archiving is not the same as removing attack surface.
- [ ] Day 3: Switch to ephemeral issues only — create issue → open PR → merge → auto-close. Keep open-issue count near zero.

## Phase 2 — Alignment & Isolation (Days 4–7)
- [ ] Day 4: Map the 9 active repos 1:1 against the live engines (Profit, Message Refiner, AI Assistant, Gmail, A11-K surface).
- [ ] Day 5: Consolidate or delete the rest. Shared libraries get strict versioning; everything else goes.
- [ ] Day 6: Separate secrets and env vars per engine. No shared .env that can leak across engines.
- [ ] Day 7: Make sure no proprietary prompts, system prompts, or core weights live in any public-facing repo.

## Phase 3 — High Layer (Days 8–14)
- [ ] Days 8–9: Calibrate Message Refiner with your real writing samples so output stays in your register.
- [ ] Days 10–11: Shadow-state test for the AI Assistant (mirror a slice of live traffic into a twin).
- [ ] Days 12–13: Air-gapped simulation for any financial / Profit engine logic.
- [ ] Day 14: Full audit — branch protection holds, issues are ephemeral, engines are isolated, public footprint is clean.

## Permanent rules
1. Security is structural, not reactive.
2. Engines never share state unless they go through a verified gateway.
3. Ship finished work. Do not use the GitHub graph as a status feed.
4. Process the minimum data needed, then purge.

---
*Extracted and tightened from the August 2026 strategy notes. Execute this before expanding physical moats.*
