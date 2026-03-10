# LBA Plugins

Claude Code plugin marketplace for [Little Bear Apps](https://littlebearapps.com).

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **pitchdocs** | Pitch-perfect documentation for every repository — READMEs that sell, changelogs, roadmaps, user guides, and docs suite auditing |
| **contextdocs** | AI context file management — generate, maintain, and audit AGENTS.md, CLAUDE.md, .cursorrules, and more with Signal Gate filtering and Context Guard hooks |
| **platform-sdk** | Platform SDK integration for Cloudflare Workers — enforces cost safety, circuit breakers, feature budgets, telemetry, and observability |

## Installation

```bash
# Add the marketplace (once)
/plugin marketplace add littlebearapps/lba-plugins

# Install a plugin
/plugin install pitchdocs@lba-plugins
/plugin install contextdocs@lba-plugins
```

## Updating

```bash
/plugin marketplace update lba-plugins
```
