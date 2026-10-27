# Quick Commands

**Last Updated:** 2026-10-27

> Part of the [Claude Code harness reference](harness.md). Source gist last updated 2026-09-22.

## Skill Management
```bash
# Install a skill from GitHub
npx skills add <github-org>/<repo>

# List installed skills
ls -1 .agents/skills/
```

## ECC
```bash
# Setup or update ECC
npx ecc-universal@2.2.1 setup --mode claude-plugin --scope project

# Available ECC agents and skills
/ecc-help
```

## Playwright
```bash
# Install browsers
playwright install

# Run browser automation
npx playwright test
```

## Claude-mem
```bash
# Start worker
npx claude-mem start

# Check status
curl http://127.0.0.1:37701

# Learn entire codebase
/learn-codebase

# Search memory
/mem-search <query>
```

## Code Review
```bash
# Review current diff
/code-review

# Review with PR comments
/code-review --comment

# Apply fixes
/code-review --fix

# Adjust depth
/code-review [low|medium|high|max]
```

## Impeccable Design
```bash
# Initialize project context
/impeccable init

# Design review with scoring
/impeccable critique <target>

# Technical quality checks
/impeccable audit <target>

# Final quality pass
/impeccable polish <target>
```

## Animation & Motion
```bash
# Build web animation
/animate

# Review existing animations
/review-animations

# Find animation opportunities
/find-animation-opportunities

# Audit all animations
/improve-animations
```
