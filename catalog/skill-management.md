# Skill Management

**Last Updated:** 2026-10-31

Where to find, assess, and install agent skills and plugins.

- **[skills.sh](https://skills.sh/)** — Skill discovery and security assessments.
- **[Claude Plugins Official](https://github.com/anthropics/claude-plugins-official)** — Official Claude Code plugin repository.
- **[Knowledge Work Plugins](https://github.com/anthropics/knowledge-work-plugins)** — Anthropic’s open-source marketplace of 11 role plugins for [Claude Cowork](https://claude.com/product/cowork) (also Claude Code): sales, marketing, product, finance, legal, data, support, productivity, enterprise search, bio-research, plus plugin management. Skills + slash commands + MCP connectors. Install: `claude plugin marketplace add anthropics/knowledge-work-plugins` then e.g. `claude plugin install sales@knowledge-work-plugins`. Browse: [claude.com/plugins](https://claude.com/plugins/).
- **[Caveman](https://github.com/juliusbrussee/caveman)** — Skill + proxy that cuts agent tokens by talking in a terse “caveman” voice while keeping code exact. Claims large input-token savings across many agents. Install notes in the repo `INSTALL.md`.
- **[RTK (Rust Token Killer)](https://github.com/rtk-ai/rtk)** — Agent-agnostic CLI that compresses, routes, and filters what agents read/send (bash-output compression up to ~90%). Single Rust binary. Site: [rtk-ai.app](https://www.rtk-ai.app).
- **[pstack](https://github.com/cursor/plugins/tree/main/pstack)** — Cursor plugin (by poteto) that turns the agent into a rigorous engineering team: less slop, fearless parallelism via `/poteto-mode`, multi-model workflows. Install in Cursor: `/add-plugin pstack`. Claude Code: `/plugin marketplace add cursor/plugins` then `/plugin install pstack@cursor-plugins`.
- **[Karpathy-inspired Claude Code guidelines](https://github.com/multica-ai/andrej-karpathy-skills)** — Single `CLAUDE.md` derived from Andrej Karpathy’s notes on LLM coding pitfalls: think before coding, simplicity first, surgical changes, goal-driven execution.
- **[Matt Pocock — Skills for Real Engineers](https://github.com/mattpocock/skills)** — Small, composable agent skills for real engineering (not vibe-coding process frameworks). Works across Claude Code, Codex, Copilot, Gemini CLI, and more. Install (Claude Code): `claude plugin install mattpocock-skills@claude-plugins-official`. Catalog: [skills.sh/mattpocock/skills](https://skills.sh/mattpocock/skills).

## Install notes
- Install a skill from GitHub: `npx skills add <github-org>/<repo>`
- List installed skills: `ls -1 .agents/skills/`
- Skills use a universal symlink structure compatible with Claude Code, Zed, and Cursor (`.agents/skills/` as storage, `.claude/skills/` as symlinks).

See also: [Claude Code skills](../claude-code/skills.md) and [installation sources](../claude-code/installation-sources.md).
