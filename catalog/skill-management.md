# Skill Management

**Last Updated:** 2026-10-27

Where to find, assess, and install agent skills and plugins.

- **[skills.sh](https://skills.sh/)** — Skill discovery and security assessments.
- **[Claude Plugins Official](https://github.com/anthropics/claude-plugins-official)** — Official Claude Code plugin repository.

## Install notes
- Install a skill from GitHub: `npx skills add <github-org>/<repo>`
- List installed skills: `ls -1 .agents/skills/`
- Skills use a universal symlink structure compatible with Claude Code, Zed, and Cursor (`.agents/skills/` as storage, `.claude/skills/` as symlinks).

See also: [Claude Code skills](../claude-code/skills.md) and [installation sources](../claude-code/installation-sources.md).
