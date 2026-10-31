# Skill Management

**Last Updated:** 2026-10-31

Where to find, assess, and install agent skills and plugins.

- **[skills.sh](https://skills.sh/)** — Skill discovery and security assessments.
- **[Claude Plugins Official](https://github.com/anthropics/claude-plugins-official)** — Official Claude Code plugin repository.
- **[Caveman](https://github.com/juliusbrussee/caveman)** — Skill + proxy that cuts agent tokens by talking in a terse “caveman” voice while keeping code exact. Claims large input-token savings across many agents. Install notes in the repo `INSTALL.md`.
- **[pstack](https://github.com/cursor/plugins/tree/main/pstack)** — Cursor plugin (by poteto) that turns the agent into a rigorous engineering team: less slop, fearless parallelism via `/poteto-mode`, multi-model workflows. Install in Cursor: `/add-plugin pstack`. Claude Code: `/plugin marketplace add cursor/plugins` then `/plugin install pstack@cursor-plugins`.
- **[Karpathy-inspired Claude Code guidelines](https://github.com/multica-ai/andrej-karpathy-skills)** — Single `CLAUDE.md` derived from Andrej Karpathy’s notes on LLM coding pitfalls: think before coding, simplicity first, surgical changes, goal-driven execution.
- **[Matt Pocock — Skills for Real Engineers](https://github.com/mattpocock/skills)** — Small, composable agent skills for real engineering (not vibe-coding process frameworks). Works across Claude Code, Codex, Copilot, Gemini CLI, and more. Install (Claude Code): `claude plugin install mattpocock-skills@claude-plugins-official`. Catalog: [skills.sh/mattpocock/skills](https://skills.sh/mattpocock/skills).

## Install notes
- Install a skill from GitHub: `npx skills add <github-org>/<repo>`
- List installed skills: `ls -1 .agents/skills/`
- Skills use a universal symlink structure compatible with Claude Code, Zed, and Cursor (`.agents/skills/` as storage, `.claude/skills/` as symlinks).

See also: [Claude Code skills](../claude-code/skills.md) and [installation sources](../claude-code/installation-sources.md).
