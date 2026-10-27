# Claude Code Plugins

**Last Updated:** 2026-10-27

> Part of the [Claude Code harness reference](harness.md). Source gist last updated 2026-09-22.

## Official Plugins
- **superpowers@claude-plugins-official** - Official Claude Code superpowers plugin
- **code-review** (built-in) - Code review with GitHub integration (requires `gh` CLI)

## Third-Party Plugins
- **ecc@ecc** (v2.2.1)
  - Agent Harness Operating System
  - 68 specialized agents with isolated scope
  - 292+ reusable skills
  - Runtime hooks for deterministic checks
  - Security scanning (AgentShield)
  - Memory vault for session persistence
  - Source: https://github.com/affaan-m/ECC

- **claude-mem** (v13.25.1)
  - Persistent cross-session memory system
  - Worker running on http://127.0.0.1:37701
  - Storage: `~/.claude-mem`
  - Provider: Anthropic (local)
  
- **claude-obsidian** (v2.2.0)
  - Local-first knowledge base integration
  - Source: https://github.com/AgriciDaniel/claude-obsidian
  - Obsidian vault management and wiki skills
