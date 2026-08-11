# LLM Gateway (Mind-Reply)

Drop-in multi-provider router with tiered model selection.

## Files
- `model-tiering.json` — source of truth for tiers and routing rules
- `gateway.js` — the actual router

## Quick use

```js
import { pickTier, routeToTier } from "./gateway.js";

const tier = pickTier({ task: "architecture_review" });
const { text, model, provider } = await routeToTier(tier, "Review this deploy plan...");
```

## Environment variables required
- `ANTHROPIC_API_KEY`
- `OPENAI_API_KEY`
- `GOOGLE_API_KEY` (optional)
- `LOCAL_MODEL_BASE_URL` (optional, defaults to http://localhost:11434/v1)

Never commit real keys. Set them in Vercel project env, Docker, or Windows service environment.

## Where it belongs
- packages/llm-gateway inside mind-reply-core
- or any engine that needs multi-model routing (Gmail Engine, Profit Engine, Ops Agent)
