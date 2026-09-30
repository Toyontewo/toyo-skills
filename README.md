<div align="center">

# Toyo Skills

**A small, practical collection of specialist agent skills I actually use.**

[![Bundled Skills](https://img.shields.io/badge/bundled_skills-7-6C5CE7?style=for-the-badge)](#bundled-skills)
[![Specialist Add-ons](https://img.shields.io/badge/specialist_add--ons-5-0EA5E9?style=for-the-badge)](#specialist-add-ons)
[![Agent Skills](https://img.shields.io/badge/Agent_Skills-compatible-111827?style=for-the-badge)](https://agentskills.io)
[![License](https://img.shields.io/badge/license-MIT-22C55E?style=for-the-badge)](LICENSE)

For Codex, Claude Code, and other agents that support the open Agent Skills format.

</div>

## Quick start

List the bundled skills:

```bash
npx skills add Toyontewo/toyo-skills --list
```

Install one skill:

```bash
npx skills add Toyontewo/toyo-skills --skill stop-slop
```

Install all bundled skills:

```bash
npx skills add Toyontewo/toyo-skills --all
```

## Bundled skills

These are complete, discoverable skill entries under `skills/<skill-name>/SKILL.md`.

| Skill | What it does | Credit | Install |
| --- | --- | --- | --- |
| [`artifacts-builder`](skills/artifacts-builder) | Builds complex, interactive HTML artifacts with React, Tailwind, and shadcn/ui. | [Anthropic](https://github.com/anthropics/skills) | `npx skills add Toyontewo/toyo-skills --skill artifacts-builder` |
| [`excalidraw-diagram`](skills/excalidraw-diagram) | Creates structured Excalidraw diagrams for workflows, systems, and client deliverables. | [AY Automate](https://github.com/walidboulanouar/Ay-Skills) | `npx skills add Toyontewo/toyo-skills --skill excalidraw-diagram` |
| [`mcp-client`](skills/mcp-client) | Connects to MCP servers without loading every tool definition into context at once. | [AY Automate](https://github.com/walidboulanouar/Ay-Skills) | `npx skills add Toyontewo/toyo-skills --skill mcp-client` |
| [`notebooklm`](skills/notebooklm) | Queries NotebookLM for source-grounded research and citation-backed answers. | [PleasePrompto](https://github.com/PleasePrompto/notebooklm-skill) | `npx skills add Toyontewo/toyo-skills --skill notebooklm` |
| [`skill-creator`](skills/skill-creator) | Guides the design, structure, validation, and packaging of reusable agent skills. | [Anthropic](https://github.com/anthropics/skills) | `npx skills add Toyontewo/toyo-skills --skill skill-creator` |
| [`stop-slop`](skills/stop-slop) | Removes predictable AI writing patterns and makes prose more natural. | [Hardik Pandya](https://github.com/hardikpandya/stop-slop) | `npx skills add Toyontewo/toyo-skills --skill stop-slop` |
| [`upwork-ai-automation-proposal-generator`](skills/upwork-ai-automation-proposal-generator) | Produces a proposal, build plan, Loom script, workflow, macro, and teleprompter for AI automation jobs. | [Toyo Ntewo](https://github.com/Toyontewo/upwork-ai-automation-proposal-generator) | `npx skills add Toyontewo/toyo-skills --skill upwork-ai-automation-proposal-generator` |

## Specialist add-ons

These tools have their own installers or larger upstream repositories, so this library keeps only a short installation guide instead of republishing the entire project.

| Add-on | What it unlocks | Guide |
| --- | --- | --- |
| `agent-browser` | Browser automation with stable, agent-friendly element references. | [Install guide](skills/agent-browser/INSTALL.md) |
| `claude-seo` | Technical SEO, AI-search, schema, and Core Web Vitals audits. | [Install guide](skills/claude-seo/INSTALL.md) |
| `remotion-best-practices` | Domain-specific guidance for creating React-based Remotion videos. | [Install guide](skills/remotion-best-practices/INSTALL.md) |
| `superpowers` | A structured agentic development workflow built around specs, worktrees, TDD, and review. | [Install guide](skills/superpowers/INSTALL.md) |
| `ui-ux-pro-max` | A large design-intelligence library covering UI styles, palettes, typography, and framework guidance. | [Install guide](skills/ui-ux-pro-max/INSTALL.md) |

## Manual installation

Copy a bundled skill's entire folder into the directory used by your agent:

| Agent | Global directory | Project directory |
| --- | --- | --- |
| Codex | `~/.codex/skills/` | `.codex/skills/` |
| Claude Code | `~/.claude/skills/` | `.claude/skills/` |
| Shared or generic agents | `~/.agents/skills/` | `.agents/skills/` |

Example:

```bash
cp -R skills/stop-slop ~/.codex/skills/stop-slop
```

Always copy the whole folder. Several skills depend on their included references, scripts, templates, or assets.

## Why this collection is small

This is a personal working library, not a catalogue of every skill available online. The previous bulk marketing set and broad design skills were intentionally removed. New additions should be focused, useful in a real workflow, and something Toyo expects to use.

## Licensing and credits

The root [MIT license](LICENSE) covers Toyo's original work and repository curation. Third-party files retain their own terms and attribution. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and [`licenses/`](licenses/).

## Not included

`linkedin-hook-writer` remains unpublished until its redistribution rights are confirmed. The five specialist add-ons above are linked through install guides rather than copied wholesale.

## Contributing

A bundled skill should be focused, self-contained, license-cleared, and useful in a real workflow. It must include a unique `name`, a useful `description`, all required supporting files, and no credentials, caches, machine-specific paths, or nested Git repositories.

---

<div align="center">

Curated by [Toyo Ntewo](https://github.com/Toyontewo)

</div>
