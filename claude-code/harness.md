# Claude Code Harness

**Last Updated:** 2026-10-27 (migrated from gist; original content last updated 2026-09-22)

Complete Claude Code configuration reference: ECC harness, plugins, skills, tools, and related resources. This page is the standalone overview; detailed lists live in sibling files.

## At a glance

| Area | Summary | Details |
|------|---------|---------|
| Plugins | Official: superpowers, code-review (built-in). Third-party: ecc v2.2.1, claude-mem v13.25.1, claude-obsidian v2.2.0 | [plugins.md](plugins.md) |
| Skills | 73 installed (69 base + 4 from ECC); ECC offers 292+ on demand | [skills.md](skills.md) |
| Tools | Playwright (latest) | [tools.md](tools.md) |
| Runtime | Node.js, Python 3.13.15, Bun 1.4.2, uv 0.12.16, gh v2.98.0, Playwright | [system-requirements.md](system-requirements.md) |
| Commands | Skills, ECC, Playwright, claude-mem, code-review, Impeccable, animation | [quick-commands.md](quick-commands.md) |
| Sources | Upstream repos and sites for each component | [installation-sources.md](installation-sources.md) |

## Skill groups

- **Design & UI (34)** — Taste-Skill (13), UI UX Pro Max (7), Impeccable (1), Emil Kowalski (13)
- **Development & Planning (14)** — brainstorming, planning, TDD, debugging, code review, worktrees
- **Code Quality — Ponytail (6)** — YAGNI enforcement and over-engineering audits
- **Knowledge Management — Claude Obsidian (15)** — vault, wiki, and research skills

## Configuration Files

- `.claude/settings.json` - Enabled plugins (includes ECC)
- `.claude/settings.local.json` - Local permissions and hooks
- `.claude/skills/` - Skill symlinks
- `.agents/skills/` - Universal skill storage
- `docs/superpowers/plans/` - Implementation plans
- `.claude/ecc/` - ECC configuration and agents

## Related projects

Curated in the catalog: [orchestration](../catalog/orchestration.md) (ECC, CAO), [gateways](../catalog/gateways.md) (OmniRoute), [design](../catalog/design.md) (claude-webkit, Awesome Design.md, Refero Styles), [browser testing](../catalog/browser-testing.md) (Playwright, Browser MCP), [skill management](../catalog/skill-management.md) (skills.sh, Claude Plugins Official).

## Notes

- All skills use universal symlink structure compatible with Claude Code, Zed, Cursor
- Claude-mem observations persist across sessions
- Plans save to `docs/superpowers/plans/YYYY-MM-DD-<feature>.md`
- Ponytail intensity: `lite` < `full` (default) < `ultra`
- **Impeccable hooks**: Auto-check UI changes after Edit/Write (configured in settings.local.json)
- **ECC runtime**: 68 specialized agents, 292+ skills on-demand. Restart Claude Code after install.
- **OmniRoute**: Use for multi-provider AI access and token budget optimization
- **CAO**: Deploy multiple AI agents for parallel/sequential specialist tasks
- **Playwright**: Use for browser-based testing and automation workflows
