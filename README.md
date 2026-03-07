# awesome-ai-dev-setup

A curated list of tools, templates, and configs for AI-assisted development.

> This list is maintained by the [monitor-forge](https://github.com/alohays/monitor-forge) team.
> We built it while researching how to make the best agent-native dashboard framework.
> If you're building tools for AI coding agents — or using them — this is for you.

## Contents

- [Agent-Native Templates](#agent-native-templates)
- [Agent Config & Rules Sharing](#agent-config--rules-sharing)
- [CLI Scaffolding Patterns](#cli-scaffolding-patterns)
- [Key Takeaways for monitor-forge](#key-takeaways-for-monitor-forge)

---

## Agent-Native Templates

Repos designed to be used WITH AI coding agents.

### Platforms & Standards

| Project | Stars | Description |
|---------|-------|-------------|
| [agentsmd/agents.md](https://github.com/agentsmd/agents.md) | 18.6K | Open standard for guiding coding agents — a README for agents |
| [vercel-labs/coding-agent-template](https://github.com/vercel-labs/coding-agent-template) | 1.6K | Multi-agent AI coding platform with Vercel Sandbox and AI Gateway |
| [vercel-labs/knowledge-agent-template](https://github.com/vercel-labs/knowledge-agent-template) | 563 | File-system and knowledge-based agent template |

### Claude Code Templates

| Project | Stars | Description |
|---------|-------|-------------|
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | 22.3K | CLI tool for configuring and monitoring Claude Code with templates |
| [ChrisWiles/claude-code-showcase](https://github.com/ChrisWiles/claude-code-showcase) | 5.5K | Comprehensive Claude Code project configuration example (hooks, skills, agents, workflows) |
| [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) | 1.9K | CLAUDE.md memory bank system and starter template |
| [danielrosehill/Claude-Code-Repos-Index](https://github.com/danielrosehill/Claude-Code-Repos-Index) | 110 | Categorized index of Claude Code related repos and starter templates |
| [abhishekray07/claude-md-templates](https://github.com/abhishekray07/claude-md-templates) | 70 | CLAUDE.md best practices and module-specific guidance |
| [serpro69/claude-starter-kit](https://github.com/serpro69/claude-starter-kit) | 62 | Starter template with MCP servers, skills, hooks, and task orchestration |

### Other Agent Templates

| Project | Stars | Description |
|---------|-------|-------------|
| [mastra-ai/template-coding-agent](https://github.com/mastra-ai/template-coding-agent) | 36 | TypeScript coding agent with E2B sandbox execution |

---

## Agent Config & Rules Sharing

### Multi-Agent Orchestration

| Project | Stars | Description |
|---------|-------|-------------|
| [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) | 37.7K | Agent harness with hooks, MCPs, and workflows — 75+ model support, 40+ lifecycle hooks |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | 8.7K | Teams-first multi-agent orchestration for Claude Code — 30+ agents, 37 skills, magic keywords |
| [Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex) | 1.5K | Multi-agent orchestration for OpenAI Codex CLI — 40+ execution modes, tmux-based workers |

### Skills & Plugins Collections

| Project | Stars | Description |
|---------|-------|-------------|
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 41.5K | Curated skills list with 500+ connected apps |
| [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 12.8K | 100+ specialized Claude Code subagents |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 9.8K | Cross-platform skills for Claude, Codex, Gemini CLI, and Cursor |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | 2.6K | 86 production-ready Claude Code skill packages |
| [levnikolaevich/claude-code-skills](https://github.com/levnikolaevich/claude-code-skills) | 165 | 109 skills covering full Agile lifecycle (research through quality gates) |

### Curated Collections & Toolkits

| Project | Stars | Description |
|---------|-------|-------------|
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | 26.7K | Skills, hooks, slash-commands, agents, and plugins for Claude Code |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | 24K | Official GitHub community instructions, prompts, and configurations |
| [rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit) | 648 | 135 agents, 35 skills, 42 commands, 120 plugins, 19 hooks |
| [josix/awesome-claude-md](https://github.com/josix/awesome-claude-md) | 143 | Curated exemplary CLAUDE.md files with analyses and best practices |

### Cursor Rules

| Project | Stars | Description |
|---------|-------|-------------|
| [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) | 38.3K | .cursorrules configuration files for Cursor AI editor |
| [sanjeed5/awesome-cursor-rules-mdc](https://github.com/sanjeed5/awesome-cursor-rules-mdc) | 3.4K | 879+ .mdc files for Cursor agent mode |
| [continuedev/awesome-rules](https://github.com/continuedev/awesome-rules) | 138 | Cross-platform rules for coding assistants (amplified.dev standard) |

### Cross-Platform Tools

| Project | Stars | Description |
|---------|-------|-------------|
| [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) | 3.2K | Master guide for 12 Claude Code lifecycle hook events |
| [lbb00/ai-rules-sync](https://github.com/lbb00/ai-rules-sync) | 15 | Sync AI rules across Cursor, Claude, Copilot, Codex, Gemini, and more |

---

## CLI Scaffolding Patterns

Tools with UX and architecture patterns worth learning from.

### Modern Scaffolding Frameworks

| Project | Stars | Key Pattern |
|---------|-------|-------------|
| [vercel/turborepo](https://github.com/vercel/turborepo) | 30K | "Use existing workspace as template" — zero-config TypeScript generators |
| [t3-oss/create-t3-app](https://github.com/t3-oss/create-t3-app) | 28.6K | Interactive step-by-step prompts with modular optionality — "yours to own" |
| [nrwl/nx](https://github.com/nrwl/nx) | 28.3K | Plugin-based generators — custom workspace generators in TypeScript |
| [oclif/oclif](https://github.com/oclif/oclif) | 9.4K | Lifecycle hooks and auto-generated help — used by Salesforce/Heroku CLI |

### Micro-Generators

| Project | Stars | Key Pattern |
|---------|-------|-------------|
| [plopjs/plop](https://github.com/plopjs/plop) | 7.6K | Action-based generation (add, modify, append) — consistency made simple |
| [jondot/hygen](https://github.com/jondot/hygen) | 6K | Generators live in your project — versioned and co-located |
| [copier-org/copier](https://github.com/copier-org/copier) | 3.2K | Template evolution — update projects when templates improve |

### Dashboard-Specific

| Project | Stars | Key Pattern |
|---------|-------|-------------|
| [jakubplichta/grafana-dashboard-builder](https://github.com/jakubplichta/grafana-dashboard-builder) | 159 | YAML-to-JSON dashboard generation — dashboard-as-code |

---

## Key Takeaways for monitor-forge

What we learned from this survey and how it shapes [monitor-forge](https://github.com/alohays/monitor-forge):

1. **Dual-format agent support is rare.** monitor-forge supports both CLAUDE.md and AGENTS.md. Few projects do this — it's a genuine differentiator for multi-agent workflows (Claude Code + Copilot + Cursor).

2. **Config-driven generation is validated.** create-t3-app, Turborepo, and grafana-dashboard-builder all prove that config files driving code generation is a winning pattern. monitor-forge's single `monitor-forge.config.json` follows this.

3. **CLI-first + agent-ready is the sweet spot.** The `--format json` flag pattern lets both humans and agents consume the same CLI. Most templates are human-only or agent-only — monitor-forge does both.

4. **Skills as modular capabilities.** SKILL.md packages with progressive disclosure are becoming a standard across Claude Code, Codex, and Gemini CLI. monitor-forge ships with 5 built-in skills.

5. **Cross-platform rule sync is emerging.** Tools like ai-rules-sync show demand for supporting multiple agents. monitor-forge already works with any AGENTS.md-compatible agent.

---

## Contributing

Found a project that belongs here? [Open an issue](https://github.com/alohays/awesome-ai-dev-setup/issues/new) or submit a PR.

Entry format: `| [org/repo](url) | stars | one-line description |`

---

Star counts last updated: March 2026
