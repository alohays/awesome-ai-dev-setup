# Contributing to awesome-ai-dev-setup

Thank you for helping expand this list!

## Adding an Entry

1. Fork this repository
2. Add your entry to the appropriate section in `README.md`
3. Follow the list format: `- [org/repo](url) - One-line description ending with a period.`
4. Keep descriptions concise (under 100 characters)
5. Submit a pull request

## Guidelines

- Projects should be publicly available on GitHub (or similar)
- Place entries in alphabetical order within their section
- One project per row
- All text must be in English

## What Belongs Here

- Templates designed for AI coding agents (Claude Code, Cursor, Copilot, Codex, Gemini CLI, etc.)
- Collections of agent rules, skills, hooks, or configurations
- CLI scaffolding tools with patterns worth learning from
- Cross-platform agent configuration tools

## What Doesn't Belong

- General AI/ML libraries (too broad)
- Closed-source tools without public repos
- Self-promotion without substance

## Quality Criteria

All submissions are evaluated against our [Quality Criteria](/docs/QUALITY_CRITERIA.md). Key requirements:

- Repository must be at least 30 days old
- At least 1 commit in the past 12 months
- Must have a README with installation and usage instructions
- Must have a license file
- Must be relevant to AI-assisted development
- Must not be a fork without significant original work

New submissions are automatically validated by our CI pipeline, which checks repository metadata via the GitHub API.

## Entry Removal

Entries may be removed if they no longer meet quality standards. See the [removal policy](/docs/QUALITY_CRITERIA.md#removal--deprecation-policy) for details.

## Review Process

- All PRs are automatically validated against quality criteria
- Maintainers review submissions against the full checklist
- Quarterly reviews ensure all entries remain up to date

## Automated Link Health Monitoring

This repository uses automated workflows to maintain link quality.

### Link Checker (Weekly)

A [lychee-based](https://github.com/lycheeverse/lychee-action) link checker runs every Sunday to detect broken links in README.md and CONTRIBUTING.md. When broken links are found, an issue is automatically created with the `link-rot` label.

- **Configuration**: See `.lychee.toml` for timeout, retry, and exclusion settings
- **Manual trigger**: Go to Actions > Link Check > Run workflow
- **Excluded domains**: `img.shields.io` (badge SVGs) are excluded to avoid false positives

### Project Health Check (Monthly)

A monthly workflow checks each listed repository via the GitHub API:

- **Archived**: Repository has been archived by its owner
- **Stale**: No commits in the past 12 months
- **Not Found**: Repository has been deleted or renamed

When issues are detected, a health report is created as a GitHub issue with `link-rot` and `health-check` labels.

### What to Do When Links Break

1. Verify the link is truly broken (not a temporary outage)
2. Search for the project's new URL if it was moved
3. If the project is archived but still useful, add a note to its description
4. If the project is deleted with no replacement, remove the entry
5. Submit a PR with your fixes
