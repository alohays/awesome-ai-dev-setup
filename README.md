# Awesome AI Dev Setup [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![Link Check](https://github.com/alohays/awesome-ai-dev-setup/actions/workflows/link-check.yml/badge.svg)

> A curated list of tools, templates, and configs for AI-assisted development.

## Contents

- [Agent-Native Templates](#agent-native-templates)
- [Agent Config and Rules Sharing](#agent-config-and-rules-sharing)
- [MCP Servers & Integrations](#mcp-servers--integrations)
- [AI-Enhanced Terminals & Shells](#ai-enhanced-terminals--shells)
- [Code Review & Security](#code-review--security)
- [Testing & QA](#testing--qa)
- [Documentation](#documentation)
- [Dotfiles & Environment Setup](#dotfiles--environment-setup)
- [CLI Scaffolding Patterns](#cli-scaffolding-patterns)

## Agent-Native Templates

Repos designed to be used with AI coding agents.

### Platforms and Standards

- [agentsmd/agents.md](https://github.com/agentsmd/agents.md) - Open standard defining how coding agents should read project instructions.
- [vercel-labs/coding-agent-template](https://github.com/vercel-labs/coding-agent-template) - Multi-agent AI coding platform combining Vercel Sandbox and AI Gateway.
- [vercel-labs/knowledge-agent-template](https://github.com/vercel-labs/knowledge-agent-template) - File-system and knowledge-base agent template for retrieval-augmented workflows.
- [openai/openai-agents-python](https://github.com/openai/openai-agents-python) - OpenAI's Python SDK for building multi-agent systems with handoffs, guardrails, and tracing.
- [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for building LLM-powered agents and plugins in Python, C#, and Java.

### Claude Code Templates

- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) - CLI tool for configuring and monitoring Claude Code with ready-made project templates.
- [ChrisWiles/claude-code-showcase](https://github.com/ChrisWiles/claude-code-showcase) - Comprehensive example project configuration for Claude Code.
- [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) - CLAUDE.md memory bank system and opinionated starter template.
- [danielrosehill/Claude-Code-Repos-Index](https://github.com/danielrosehill/Claude-Code-Repos-Index) - Categorized index of Claude Code related repos and starter templates.
- [abhishekray07/claude-md-templates](https://github.com/abhishekray07/claude-md-templates) - CLAUDE.md best practices and module-specific guidance for common project types.
- [serpro69/claude-starter-kit](https://github.com/serpro69/claude-starter-kit) - Starter template bundling MCP servers, skills, hooks, and task orchestration configs.

### Other Agent Templates

- [mastra-ai/template-coding-agent](https://github.com/mastra-ai/template-coding-agent) - TypeScript coding agent with sandboxed E2B code execution environment.
- [run-llama/create_llama](https://github.com/run-llama/create_llama) - CLI bootstrapper for LlamaIndex-powered agent applications in TypeScript and Python.
- [gptscript-ai/gptscript](https://github.com/gptscript-ai/gptscript) - Natural language scripting language for composing AI agents and automated workflows.
- [microsoft/autogen](https://github.com/microsoft/autogen) - Microsoft Research's framework for building multi-agent conversational systems.
- [agno-agi/agno](https://github.com/agno-agi/agno) - Lightweight framework for building multi-modal agents with memory, knowledge, and tools.

## Agent Config and Rules Sharing

### Multi-Agent Orchestration

- [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) - Agent harness with hooks, MCPs, and workflows supporting 75+ models and 40+ lifecycle hooks.
- [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) - Teams-first multi-agent orchestration for Claude Code with 30+ agents and 37 skills.
- [Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex) - Multi-agent orchestration for OpenAI Codex CLI with 40+ execution modes.
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) - Role-based multi-agent framework for coordinating specialized AI agent teams.
- [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open-source AI software development agent platform with multi-agent task support.

### Skills and Plugins Collections

- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) - Curated skills list with 500+ connected app integrations.
- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - 100+ specialized Claude Code subagents for targeted development tasks.
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) - Cross-platform skills for Claude, Codex, Gemini CLI, and Cursor.
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) - 86 production-ready Claude Code skill packages.
- [levnikolaevich/claude-code-skills](https://github.com/levnikolaevich/claude-code-skills) - 109 skills covering the full Agile lifecycle from research through quality gates.

### Curated Collections and Toolkits

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - Community-curated skills, hooks, slash-commands, agents, and plugins for Claude Code.
- [GitHub/awesome-copilot](https://github.com/github/awesome-copilot) - Official GitHub community instructions, prompts, and configurations for Copilot.
- [rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit) - 135 agents, 35 skills, 42 commands, 120 plugins, and 19 hooks bundled together.
- [josix/awesome-claude-md](https://github.com/josix/awesome-claude-md) - Curated exemplary CLAUDE.md files with analyses and best practices.
- [anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) - Official Anthropic code samples and patterns for building with Claude APIs and agents.

### Cursor Rules

- [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) - Large collection of .cursorrules configuration files for the Cursor AI editor.
- [sanjeed5/awesome-cursor-rules-mdc](https://github.com/sanjeed5/awesome-cursor-rules-mdc) - 879+ .mdc rule files for Cursor agent mode across many tech stacks.
- [continuedev/awesome-rules](https://github.com/continuedev/awesome-rules) - Cross-platform rules for coding assistants using the amplified.dev standard.
- [pontusab/cursor.directory](https://github.com/pontusab/cursor.directory) - Community platform and open-source repo for discovering and sharing Cursor rules by framework.
- [eastlondoner/cursor-tools](https://github.com/eastlondoner/cursor-tools) - CLI giving Cursor Agent browser automation, web research, and cross-agent workflow capabilities.

### Cross-Platform Tools

- [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) - Reference guide and examples for all 12 Claude Code lifecycle hook events.
- [lbb00/ai-rules-sync](https://github.com/lbb00/ai-rules-sync) - Sync AI rules across Cursor, Claude, Copilot, Codex, Gemini, and more from one source.
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) - Official GitHub Action for running Claude Code in CI workflows and PR automation.
- [kortix-ai/suna](https://github.com/kortix-ai/suna) - Open-source generalist AI agent with browser, file, terminal, and external API access.
- [continuedev/continue](https://github.com/continuedev/continue) - Open-source AI code assistant for VS Code and JetBrains that connects to any LLM.

## MCP Servers & Integrations

The [Model Context Protocol](https://modelcontextprotocol.io) (MCP) is an open standard for connecting AI agents to external tools, APIs, and data sources.

### Reference Implementations

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) - Official reference MCP servers: filesystem, GitHub, Slack, PostgreSQL, Google Drive, and more.
- [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) - Official TypeScript SDK for building and connecting to MCP servers.
- [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK for implementing MCP servers and clients.

### Server Development Frameworks

- [jlowin/fastmcp](https://github.com/jlowin/fastmcp) - High-level Python framework for building MCP servers with minimal boilerplate.
- [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) - Open-source library for connecting any LLM to MCP servers without a dedicated MCP client.

### Curated Directories

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - Actively maintained catalog of community and official MCP servers by category.
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) - Community-driven MCP server directory with categorized and searchable listings.

## AI-Enhanced Terminals & Shells

### AI Coding Agents in the Terminal

- [aider-chat/aider](https://github.com/aider-chat/aider) - AI pair programmer that edits files in your local git repo from the terminal, supporting any LLM.
- [anthropics/claude-code](https://github.com/anthropics/claude-code) - Anthropic's terminal-native AI coding agent with deep file system and shell access.
- [openai/codex](https://github.com/openai/codex) - OpenAI's CLI coding agent for terminal-based AI-assisted software development.

### AI Shell Tools

- [BuilderIO/ai-shell](https://github.com/BuilderIO/ai-shell) - CLI that converts natural language descriptions into runnable shell commands.
- [sigoden/aichat](https://github.com/sigoden/aichat) - All-in-one AI CLI supporting chat, shell assistance, and RAG over local files and docs.
- [charmbracelet/mods](https://github.com/charmbracelet/mods) - AI on the command line, designed to compose cleanly with Unix pipes and shell scripts.

## Code Review & Security

Research shows approximately one-third of AI-generated code contains security vulnerabilities, making automated review and static analysis a critical layer in AI-assisted development workflows.

### AI Code Review

- [Codium-ai/pr-agent](https://github.com/Codium-ai/pr-agent) - AI-powered automated PR analysis, inline code review, and improvement suggestions.
- [sturdy-dev/codereview.gpt](https://github.com/sturdy-dev/codereview.gpt) - Reviews GitHub pull requests using large language models via the CLI.

### AI-Generated Code Security

- [NVIDIA/garak](https://github.com/NVIDIA/garak) - LLM vulnerability scanner and red-teaming toolkit for probing model weaknesses and failure modes.
- [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) - Meta's open toolkit for evaluating and hardening the security of LLM applications.
- [Bearer/bearer](https://github.com/Bearer/bearer) - Code security scanner detecting sensitive data flows and OWASP Top 10 vulnerabilities in source code.
- [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) - SAST tool for detecting hardcoded secrets and leaked credentials across git history.
- [returntocorp/semgrep](https://github.com/returntocorp/semgrep) - Fast, customizable static analysis with AI-assisted rule generation across many languages.

## Testing & QA

### AI Test Generation

- [Codium-ai/cover-agent](https://github.com/Codium-ai/cover-agent) - AI-powered CLI that generates tests targeting uncovered code paths to maximize coverage.

### LLM Evaluation Frameworks

- [confident-ai/deepeval](https://github.com/confident-ai/deepeval) - LLM testing framework with 14+ built-in evaluation metrics and native CI/CD integration.
- [microsoft/promptflow](https://github.com/microsoft/promptflow) - End-to-end framework for building, evaluating, and deploying high-quality LLM applications.

### Agent Observability & Testing

- [AgentOps-AI/agentops](https://github.com/AgentOps-AI/agentops) - Observability, testing, cost tracking, and session replay for AI agents.
- [traceloop/openllmetry](https://github.com/traceloop/openllmetry) - OpenTelemetry-based observability SDK for tracing LLM calls and agent execution.

## Documentation

### AI Documentation Generation

- [eli64s/readme-ai](https://github.com/eli64s/readme-ai) - AI README generator that analyzes codebase structure to produce comprehensive project docs.
- [context-labs/autodoc](https://github.com/context-labs/autodoc) - Auto-generates and indexes codebase documentation using LLMs, queryable from the CLI.
- [Nutlope/aicommits](https://github.com/Nutlope/aicommits) - Generates conventional Git commit messages from staged changes using AI.

### Codebase Understanding & Onboarding

- [sourcegraph/cody](https://github.com/sourcegraph/cody) - AI coding assistant with deep codebase indexing, semantic search, and contextual explanation.
- [sweepai/sweep](https://github.com/sweepai/sweep) - AI developer agent that reads your codebase to autonomously resolve GitHub issues.

## Dotfiles & Environment Setup

### AI Dev Dotfiles Collections

- [mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles) - Sensible macOS defaults and shell configuration widely used as a base for AI-enhanced dev setups.
- [nicknisi/dotfiles](https://github.com/nicknisi/dotfiles) - Neovim, tmux, and zsh configuration with solid tooling integration for AI-assisted development.
- [webpro-nl/dotfiles](https://github.com/webpro-nl/dotfiles) - Modular dotfiles with automated installation and cross-platform support for macOS and Linux.

### Automated Dev Environment Setup

- [thoughtbot/laptop](https://github.com/thoughtbot/laptop) - Shell script for bootstrapping a macOS development environment from a clean install.
- [anishathalye/dotbot](https://github.com/anishathalye/dotbot) - Declarative dotfiles bootstrapper that makes setup scripts reproducible and portable across machines.
- [twpayne/chezmoi](https://github.com/twpayne/chezmoi) - Manage dotfiles across multiple machines with templates, secret encryption, and version control.

## CLI Scaffolding Patterns

Generator and scaffolding patterns that inform AI-assisted project bootstrapping. These tools demonstrate UX conventions—interactive prompts, plugin extensibility, template evolution—that AI coding agents reference when generating and scaffolding new projects.

### Modern Scaffolding Frameworks

- [Vercel/turborepo](https://github.com/vercel/turborepo) - Zero-config TypeScript generators using an existing workspace as a live template.
- [t3-oss/create-t3-app](https://github.com/t3-oss/create-t3-app) - Interactive step-by-step prompts with modular, opt-in stack selection.
- [nrwl/nx](https://github.com/nrwl/nx) - Plugin-based generators with custom workspace generators written in TypeScript.
- [oclif/oclif](https://github.com/oclif/oclif) - Lifecycle hooks and auto-generated help used by major CLIs including Salesforce and Heroku.
- [scaffoldog/scaffdog](https://github.com/scaffoldog/scaffdog) - Markdown-driven file scaffolding with Handlebars templates that are easy for AI agents to read and modify.

### Micro-Generators

- [plopjs/plop](https://github.com/plopjs/plop) - Action-based code generation with add, modify, and append operations for enforcing project consistency.
- [jondot/hygen](https://github.com/jondot/hygen) - Generators that live inside your project, versioned and co-located with source code.
- [copier-org/copier](https://github.com/copier-org/copier) - Template evolution tool that updates downstream projects when the upstream template improves.
- [infinitered/gluegun](https://github.com/infinitered/gluegun) - Toolkit for building CLIs with generators, template rendering, and file patching.
- [jakubplichta/grafana-dashboard-builder](https://github.com/jakubplichta/grafana-dashboard-builder) - YAML-to-JSON dashboard generation illustrating declarative, domain-specific generator patterns.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
