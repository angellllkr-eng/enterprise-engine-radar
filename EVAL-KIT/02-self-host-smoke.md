# 02 — Self-Host Smoke Protocol

**Goal:** Measure time-to-first-useful-signal in a clean environment.

## Steps
1. Start from a fresh VM or local Docker host with no prior state.
2. Follow only the official self-host documentation for that platform.
3. Instrument a minimal OpenAI or Anthropic call (or the platform’s recommended first example).
4. Confirm without custom glue:
   - A trace appears with latency and token counts
   - The prompt version is linked to the trace
   - Basic cost attribution is visible
   - A version can be labelled production (or equivalent)

## Capture
- Wall-clock time to first successful trace
- Number of manual steps required
- Whether a non-engineer can see and understand the prompt version
- Any forced external network calls during core operation

## Pass bar
Usable registry + tracing in under 45 minutes for an experienced platform engineer, with no mandatory data egress for core features.
