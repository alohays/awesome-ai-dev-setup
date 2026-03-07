# Awesome AI Dev Setup [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, templates, and configs for developers using or building AI coding agents.

Maintained by the [monitor-forge](https://github.com/monitor-forge) team. **Contributions welcome!** See the [contribution guidelines](CONTRIBUTING.md) and [code of conduct](code-of-conduct.md).

## Contents

- [Agent-Native Templates](#agent-native-templates)
- [Agent Config and Rules Sharing](#agent-config-and-rules-sharing)
- [CLI Scaffolding Patterns](#cli-scaffolding-patterns)
- [Related Lists](#related-lists)

## Agent-Native Templates

Ready-made project scaffolds that give AI coding agents the context, structure, and tooling they need to work effectively. Start here if you want to build or migrate a project for agent-first development.

### Platforms and Standards

- [agentsmd/agents.md](https://github.com/agentsmd/agents.md) - Open standard for guiding coding agents.
- [vercel-labs/coding-agent-template](https://github.com/vercel-labs/coding-agent-template) - Multi-agent AI coding platform with Vercel Sandbox and AI Gateway.
- [vercel-labs/knowledge-agent-template](https://github.com/vercel-labs/knowledge-agent-template) - File-system and knowledge-based agent template.

### Claude Code Templates

- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) - CLI tool for configuring and monitoring Claude Code with templates.
- [ChrisWiles/claude-code-showcase](https://github.com/ChrisWiles/claude-code-showcase) - Comprehensive Claude Code project configuration example.
- [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) - CLAUDE.md memory bank system and starter template.
- [danielrosehill/Claude-Code-Repos-Index](https://github.com/danielrosehill/Claude-Code-Repos-Index) - Categorized index of Claude Code related repos and starter templates.
- [abhishekray07/claude-md-templates](https://github.com/abhishekray07/claude-md-templates) - CLAUDE.md best practices and module-specific guidance.
- [serpro69/claude-starter-kit](https://github.com/serpro69/claude-starter-kit) - Starter template with MCP servers, skills, hooks, and task orchestration.

### Other Agent Templates

- [mastra-ai/template-coding-agent](https://github.com/mastra-ai/template-coding-agent) - TypeScript coding agent with E2B sandbox execution.

## Agent Config and Rules Sharing

Shared configurations, rules, and skills that define how your AI agent should work across projects and teams. Compose these building blocks to enforce consistent workflows, coding standards, and tool integrations without repeating yourself.

### Multi-Agent Orchestration

- [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) - Agent harness with hooks, MCPs, and workflows supporting 75+ models and 40+ lifecycle hooks.
- [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) - Teams-first multi-agent orchestration for Claude Code with 30+ agents and 37 skills.
- [Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex) - Multi-agent orchestration for OpenAI Codex CLI with 40+ execution modes.

### Skills and Plugins Collections

- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) - Curated skills list with 500+ connected apps.
- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - 100+ specialized Claude Code subagents.
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) - Cross-platform skills for Claude, Codex, Gemini CLI, and Cursor.
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) - 86 production-ready Claude Code skill packages.
- [levnikolaevich/claude-code-skills](https://github.com/levnikolaevich/claude-code-skills) - 109 skills covering the full Agile lifecycle from research through quality gates.

### Curated Collections and Toolkits

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - Skills, hooks, slash-commands, agents, and plugins for Claude Code.
- [GitHub/awesome-copilot](https://github.com/github/awesome-copilot) - Official GitHub community instructions, prompts, and configurations.
- [rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit) - 135 agents, 35 skills, 42 commands, 120 plugins, and 19 hooks.
- [josix/awesome-claude-md](https://github.com/josix/awesome-claude-md) - Curated exemplary CLAUDE.md files with analyses and best practices.

### Cursor Rules

- [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) - Collection of .cursorrules configuration files for Cursor AI editor.
- [sanjeed5/awesome-cursor-rules-mdc](https://github.com/sanjeed5/awesome-cursor-rules-mdc) - 879+ .mdc files for Cursor agent mode.
- [continuedev/awesome-rules](https://github.com/continuedev/awesome-rules) - Cross-platform rules for coding assistants using the amplified.dev standard.

### Cross-Platform Tools

- [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) - Master guide for 12 Claude Code lifecycle hook events.
- [lbb00/ai-rules-sync](https://github.com/lbb00/ai-rules-sync) - Sync AI rules across Cursor, Claude, Copilot, Codex, Gemini, and more.

## CLI Scaffolding Patterns

Well-designed CLI tools whose architecture and UX patterns are worth studying when building AI-driven scaffolding or developer tooling. Each entry demonstrates a different approach to interactivity, extensibility, or template management.

### Modern Scaffolding Frameworks

- [Vercel/turborepo](https://github.com/vercel/turborepo) - Zero-config TypeScript generators using existing workspace as template.
- [t3-oss/create-t3-app](https://github.com/t3-oss/create-t3-app) - Interactive step-by-step prompts with modular optionality.
- [nrwl/nx](https://github.com/nrwl/nx) - Plugin-based generators with custom workspace generators in TypeScript.
- [oclif/oclif](https://github.com/oclif/oclif) - Lifecycle hooks and auto-generated help used by Salesforce and Heroku CLI.

### Micro-Generators

- [plopjs/plop](https://github.com/plopjs/plop) - Action-based generation with add, modify, and append for consistency.
- [jondot/hygen](https://github.com/jondot/hygen) - Generators that live in your project, versioned and co-located.
- [copier-org/copier](https://github.com/copier-org/copier) - Template evolution that updates projects when templates improve.

### Dashboard-Specific

- [jakubplichta/grafana-dashboard-builder](https://github.com/jakubplichta/grafana-dashboard-builder) - YAML-to-JSON dashboard generation for dashboard-as-code.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

---

## Related Lists

- [awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) - A curated list of .cursorrules files for the Cursor AI editor; a proven success case in the AI agent tooling space.
- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - A list of Free Software network services and web applications which can be hosted on your own server.
- [awesome-react](https://github.com/enaqx/awesome-react) - A collection of awesome things regarding the React ecosystem, notable for its clear contribution policies and category structure.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=alohays/awesome-ai-dev-setup&type=Date)](https://star-history.com/#alohays/awesome-ai-dev-setup&Date)

---

[Back to Top](#awesome-ai-dev-setup)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the [monitor-forge](https://github.com/monitor-forge) team has waived all copyright and related or neighboring rights to this work.
