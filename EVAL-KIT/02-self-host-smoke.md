# 02 — Self-Host Smoke Protocol

**Goal:** Measure time-to-first-useful-signal in a clean environment.

## Protocol
1. Fresh VM or local Docker (no prior state).
2. Follow official self-host docs only (no tribal knowledge).
3. Instrument a minimal OpenAI or Anthropic call.
4. Confirm the following appear without custom glue:
   - Trace with latency + token counts
   - Prompt version linked to the trace
   - Basic cost attribution
   - Ability to label a version as “production”

## Metrics to Capture
- Wall-clock time to first successful trace
- Number of manual steps required
- Whether prompt registry was usable by a non-engineer without code changes
- Any forced external calls during core operation

## Pass Criteria
- Usable registry + tracing in < 45 minutes for an experienced platform engineer
- No mandatory data egress for core features
