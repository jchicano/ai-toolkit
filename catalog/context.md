# Context & Codebase Packing

**Last Updated:** 2026-11-04

Tools that pack repositories or projects into AI-friendly context for LLMs.

- **[Repomix](https://repomix.com/)** — Packs an entire repository into a single AI-friendly file for Claude, ChatGPT, Gemini, and other LLMs. Source: [yamadashy/repomix](https://github.com/yamadashy/repomix).
- **[Context Mode](https://github.com/mksglu/context-mode)** — Context-window optimization for coding agents: sandboxes tool output (~98% reduction claimed), persists session memory, and enforces routing across many platforms via MCP + hooks.
- **[claude-mem](https://github.com/thedotmack/claude-mem)** — Persistent cross-session memory for coding agents: captures session work, compresses it with AI, and reinjects relevant context later. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode, and more. Site: [claude-mem.ai](https://claude-mem.ai). See also [claude-code/plugins.md](../claude-code/plugins.md).
- **[CodeGraph](https://github.com/colbymchenry/codegraph)** — Local pre-indexed code knowledge graph that auto-syncs on changes; gives agents surgical context with fewer tokens/tool calls. Works with Claude Code, Cursor, Codex, Copilot, OpenCode, and more. Docs: [colbymchenry.github.io/codegraph](https://colbymchenry.github.io/codegraph/).
