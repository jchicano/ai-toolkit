# AI Gateways & Provider Consolidation

**Last Updated:** 2026-11-13

Single endpoints that unify access to multiple AI providers.

- **[OmniRoute — Free AI Gateway](https://github.com/diegosouzapw/OmniRoute)** — Consolidates 357 AI providers through a single endpoint. 1.62B free tokens/month, 19 routing strategies, 15–95% token compression. Compatible with Claude Code, Cursor, Cline, and GitHub Copilot. Use it for multi-provider AI access and token budget optimization.
- **[FreeLLMAPI](https://github.com/tashfeenahmed/freellmapi)** — Aggregates free LLM tiers (34 providers, 635 free endpoints, ~7.4B tokens/month claimed) behind one OpenAI-compatible `/v1` API with smart routing, failover, and encrypted keys. Site: [freellmapi.co](https://freellmapi.co/). Personal experimentation only.
- **[Free Claude Code (FCC)](https://github.com/Alishahryar1/free-claude-code)** — Independent AGPL-3.0 router that points 12 coding harnesses (Claude Code, Codex, Pi, OpenCode, Cline, Hermes, DeepSeek Harness, Grok Build, Muse Code, Aider, Antigravity CLI, VS Code Chat) at 61 providers (free, paid, subscription, or local), with ~1.3B+ free tokens/month, retries, and fallbacks. Not affiliated with Anthropic; follows provider TOS. Install (macOS/Linux): `curl -fsSL "https://raw.githubusercontent.com/Alishahryar1/free-claude-code/main/scripts/install.sh" | sh`. Windows PowerShell: `& ([scriptblock]::Create((irm "https://raw.githubusercontent.com/Alishahryar1/free-claude-code/main/scripts/install.ps1")))`.
- **[DeepRelay](https://deeprelay.ai)** — Inference relay for frontier open models (DeepSeek, GLM, Kimi): chat, image & video on one flat subscription.
- **[Token Harbor](https://tokenharbor.ai)** — One OpenAI-compatible API for GPT, Claude, Gemini, DeepSeek and more: encrypted keys, automatic failover, per-token pricing, free tier.

## Local & self-hosted model apps

- **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)** — MIT-licensed, local-first all-in-one AI app by Mintplex Labs: chat with your documents (built-in RAG), no-code agents and MCP support, using local models (Ollama, LM Studio, built-in runner) or any cloud provider. Desktop app for macOS/Windows/Linux, or self-host via Docker. Site: [anythingllm.com](https://anythingllm.com/). Install: `brew install --cask anythingllm`.
- **[Open WebUI](https://github.com/open-webui/open-webui)** — Self-hosted, offline-capable ChatGPT-style web UI (~158k★) for Ollama and any OpenAI-compatible API: built-in RAG over documents, web search, tools/functions and MCP, pipelines, multi-user with RBAC. Site: [openwebui.com](https://openwebui.com). Docs: [docs.openwebui.com](https://docs.openwebui.com). Install: `pip install open-webui && open-webui serve` (or Docker: `ghcr.io/open-webui/open-webui:main`).
