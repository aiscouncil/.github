## AI Supreme Council

Zero-hosting, browser-first AI council platform. Chat with Claude, GPT, Grok, Gemini, and 300+ models — no server, no setup. The URL is the bot.

**[aiscouncil.com](https://aiscouncil.com)** | **[Documentation](https://doc.aiscouncil.com)**

### What is this?

AI Supreme Council runs entirely in your browser. Bot configurations are encoded in the URL fragment — share a link, the recipient opens it, they have your exact bot. Just add their own API key.

- **6 providers** — Anthropic, OpenAI, xAI, Google Gemini, OpenRouter, Ollama (local)
- **50+ models** — including 20+ free models via OpenRouter and Gemini
- **LLM Council** — multiple models deliberate on your prompt (fan-out, peer review, synthesis)
- **Mini-programs** — sandboxed apps with SDK, marketplace, and permission system
- **Zero server dependency** — everything runs client-side with BYOK (Bring Your Own Key)

### Repositories

| Repo | Purpose |
|------|---------|
| **[registry](https://github.com/aiscouncil/registry)** | Community model and package registry (50 models, 6 providers) |
| **[support](https://github.com/aiscouncil/support)** | FAQ, security policy, acceptable use, contact info |

### For Developers

- **Add models** — PR to [registry/models.json](https://github.com/aiscouncil/registry/blob/main/models.json)
- **Build mini-programs** — Use the [SDK](https://doc.aiscouncil.com/advanced/self-hosting) (`window.ais` namespace)
- **Self-host** — Serve `index.html` from any static host. No build step, no dependencies.
