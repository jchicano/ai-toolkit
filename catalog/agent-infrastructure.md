# Agent Infrastructure & Services

**Last Updated:** 2026-11-26

Services and local tools that give agents their own identity, channels (email, accounts), and web access instead of borrowing yours.

- **[AgentMail](https://www.agentmail.to/)** — Email inboxes built for AI agents: each agent gets its own real address to send, receive, reply in threads, and receive sign-up verification codes, with its own sending reputation separate from your personal Gmail. API + SDKs (Python, Node, Go), MCP server, CLI, and skills; free tier. Available as an official plugin in Grok Bot (OAuth, 24 email tools). Site: [agentmail.to](https://www.agentmail.to/). Docs: [docs.agentmail.to](https://docs.agentmail.to). MCP: [agentmail-to/agentmail-mcp](https://github.com/agentmail-to/agentmail-mcp).

## Web access

- **[DonSeTch](https://github.com/dondai44423/donsetch)** — Web search, fetch, crawl, and screenshot for AI agents in one local Rust binary; no API keys or accounts. Exposed over MCP (~2k tokens of tool schemas) or CLI; page reads use real client profiles and embedded V8 without launching a browser (Chromium only for screenshots). Self-hosted alternative to Firecrawl Cloud. Linux, macOS, Windows. AGPL-3.0. Install: `npm install -g donsetch && donsetch doctor`.
