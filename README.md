# Agent Templates — Claude Code components, curated for a working stack

![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)
![Components](https://img.shields.io/badge/components-1892-blue)
![Catalog](https://img.shields.io/badge/catalog-1%2C940%2B%20components-teal)

<img src="agent-templates-banner.png" alt="Agent Templates" width="100%" />

A stacked arsenal of agents, hooks, commands, MCP configs, sandbox runtimes, loops, mods, settings and skills — drawn from a 1,940+ component open-source catalog and organized in a clean layout so future AI agents can find and load what they need fast. Full list: [INDEX.md](INDEX.md).

## What's inside — 1892 files

| Folder | Files | What it is |
| --- | --- | --- |
| `agents/` | 433 | Every agent in the catalog: development teams, security, git, devops, documentation, data/AI, business, research, ffmpeg, Obsidian ops and more |
| `skills/` | 400 | Eight complete skill categories: workflow-automation, web-development, database, video, media, web-data, git, analytics |
| `mods/` | 383 | Full app mods / behaviour packs |
| `commands/` | 348 | Every slash command: git flow, deployment/release, testing, project setup |
| `hooks/` | 91 | Security pack (read-only subagent guard, dangerous-command blocker, secret scanner, env protection, force-push blocker), quality gates (plan/tdd/scope), monitoring (LangSmith tracing), git + automation |
| `mcps/` | 111 | MCP server configs: browser automation, databases, devtools (GitHub, Context7, Firecrawl, Chrome DevTools), filesystem, web, research, productivity |
| `settings/` | 82 | Settings presets |
| `sandbox/` | 25 | Real isolation runtimes: Docker, E2B, Cloudflare |
| `loops/` | 18 | Loop definitions |
| `plugins/` | 1 | Plugin manifests |

Everything above is the complete catalog set for its type, except `skills/`: the catalog holds 5,711 skill files, and this repo carries the eight categories above in full (seven decorative PNG assets were left out — the pack is text-only; the skills themselves are complete). The remaining skill categories install in one line from the source catalog (below).

## Use it

Components are plain files — read before you install anything.

- **Claude Code:** copy agents into `.claude/agents/`, commands into `.claude/commands/`, hooks into `.claude/hooks/` with their settings snippets, skills into `.claude/skills/`, MCP configs into your MCP settings.
- **Any other agent surface:** agents, commands and skills are markdown and port directly; hooks are Claude Code settings hooks and need adapting.
- Or install anything from the source catalog with its own CLI: `npx claude-code-templates@latest --agent <category>/<name>`.

## Credit & license

All components come from [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) by Daniel (San) Ávila and contributors, MIT-licensed — see [LICENSE](LICENSE). This repo is a curated selection with selection notes, not an official release of that project, and is not affiliated with it or with Anthropic.
