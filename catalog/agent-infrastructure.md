# Agent Infrastructure & Services

**Last Updated:** 2026-11-26

Services and local tools that give agents their own identity, channels (email, accounts), app connections, and web access instead of borrowing yours.

- **[AgentMail](https://www.agentmail.to/)** — Email inboxes built for AI agents: each agent gets its own real address to send, receive, reply in threads, and receive sign-up verification codes, with its own sending reputation separate from your personal Gmail. API + SDKs (Python, Node, Go), MCP server, CLI, and skills; free tier. Available as an official plugin in Grok Bot (OAuth, 24 email tools). Site: [agentmail.to](https://www.agentmail.to/). Docs: [docs.agentmail.to](https://docs.agentmail.to). MCP: [agentmail-to/agentmail-mcp](https://github.com/agentmail-to/agentmail-mcp).

## App connectors & MCP gateways

- **[Executor](https://executor.sh/)** — Your agents' cloud: connect accounts (Gmail, GitHub, Linear, Stripe, Slack, …) or existing MCP servers once and expose them to every agent (Claude Code, Codex, Cursor, ChatGPT, Gemini) through one MCP server, with code mode, skills, storage, schedules, webhooks, durable workflows, and small apps built on top. Runs no AI itself. Cloud (free up to 3 people; Team $15/member/mo), Desktop beta (macOS/Windows/Linux), or self-hosted (free). CLI: `npm i -g executor@beta`.
- **[Composio](https://composio.dev/)** — Secure access to 2,000+ apps for any AI (ChatGPT/Codex, Claude, Claude Code plugin, Cursor via MCP URL, Grok Bot, Hermes, OpenClaw) with managed OAuth, multiple accounts per app, per-action limits/approvals, and audit log; developer SDKs and Proxy Execute for backend agents. Free Hobby plan (100k tool calls/mo); SOC 2 Type II. Docs: [docs.composio.dev](https://docs.composio.dev).
- **[Upsy](https://upsy.ai/home)** — Control layer between your AI assistants and your apps: connect Gmail, Calendar, Slack, Notion, etc. once, set per-assistant/per-app permissions (full, read-only, chosen actions, off), full action history, rogue-agent alerts and one-click kill switch; shared signed-in browser, files and memory stored in your own Drive/Dropbox/S3; team channels where agents and people collaborate. Free. Coding agents: `claude mcp add --transport http upsy https://upsy.ai/connect`.

## Web access

- **[DonSeTch](https://github.com/dondai44423/donsetch)** — Web search, fetch, crawl, and screenshot for AI agents in one local Rust binary; no API keys or accounts. Exposed over MCP (~2k tokens of tool schemas) or CLI; page reads use real client profiles and embedded V8 without launching a browser (Chromium only for screenshots). Self-hosted alternative to Firecrawl Cloud. Linux, macOS, Windows. AGPL-3.0. Install: `npm install -g donsetch && donsetch doctor`.
