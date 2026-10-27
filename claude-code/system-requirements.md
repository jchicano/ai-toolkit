# System Requirements

**Last Updated:** 2026-10-27

> Part of the [Claude Code harness reference](harness.md). Source gist last updated 2026-09-22.

## Runtime Dependencies
- **Node.js** - npm/npx for skill management
- **Python 3.13.15** - Required for claude-obsidian
- **Bun 1.4.2** - Used by claude-mem
- **uv 0.12.16** - Python package manager for claude-mem
- **GitHub CLI (gh)** v2.98.0 - Required for code-review
- **Playwright** (latest) - Browser automation

## Storage Locations
- Skills: `~/.claude/plugins/marketplaces/` + `.agents/skills/`
- Claude Code skills: `.claude/skills/` (symlinks)
- Claude-mem: `~/.claude-mem/`
- Obsidian vaults: User-specified (default: `~/.claude-obsidian-vault/`)
- Implementation plans: `docs/superpowers/plans/`
- ECC config: `.claude/` (settings.json, hooks, agents)
