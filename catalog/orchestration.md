# AI Agent Orchestration & Routing

**Last Updated:** 2026-11-06

Tools for coordinating, routing, and running AI coding agents.

- **[ECC — Agent Harness Operating System](https://github.com/affaan-m/ECC)** — Complete system for AI agent workflows: 68 specialized agents, 292+ reusable skills, runtime hooks for deterministic checks, security scanning (AgentShield), and a memory vault. Install: `npx ecc-universal@2.2.1 setup --mode claude-plugin --scope project`
- **[CLI Agent Orchestrator (CAO)](https://github.com/awslabs/cli-agent-orchestrator)** — Multi-agent coordination platform. A supervisor coordinates specialist AI coding assistants (Claude Code, Cursor, GitHub Copilot CLI, etc.) on parallel or sequential tasks. Web UI, persistent memory, workflow automation, EKS deployment support.
- **[Spec Kit](https://github.com/github/spec-kit)** — GitHub’s open-source toolkit for Spec-Driven Development (and bug-fix / idea-assessment processes) with coding agents: templates, extensions, presets, workflows. Docs: [github.github.io/spec-kit](https://github.github.io/spec-kit/). Install: `uv tool install specify-cli` then `specify init <project> --integration <agent>`.
- **[The Agency (agency-agents)](https://github.com/msitarzewski/agency-agents)** — Large roster of specialized AI agent personalities (engineering, design, marketing, security, etc.) with workflows and deliverables. Install via desktop app ([agencyagents.app](https://agencyagents.app)) or `./scripts/install.sh` into Claude Code, Cursor, Codex, Gemini, and more.
- **[herdr](https://github.com/herdrdev/herdr)** — Terminal runtime/multiplexer for coding agents: detachable sessions, multi-machine panes, working/blocked/idle status, agent-native CLI/socket API. Site: [herdr.dev](https://herdr.dev). Homebrew: `brew install herdr`.
- **[CLI-Anything](https://github.com/HKUDS/CLI-Anything)** — Make any software agent-native via generated CLIs (hub of community harnesses for CAD, office apps, editors, etc.). Hub: [clianything.cc](https://clianything.cc/) / [hkuds.github.io/CLI-Anything](https://hkuds.github.io/CLI-Anything/). Install hub: `pip install cli-anything-hub` then `cli-hub install <name>`.
- **[Orca](https://github.com/stablyai/orca)** — Orchestrator for fleets of coding agents (Claude Code, Codex, OpenCode, Pi, …): parallel git worktrees, desktop + mobile companion, remote runtime. Use your own subscriptions. Site: [orca.dev](https://orca.dev) / [onorca.dev](https://onorca.dev).
- **[Cline](https://github.com/cline/cline)** — Autonomous coding agent as IDE extension, desktop app, CLI (`npm i -g cline`), or SDK. Site: [cline.bot](https://cline.bot). Docs: [docs.cline.bot](https://docs.cline.bot).
- **[Pi](https://github.com/earendil-works/pi)** — Minimal, extensible coding-agent harness (unified LLM API, agent loop, TUI, CLI/SDK). Customize with extensions, skills, prompt templates, themes; share as Pi packages. Site: [pi.dev](https://pi.dev). Install: `curl -fsSL https://pi.dev/install.sh | sh` (or `npm i -g --ignore-scripts @earendil-works/pi-coding-agent`).
- **[Traycer](https://github.com/traycerai/traycer)** — Open-source AI orchestration desktop app (“nerve center” for agentic coding): BYOA, shared context across models/providers, agent-to-agent loops, collaboration boards. Site: [traycer.ai](https://traycer.ai). Docs: [docs.traycer.ai](https://docs.traycer.ai).
- **[OpenCode](https://github.com/anomalyco/opencode)** — Open-source AI coding agent (TUI, desktop, IDE): multi-session, any provider via Models.dev, free models included. Site: [opencode.ai](https://opencode.ai). Install: `curl -fsSL https://opencode.ai/v2/install | bash` (or `brew install anomalyco/tap/opencode-v2` / `npm i -g @opencode/cli@latest`).
- **[Command Code](https://commandcode.ai)** — Coding agent tuned for open models (tool-call repairs, token-efficient tools, taste learning). Alternative to Claude Code / Cursor / OpenCode / Copilot; also used as a model API by community providers. Site: [commandcode.ai](https://commandcode.ai).
- **[Freebuff](https://github.com/CodebuffAI/codebuff)** — Free coding agent (browser, desktop, CLI): frontier models funded by ads, no subscription. Site: [freebuff.com](https://freebuff.com/).
- **[Qoder](https://qoder.com)** — Agentic coding platform / AI programming IDE: conversational coding, completion, code generation; VS Code & JetBrains. Site: [qoder.com](https://qoder.com).
- **[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)** — Open-source agent harness (“everything is a plugin” via Cordis): docs, data, coding, scheduled tasks; desktop + web; composable community plugins. Site: [deepseek.com/en/harness](https://www.deepseek.com/en/harness/).
- **[OmniRoute — Free AI Gateway](https://github.com/diegosouzapw/OmniRoute)** — Routes many AI providers through one endpoint. See [gateways.md](gateways.md) for details.

See also: [Claude Code plugins](../claude-code/plugins.md) for the installed ECC plugin.

Special mention to [Jailbreaks](https://github.com/togg53192-cmd/jailbreaks)
