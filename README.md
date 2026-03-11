<p align="center">
  <a href="https://littlebearapps.com"><img src="logo.jpg" alt="Little Bear Apps" width="200"></a>
</p>

<p align="center">
  <strong>LBA Plugins</strong><br>
  Claude Code plugin marketplace from <a href="https://littlebearapps.com">Little Bear Apps</a>
</p>

<p align="center">
  <a href="https://docs.anthropic.com/en/docs/claude-code/plugins"><img src="https://img.shields.io/badge/Claude_Code-Marketplace-D97757?logo=claude&logoColor=white" alt="Claude Code Marketplace"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/Licence-MIT-blue" alt="MIT Licence"></a>
  <a href="https://littlebearapps.com"><img src="https://img.shields.io/badge/Little_Bear_Apps-littlebearapps.com-orange" alt="Little Bear Apps"></a>
</p>

<p align="center">
  <a href="#-available-plugins">Plugins</a> · <a href="#-installation">Install</a> · <a href="#-plugin-highlights">Highlights</a> · <a href="#-about">About</a>
</p>

---

## 🔌 Available Plugins

| Plugin | What It Does | Version | Links |
|--------|-------------|---------|-------|
| **PitchDocs** | READMEs that sell, changelogs, roadmaps, user guides, and docs suite auditing — 16 skills, 15 commands | v2.0.0 | [Repo](https://github.com/littlebearapps/pitchdocs) |
| **ContextDocs** | Your AI agent maintains its own context files — CLAUDE.md, AGENTS.md, and 5 more, always fresh, always lean | v1.2.0 | [Repo](https://github.com/littlebearapps/contextdocs) |

## 💡 What Are Claude Code Plugins?

[Claude Code plugins](https://docs.anthropic.com/en/docs/claude-code/plugins) extend Claude's capabilities with domain-specific skills, slash commands, and automated agents. They're pure Markdown — no runtime dependencies, no build steps. Install a plugin and its skills are available in every session.

Marketplaces like this one let you discover and install plugins with a single command. Each plugin listed here is open-source and independently versioned.

## ⚡ Installation

```bash
# Add this marketplace (once)
/plugin marketplace add littlebearapps/lba-plugins

# Install a plugin
/plugin install pitchdocs@lba-plugins
/plugin install contextdocs@lba-plugins
```

### Updating

```bash
# Pull the latest plugin versions
/plugin marketplace update lba-plugins
```

## 🎯 Plugin Highlights

### PitchDocs

Generate and maintain public-facing repository documentation with a marketing edge.

```
/pitchdocs:readme              # Generate a benefit-driven README
/pitchdocs:changelog           # Changelog from git history in user language
/pitchdocs:docs-audit          # Audit your full documentation suite
/pitchdocs:features benefits   # Extract features and translate to user benefits
```

See the full command list in the [PitchDocs README](https://github.com/littlebearapps/pitchdocs#readme).

### ContextDocs

Keep AI context files fresh and consistent across tools.

```
/contextdocs:ai-context          # Generate context files for your project
/contextdocs:ai-context audit    # Check context file health and freshness
/contextdocs:context-guard       # Install hooks that warn on stale context
/contextdocs:context-verify      # Score context file quality (0–100)
```

See the full command list in the [ContextDocs README](https://github.com/littlebearapps/contextdocs#readme).

## 🐻 About

[Little Bear Apps](https://littlebearapps.com) builds microtools — small, focused utilities that do one thing well. These plugins follow the same philosophy: each solves a specific documentation or developer-experience problem without bloat.

## 📄 Licence

This marketplace catalogue is released under the [MIT Licence](LICENSE). Each plugin is independently licensed — see [PitchDocs licence](https://github.com/littlebearapps/pitchdocs/blob/main/LICENSE) and [ContextDocs licence](https://github.com/littlebearapps/contextdocs/blob/main/LICENSE).
