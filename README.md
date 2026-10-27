# AI Tools Aggregator

**Last Updated:** 2026-10-27

A curated, growing collection of AI tools, agent harnesses, skills, plugins, and resources. It started as a single gist documenting a Claude Code setup and is now organized into a browsable repository. The `catalog/` holds public, curated resources by category; `claude-code/` documents a full Claude Code harness (plugins, skills, tools, commands).

## Directory map

```
ai-tools-aggregator/
├── README.md                  # This index
├── catalog/                   # Curated public resources by category
│   ├── orchestration.md
│   ├── design.md
│   ├── gateways.md
│   ├── browser-testing.md
│   └── skill-management.md
├── claude-code/               # Claude Code harness reference
│   ├── README.md
│   ├── harness.md
│   ├── plugins.md
│   ├── skills.md
│   ├── tools.md
│   ├── system-requirements.md
│   ├── quick-commands.md
│   └── installation-sources.md
└── personal/                  # Machine-specific notes (keep private data out of public pushes)
```

## Table of contents

### Catalog
- [AI Agent Orchestration & Routing](catalog/orchestration.md)
- [Frontend & Design Tools](catalog/design.md)
- [AI Gateways](catalog/gateways.md)
- [Browser & Testing](catalog/browser-testing.md)
- [Skill Management](catalog/skill-management.md)

### Claude Code harness
- [Overview](claude-code/README.md)
- [Harness reference](claude-code/harness.md)
- [Plugins](claude-code/plugins.md)
- [Skills](claude-code/skills.md)
- [Tools](claude-code/tools.md)
- [System requirements](claude-code/system-requirements.md)
- [Quick commands](claude-code/quick-commands.md)
- [Installation sources](claude-code/installation-sources.md)

## How to use

- Browse `catalog/` to discover tools by category.
- Use `claude-code/` as a reference to reproduce or extend a Claude Code setup.
- To add a resource, append a bullet to the matching catalog file using the format:
  ``- **[Name](url)** — short description. Install: `command` `` (install line optional).

## Provenance

Originally migrated from the gist [Claude Code Harness](https://gist.github.com/jchicano/e19ebc7bf6df73e61d41cb7b6ddf754d) (last updated there 2026-09-22).
