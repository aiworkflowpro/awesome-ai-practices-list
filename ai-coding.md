# AI Coding & Agents — real-world best practices

> Working setups for coding agents, not hot takes

Auto-curated from X by [DigestOps](https://digestops.com/t/ai-coding) · updated 2026-07-04 04:26 UTC · 16 practices

## 2026-07-03

### [Design award-level website in 18 min with Claude Code + Sonnet 5](https://digestops.com/p/design-award-level-website-in-18-min-with-claude-code-88)
*by [@ClaudeCode_love](https://x.com/ClaudeCode_love) · 1300 likes · [source](https://x.com/ClaudeCode_love/status/2073008603796226267)*

- Claude Code with Sonnet 5 can produce a design award-level website in 18 minutes from scratch.
- The video demonstrates the full process from giving instructions to finishing the visual appearance.
- The approach is documented as 'HTML-first thinking' for achieving high-quality design.

## 2026-07-02

### [Built a high-quality brand site with glowing effects and depth in one evening using Claude Code.](https://digestops.com/p/built-a-high-quality-brand-site-with-glowing-effects-and-9)
*by [@monokern](https://x.com/monokern) · 1700 likes · [source](https://x.com/monokern/status/2072618245790580820)*

- Claude Code can generate a brand site with custom effects like glowing headlines and product breaking out of frame.
- The result matches quality of $5,000-$8,000 brand sites but costs only a Claude subscription.

## 2026-07-01

### [Set up Fable 5 as orchestrator with Opus and Sonnet subagents and Codex plugin in Claude Code.](https://digestops.com/p/set-up-fable-5-as-orchestrator-with-opus-and-sonnet-6)
*by [@diegocabezas01](https://x.com/diegocabezas01) · 4856 likes · [source](https://x.com/diegocabezas01/status/2072436501263339841)*

- Use Fable 5 with max reasoning as the main orchestrator model.
- Create two subagents: deep-reasoner pinned to Opus for complex reasoning, and fast-worker pinned to Sonnet for mechanical tasks.
- Install and add the OpenAI Codex plugin to Claude Code for peer review.

## 2026-06-30

### [Debugged year of crashes: found hardware issue and 18-year-old bug in open-source code](https://digestops.com/p/debugged-year-of-crashes-found-hardware-issue-and-18-year-39)
*by [@OpenAIDevs](https://x.com/OpenAIDevs) · 1018 likes · [source](https://x.com/OpenAIDevs/status/2071995642436800916)*

- Systematic debugging of data infrastructure crashes revealed one hardware issue.
- Another root cause was an unnoticed bug in open-source code for 18 years.
- The debugging process is detailed in the linked article.

### [Claude Code transforms with official setup plugin](https://digestops.com/p/claude-code-transforms-with-official-setup-plugin-72)
*by [@claudecode84](https://x.com/claudecode84) · 3569 likes · [source](https://x.com/claudecode84/status/2071888301909475338)*

- The 'claude-code-setup' plugin scans your project and suggests hooks, skills, MCP servers, sub-agents, and automations.
- It provides step-by-step setup guidance, not just suggestions.
- Install via: /plugin install claude-code-setup@claude-plugins-official

### [Automate your job with Claude Skills from Anthropic paper](https://digestops.com/p/automate-your-job-with-claude-skills-from-anthropic-paper-102)
*by [@polydao](https://x.com/polydao) · 2221 likes · [source](https://x.com/polydao/status/2071832672066830847)*

- Encode daily workflows into Claude as custom Skills.
- Package routines into automated folders for agent execution.
- Agent connects to local tools via MCP servers.

## 2026-06-29

### [Google's Agents CLI unifies agentic engineering workflow](https://digestops.com/p/google-s-agents-cli-unifies-agentic-engineering-workflow-73)
*by [@akshay_pachaar](https://x.com/akshay_pachaar) · 1824 likes · [source](https://x.com/akshay_pachaar/status/2071509401224261823)*

- Karpathy's agentic engineering skills (spec design, eval loops, security) are now tooled in one CLI.
- One setup command injects 7 ADK-specific skills into a coding agent's context.
- Covers scaffolding, evaluating, and deploying ADK agents without context switching.

## 2026-06-28

### [Automate Obsidian with Claude: Karpathy's method turns AI into full-time Zettelkasten maintainer](https://digestops.com/p/automate-obsidian-with-claude-karpathy-s-method-turns-ai-58)
*by [@polydao](https://x.com/polydao) · 1928 likes · [source](https://x.com/polydao/status/2071105441698910415)*

- LLM reads every new source and integrates it into a structured wiki.
- Obsidian becomes visual IDE while Claude operates as backend.
- Agent runs automated checks to find contradictions across notes.

## 2026-06-27

### [Karpathy's LLM Wiki structure cuts token costs up to 95% by avoiding full reloads](https://digestops.com/p/karpathy-s-llm-wiki-structure-cuts-token-costs-up-to-95-by-38)
*by [@ClaudeCode_UT](https://x.com/ClaudeCode_UT) · 1039 likes · [source](https://x.com/ClaudeCode_UT/status/2070764072736587823)*

- Most AI implementations reload the entire database from scratch on every query, causing high token costs.
- Karpathy's 'LLM Wiki' compiles data once and stores it in memory, eliminating repeated reloads.
- Designing Claude Code Skills and CLAUDE.md carefully already implements this structure.

## 2026-06-26

### [Japanese dev's YouTube automation succeeds using Claude Code 'Find Skills' skill](https://digestops.com/p/japanese-dev-s-youtube-automation-succeeds-using-claude-37)
*by [@angeldot_](https://x.com/angeldot_) · 1421 likes · [source](https://x.com/angeldot_/status/2070620788592369881)*

- Install the 'Find Skills' skill via npx skills add https://t.co/b9jDCteIzD --skill find-skills.
- Ask Claude Code: 'Is there a good skill for [YOUR GOAL]?' to automatically apply relevant skills.
- This method led to a successful automated YouTube system.

### [Built an AI second brain by connecting Claude Desktop to Obsidian vault using a prompt.](https://digestops.com/p/built-an-ai-second-brain-by-connecting-claude-desktop-to-7)
*by [@Av1dlive](https://x.com/Av1dlive) · 2365 likes · [source](https://x.com/Av1dlive/status/2070507527213871594)*

- Download and install Claude Desktop and Obsidian Desktop.
- Create a new Obsidian vault and add .md files.
- Use Andrej Karpathy's prompt to instruct Claude Code to connect to the vault.

## 2026-06-25

### [Spin up persistent cloud dev environment in one prompt with DigitalOcean Codex plugin](https://digestops.com/p/spin-up-persistent-cloud-dev-environment-in-one-prompt-with-74)
*by [@OpenAIDevs](https://x.com/OpenAIDevs) · 1007 likes · [source](https://x.com/OpenAIDevs/status/2070261549391024403)*

- One prompt creates a persistent cloud development environment via the DigitalOcean plugin for Codex.
- Environment runs in your DigitalOcean account and stays active when you step away.

## 2026-06-24

### [Delegate tasks to Cursor from Notion via Cursor SDK](https://digestops.com/p/delegate-tasks-to-cursor-from-notion-via-cursor-sdk-101)
*by [@cursor_ai](https://x.com/cursor_ai) · 2480 likes · [source](https://x.com/cursor_ai/status/2069872515548340407)*

- Cloud agents run on same models and runtime as Cursor.
- Assign tasks from Notion to open a PR for team review.

## 2026-06-23

### [One-click add popular plugins, skills, MCPs from team leaderboard](https://digestops.com/p/one-click-add-popular-plugins-skills-mcps-from-team-103)
*by [@cursor_ai](https://x.com/cursor_ai) · 1840 likes · [source](https://x.com/cursor_ai/status/2069512593887092811)*

- Cursor shows leaderboard of most popular plugins, skills, MCPs across team.
- Add any to your setup with one click from Customize page.

### [206-page Codex guide from zero to real projects](https://digestops.com/p/206-page-codex-guide-from-zero-to-real-projects-71)
*by [@bozhou_ai](https://x.com/bozhou_ai) · 4205 likes · [source](https://x.com/bozhou_ai/status/2069250352168493142)*

- Created a 206-page PDF covering Codex from installation to five hands-on projects including a pet snack website and admin dashboard.
- Includes a standard six-step workflow and reusable task templates for beginners.
- All content is in Chinese with screenshots, targeting newcomers.

## 2026-05-18

### [Integrated Open Design canvas into Codex for AI agents to design, code, and animate in one workflow.](https://digestops.com/p/integrated-open-design-canvas-into-codex-for-ai-agents-to-8)
*by [@OpenDesignHQ](https://x.com/OpenDesignHQ) · 2036 likes · [source](https://x.com/OpenDesignHQ/status/2056309544997818507)*

- Open Design now works inside Codex, allowing agents to use the canvas directly.
- The integration supports design-to-code-to-motion in a single workflow.
