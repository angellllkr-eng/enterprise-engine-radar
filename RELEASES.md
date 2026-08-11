<div align="center">

# Current Release Notes

**MindReply · Enterprise Engine Radar**  
*As of 11 August 2026*

</div>

---

Only material, public signals. No filler.

### Langfuse
- **v4.6.0** released 6 August 2026 (also v4.5.0 same day).
- v4 observations-first data model: faster dashboards and evals at scale; input/output now read from the relevant observation rather than assembled at the full-trace level.
- Continuous shipping cadence (multiple 4.x releases in early August).
- Self-host remains first-class (Docker, Helm, Terraform for AWS/Azure/GCP).
- Still MIT core; EE for advanced admin features.

### LangSmith
- Self-hosted **0.16.0** (Aug 2026): SmithDB (purpose-built columnar store), Engine, LLM Gateway, Sandboxes.
- **Managed Deep Agents** public beta (Aug 2026): author locally, deploy to managed runtime with persistence, streaming, sandboxes.
- **LLM Gateway** public beta: spend/rate limits, fallbacks, redaction across providers.
- **Sandboxes** GA earlier in 2026: microVM isolation, snapshots, forks, Service URLs.
- **Engine**: clusters production failures, proposes root causes and eval coverage.

### PromptLayer
- 10 August 2026 changelog: OpenRouter audio models, image generation (including vector/SVG), and speech models in the Playground with real-time playback and parameter controls.
- Registry, release labels, and traffic-split remain the core product surface.
- JS SDK and agent skill/MCP setup path actively maintained.

### Arize
- **Signal** generally available (late July 2026): continuous review of production traces, ranked issues, proposed fixes.
- Managed agents on Enterprise; Agent-as-a-Judge and skills support.
- Phoenix continues as the open observability surface with PXI agent and remote MCP server.

### Braintrust
- Topics (beta): clusters traces into recurring issues and sentiment shifts.
- Gateway beta for multi-provider access with automatic tracing.
- Core loop (trace → dataset → scorer → environment) unchanged and still the strongest pure-eval path.

### Portkey
- Gateway capabilities remain the differentiator: routing, fallbacks, semantic caching, budget limits across a large model catalog.
- Often paired with a primary observability/eval engine rather than used alone.

Update this file when a platform ships a release that changes enterprise readiness, self-host posture, or core evaluation/observability behaviour.

---

<div align="center">

[mind-reply.com](https://mind-reply.com)

</div>
