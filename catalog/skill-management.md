# Skill Management

**Last Updated:** 2026-11-13

Where to find, assess, and install agent skills and plugins.

- **[skills.sh](https://skills.sh/)** — Skill discovery and security assessments.
- **[SkillsMP](https://skillsmp.com/)** — Community marketplace indexing millions of open-source agent skills from GitHub (Claude Code, Codex CLI, ChatGPT). Browse by category, occupation, or keyword; free REST API and MCP server (account needed for MCP, daily free quota).
- **[Claude Plugins Official](https://github.com/anthropics/claude-plugins-official)** — Official Claude Code plugin repository.
- **[Knowledge Work Plugins](https://github.com/anthropics/knowledge-work-plugins)** — Anthropic’s open-source marketplace of 11 role plugins for [Claude Cowork](https://claude.com/product/cowork) (also Claude Code): sales, marketing, product, finance, legal, data, support, productivity, enterprise search, bio-research, plus plugin management. Skills + slash commands + MCP connectors. Install: `claude plugin marketplace add anthropics/knowledge-work-plugins` then e.g. `claude plugin install sales@knowledge-work-plugins`. Browse: [claude.com/plugins](https://claude.com/plugins/).
- **[Caveman](https://github.com/juliusbrussee/caveman)** — Skill + proxy that cuts agent tokens by talking in a terse “caveman” voice while keeping code exact. Claims large input-token savings across many agents. Install notes in the repo `INSTALL.md`.
- **[RTK (Rust Token Killer)](https://github.com/rtk-ai/rtk)** — Agent-agnostic CLI that compresses, routes, and filters what agents read/send (bash-output compression up to ~90%). Single Rust binary. Site: [rtk-ai.app](https://www.rtk-ai.app).
- **[pstack](https://github.com/cursor/plugins/tree/main/pstack)** — Cursor plugin (by poteto) that turns the agent into a rigorous engineering team: less slop, fearless parallelism via `/poteto-mode`, multi-model workflows. Install in Cursor: `/add-plugin pstack`. Claude Code: `/plugin marketplace add cursor/plugins` then `/plugin install pstack@cursor-plugins`.
- **[Karpathy-inspired Claude Code guidelines](https://github.com/multica-ai/andrej-karpathy-skills)** — Single `CLAUDE.md` derived from Andrej Karpathy’s notes on LLM coding pitfalls: think before coding, simplicity first, surgical changes, goal-driven execution.
- **[Matt Pocock — Skills for Real Engineers](https://github.com/mattpocock/skills)** — Small, composable agent skills for real engineering (not vibe-coding process frameworks). Works across Claude Code, Codex, Copilot, Gemini CLI, and more. Install (Claude Code): `claude plugin install mattpocock-skills@claude-plugins-official`. Catalog: [skills.sh/mattpocock/skills](https://skills.sh/mattpocock/skills).

- **[Claude Code Templates (aitmpl)](https://github.com/davila7/claude-code-templates)** — Open catalog (~1,900 components: skills, agents, commands, MCPs, hooks, mods, loops) plus a CLI to install/configure Claude Code; also analytics, chat browser, health check. Browse: [aitmpl.com](https://aitmpl.com). Docs: [docs.aitmpl.com](https://docs.aitmpl.com/). Install: `npx claude-code-templates@latest`.

- **[i-have-adhd](https://github.com/ayghri/i-have-adhd)** — Skill/plugin that forces ADHD-friendly agent output: answer first, numbered steps, no fluff. Works across coding agents. See repo `INSTALL.md` / `AGENTS.md`.

- **[Agent Skills](https://github.com/addyosmani/agent-skills)** (Addy Osmani) — 25 production-grade engineering skills plus slash commands (`/spec`, `/plan`, `/build`, `/test`, `/review`, `/ship`, …) that walk agents through define → plan → build → verify → review → ship. Works with Claude Code, Cursor, Codex, Copilot, Cline, and more. Site: [skills.addy.ie](https://skills.addy.ie). Install: `npx skills add addyosmani/agent-skills`. Claude Code marketplace: `/plugin marketplace add addyosmani/agent-skills` then `/plugin install agent-skills@addy-agent-skills`.
- **[Awesome OpenClaw Skills](https://github.com/VoltAgent/awesome-openclaw-skills)** — Curated catalog of OpenClaw skills drawn from [ClawHub](https://clawhub.ai) (the official registry), with spam, duplicates, and known-malicious entries filtered out. Site: [clawskills.sh](https://clawskills.sh/). Install a skill: `openclaw skills install <skill-slug>` (or `npx clawhub install <skill-slug>`).
- **[Claude for Financial Services](https://github.com/anthropics/financial-services)** — Official Anthropic reference agents, skills, and connectors for investment banking, equity research, private equity, and wealth management (pitch decks, comps/DCF, earnings notes, reconciliations, KYC, and more). Available as Claude Cowork plugins or via the Managed Agents API; outputs are drafts for human review, not advice. Install (Claude Code): `claude plugin marketplace add anthropics/financial-services` then e.g. `claude plugin install financial-analysis@claude-for-financial-services`.

## Install notes
- Install a skill from GitHub: `npx skills add <github-org>/<repo>`
- List installed skills: `ls -1 .agents/skills/`
- Skills use a universal symlink structure compatible with Claude Code, Zed, and Cursor (`.agents/skills/` as storage, `.claude/skills/` as symlinks).

See also: [Claude Code skills](../claude-code/skills.md) and [installation sources](../claude-code/installation-sources.md).
