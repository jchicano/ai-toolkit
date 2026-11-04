# AI Agent Orchestration & Routing

**Last Updated:** 2026-11-04

Tools for coordinating, routing, and running AI coding agents.

- **[ECC — Agent Harness Operating System](https://github.com/affaan-m/ECC)** — Complete system for AI agent workflows: 68 specialized agents, 292+ reusable skills, runtime hooks for deterministic checks, security scanning (AgentShield), and a memory vault. Install: `npx ecc-universal@2.2.1 setup --mode claude-plugin --scope project`
- **[CLI Agent Orchestrator (CAO)](https://github.com/awslabs/cli-agent-orchestrator)** — Multi-agent coordination platform. A supervisor coordinates specialist AI coding assistants (Claude Code, Cursor, GitHub Copilot CLI, etc.) on parallel or sequential tasks. Web UI, persistent memory, workflow automation, EKS deployment support.
- **[Spec Kit](https://github.com/github/spec-kit)** — GitHub’s open-source toolkit for Spec-Driven Development (and bug-fix / idea-assessment processes) with coding agents: templates, extensions, presets, workflows. Docs: [github.github.io/spec-kit](https://github.github.io/spec-kit/). Install: `uv tool install specify-cli` then `specify init <project> --integration <agent>`.
- **[The Agency (agency-agents)](https://github.com/msitarzewski/agency-agents)** — Large roster of specialized AI agent personalities (engineering, design, marketing, security, etc.) with workflows and deliverables. Install via desktop app ([agencyagents.app](https://agencyagents.app)) or `./scripts/install.sh` into Claude Code, Cursor, Codex, Gemini, and more.
- **[herdr](https://github.com/herdrdev/herdr)** — Terminal runtime/multiplexer for coding agents: detachable sessions, multi-machine panes, working/blocked/idle status, agent-native CLI/socket API. Site: [herdr.dev](https://herdr.dev). Homebrew: `brew install herdr`.
- **[OmniRoute — Free AI Gateway](https://github.com/diegosouzapw/OmniRoute)** — Routes many AI providers through one endpoint. See [gateways.md](gateways.md) for details.

See also: [Claude Code plugins](../claude-code/plugins.md) for the installed ECC plugin.
