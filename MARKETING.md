# Community Marketing & Promotion Strategy

This document outlines the promotion strategy for [awesome-ai-dev-setup](https://github.com/alohays/awesome-ai-dev-setup). The goal is to grow community awareness and GitHub stars by providing genuine value — not by spamming.

---

## Core Principle

> GitHub star count correlates with community awareness, not content volume. Focus on reaching the right people in the right communities with the right message.

---

## 1. Reddit

Engage authentically. Lead with value — share insights, answer questions, and mention the project naturally when relevant. Never post the same message across subreddits.

### Target Subreddits

| Subreddit | Audience | Tone & Angle |
|---|---|---|
| [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) | Claude Code users | Highlight Claude-specific configs, CLAUDE.md templates, skills collections |
| [r/cursor](https://www.reddit.com/r/cursor/) | Cursor users | Focus on `.cursorrules`, Cursor config patterns, productivity setups |
| [r/CodingWithAI](https://www.reddit.com/r/CodingWithAI/) | General AI coding | Broad overview — templates, agent configs, scaffolding tools |
| [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) | Local AI enthusiasts | Emphasize open-source tools and self-hosted agent setups |
| [r/programming](https://www.reddit.com/r/programming/) | General developers | Frame as "how the ecosystem looks" — insightful, not promotional |

### Post Guidelines

- **Do:** Answer questions first, then mention the resource if relevant.
- **Do:** Write unique posts per subreddit with tailored framing.
- **Do:** Engage in comments after posting — reply to questions.
- **Don't:** Cross-post identical content.
- **Don't:** Open with "Check out my repo."

### Sample Post Frames

- r/ClaudeAI: *"I've been collecting the most useful CLAUDE.md setups and agent skill repos — here's what I found"*
- r/cursor: *"Curated list of Cursor config patterns and community setups that changed how I code"*
- r/LocalLLaMA: *"Awesome list of open-source AI dev setup resources — templates, configs, agent orchestration"*

---

## 2. Hacker News

### Show HN Post

**Title:** `Show HN: Awesome AI Dev Setup – curated tools, templates, and configs for AI coding agents`

**Body outline:**
- What it is: a curated list of tools for AI-assisted development
- Why it exists: the ecosystem moves fast and good setups are scattered across GitHub
- What's included: agent templates, CLAUDE.md configs, MCP servers, CLI scaffolding
- Invite: contributions and feedback welcome

### Timing

- **Optimal window:** Tuesday–Thursday, 8–10 AM US Eastern Time
- **Korea equivalent:** Tuesday–Thursday, 10 PM–midnight KST
- Monitor the thread actively for the first 2 hours; respond to every comment

### Tips

- Keep the HN post factual and humble — HN users dislike marketing language.
- Mention what makes the curation opinionated (quality criteria, not just a link dump).
- Link to [QUALITY_CRITERIA.md](docs/QUALITY_CRITERIA.md) to show rigor.

---

## 3. Twitter / X

### Strategy

- Post when a significant update lands (new category, milestone stars, notable addition).
- Tag maintainers of newly added projects — this often earns a retweet and drives their followers.
- Keep posts concise and specific; avoid vague hype.

### Target Accounts to Tag

| Account | Relevance |
|---|---|
| @AnthropicAI | Claude Code ecosystem |
| @cursor_ai | Cursor editor community |
| @github | General developer audience |
| Maintainers of listed projects | Natural engagement, likely retweet |

### Sample Tweets

```
Just added [ProjectName] to awesome-ai-dev-setup — a curated list of
templates and configs for AI coding agents.

If you're building with Claude Code or Cursor, this might save you hours.

→ https://github.com/alohays/awesome-ai-dev-setup

@maintainerhandle
```

```
awesome-ai-dev-setup just crossed [N] stars.

Here are the 3 most-starred categories:
1. Claude Code templates
2. MCP server collections
3. Agent orchestration setups

Full list → https://github.com/alohays/awesome-ai-dev-setup
```

### Do's and Don'ts

- **Do:** Tag only maintainers of projects you actually added.
- **Do:** Use specific numbers and names — "5 new tools" beats "new update."
- **Don't:** Mass-tag unrelated accounts.
- **Don't:** Ask for follows or stars directly.

---

## 4. Korean Developer Communities

### Platforms

| Platform | Notes |
|---|---|
| [GeekNews](https://news.hada.io) | Submit as a link post; write a Korean-language summary in the description |
| [Disquiet](https://disquiet.io) | Product maker community; frame as a "maker story" — why this list was built |
| Developer Discord / Kakao channels | Share in `#resources` or `#tools` channels; ask community admins first |

### GeekNews Submission Template

- **Title:** `Awesome AI Dev Setup — AI 코딩 에이전트를 위한 도구, 템플릿, 설정 모음`
- **Description (Korean):** 핵심 내용을 3–4문장으로 요약. Claude Code, Cursor, MCP 서버 등의 설정 예시와 커뮤니티 기여 방법 언급.

### Disquiet Post Frame

Write a maker story: "Why I built this list and what I learned about the AI coding ecosystem."

---

## 5. Blog & Content

### Articles to Write

1. **"Why I curated awesome-ai-dev-setup"**
   - Platforms: [DEV.to](https://dev.to), [Hashnode](https://hashnode.com)
   - Cover: the problem (scattered ecosystem), the curation process, quality criteria
   - End with: how to contribute

2. **"The best CLAUDE.md setups I found on GitHub"**
   - More specific, higher search value
   - Link back to the list naturally

3. **"AI coding agent setup: what the community is actually using"**
   - Data-driven angle: star counts, categories, trends

### Content Tips

- Write articles first, publish to DEV.to/Hashnode, then share links to Reddit and HN.
- Canonical URL should always point to the GitHub repo.
- Articles drive long-tail discovery (search engines index them).

---

## 6. Project Maintainer Outreach

When a project is added to this list, notify its maintainer. This creates goodwill and often leads to natural promotion.

### Outreach Template (GitHub Issue or Discussion)

```
Title: Your project is featured in awesome-ai-dev-setup

Hi @maintainer,

I wanted to let you know that [project-name] has been added to
awesome-ai-dev-setup — a curated list of tools, templates, and configs
for AI-assisted development.

https://github.com/alohays/awesome-ai-dev-setup

Thanks for building such a useful resource. Feel free to add a
"Featured in awesome-ai-dev-setup" badge to your README if you'd like:

[![Featured in awesome-ai-dev-setup](https://img.shields.io/badge/featured%20in-awesome--ai--dev--setup-blue)](https://github.com/alohays/awesome-ai-dev-setup)

Contributions and feedback are always welcome.
```

### Badge Markdown

```markdown
[![Featured in awesome-ai-dev-setup](https://img.shields.io/badge/featured%20in-awesome--ai--dev--setup-blue)](https://github.com/alohays/awesome-ai-dev-setup)
```

### Guidelines

- Open an Issue (not a PR) on the target repo — less intrusive.
- One message per project; do not follow up.
- Keep it short and appreciative — not a request, just a notification.

---

## 7. Monthly Update Routine

Consistency signals an active project. Run this checklist every month.

### Monthly Checklist

- [ ] Run the automated link checker (see `.github/workflows/link-check.yml`)
- [ ] Remove or mark archived projects
- [ ] Add at least 2–3 new tools discovered in the past month
- [ ] Review open Issues and PRs
- [ ] Post a brief update tweet: "Monthly update: N new tools added to awesome-ai-dev-setup"
- [ ] Submit notable updates to GeekNews or relevant subreddits if the update is significant

### Signals to Watch

- GitHub Trending (AI, developer-tools categories)
- r/ClaudeAI, r/cursor new posts mentioning tools or configs
- Hacker News "Ask HN" threads about AI coding setups
- Twitter searches for "claude code setup", "cursor rules", "mcp server"

---

## Summary

| Channel | Priority | Effort | Expected Impact |
|---|---|---|---|
| Reddit (r/ClaudeAI, r/CodingWithAI) | High | Medium | High — direct audience match |
| Hacker News Show HN | High | Low | High — broad reach, persistent |
| Maintainer outreach | High | Low | Medium — organic amplification |
| Twitter/X | Medium | Low | Medium — dependent on engagement |
| Blog articles (DEV.to) | Medium | High | Medium — long-tail search value |
| GeekNews (Korean) | Medium | Low | Medium — niche but relevant |
| Disquiet | Low | Medium | Low — awareness building |

---

*Last updated: 2026-03-08*
