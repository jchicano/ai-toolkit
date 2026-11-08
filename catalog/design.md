# Frontend & Design Tools

**Last Updated:** 2026-11-08

Design systems, UI generators, and design-focused resources for AI agents.

## Tools
- **[Anime.js](https://animejs.com/)** — JavaScript animation engine ([juliangarnier/anime](https://github.com/juliangarnier/anime)). Lightweight API for timeline, stagger, SVG, and CSS-driven motion in the browser.
- **[claude-webkit](https://github.com/hainrixz/claude-webkit)** — Automated landing page builder. No-code website generator with 21 bundled skills, professional design output, and Vercel deployment.
- **[HTML Anything](https://github.com/nexu-io/html-anything)** — Agentic HTML editor: local coding-agent CLI writes ship-ready HTML (75 skills × 9 surfaces: magazine, deck, poster, XHS/tweet, prototype, data report, Hyperframes). Sandboxed preview; export WeChat/X/Zhihu/HTML/PNG. No API key. Site: [open-design.ai/html-anything](https://open-design.ai/html-anything/). Run: `pnpm install` then `pnpm -F @html-anything/next dev`.
- **[MotionSites](https://motionsites.ai/)** — Library of AI website prompts and motion/3D landing-page inspiration for Lovable, Bolt, Cursor, and Claude. Free Claude skill: [Motionsites-AI/claude-skill](https://github.com/Motionsites-AI/claude-skill) (`/plugin marketplace add Motionsites-AI/claude-skill` then `/plugin install motionsites-web-builder@motionsites`).

## Design systems (DESIGN.md)
- **[DESIGN.md (Google Labs)](https://github.com/google-labs-code/design.md)** — Format spec for describing a visual identity to coding agents (tokens + rationale). Lint/diff CLI: `npx @google/design.md lint DESIGN.md`. Spec: [stitch.withgoogle.com/docs/design-md/specification](https://stitch.withgoogle.com/docs/design-md/specification).
- **[Awesome Design.md](https://github.com/voltagent/awesome-design-md)** — Curated collection of 73+ DESIGN.md files from major brands (Claude, Stripe, Figma, Notion, Apple, Tesla, Spotify). AI-readable design systems with color palettes, typography, and components. 60+ companies analyzed. 117k stars.
- **[Refero Styles](https://styles.refero.design/)** — 2,000+ AI-readable design systems. DESIGN.md examples for AI agents. MCP integration.

## Design skill packs
These are installed in the Claude Code harness; see [claude-code/skills.md](../claude-code/skills.md#design--ui-34-skills).
- **[Taste-Skill](https://www.tasteskill.dev/)** — Anti-slop frontend design skill set (13 skills).
- **[UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)** — AI design-intelligence skill (79 searchable UI styles, design-system generator). Site: [uupm.cc](https://uupm.cc/). Install CLI: `npm install -g ui-ux-pro-max-cli` then `uipro init --ai <assistant>`. Claude Code: `/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill` then `/plugin install ui-ux-pro-max@ui-ux-pro-max-skill`.
- **[Impeccable](https://impeccable.style/)** — Complete design vocabulary for agents (critique, audit, polish, and more).
- **[Emil Kowalski skills](https://emilkowal.ski/skill)** — Design engineering and animation (13 skills).
- **[Interface Design](https://github.com/Dammyjay93/interface-design)** — Design-engineering skill for Claude Code and other agents, aimed at dashboards, apps, and admin panels (not marketing sites). Principle-based craft plus memory: saves spacing, color, and depth decisions to `.interface-design/system.md` and reloads them each session for consistent UI. Site: [interface-design.dev](https://interface-design.dev). Install: `npx skills add https://github.com/dammyjay93/interface-design --skill interface-design`.
