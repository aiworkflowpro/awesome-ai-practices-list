# AI Coding & Agents — real-world best practices

> Working setups for coding agents, not hot takes

Auto-curated from X by [DigestOps](https://digestops.com/t/ai-coding) · updated 2026-07-03 10:12 UTC · 7 practices

## 2026-07-02

### [Built a high-quality brand site with glowing effects and depth in one evening using Claude Code.](https://digestops.com/p/built-a-high-quality-brand-site-with-glowing-effects-and-9)
*by [@monokern](https://x.com/monokern) · 1552 likes · [source](https://x.com/monokern/status/2072618245790580820)*

- Claude Code can generate a brand site with custom effects like glowing headlines and product breaking out of frame.
- The result matches quality of $5,000-$8,000 brand sites but costs only a Claude subscription.

## 2026-07-01

### [Set up Fable 5 as orchestrator with Opus and Sonnet subagents and Codex plugin in Claude Code.](https://digestops.com/p/set-up-fable-5-as-orchestrator-with-opus-and-sonnet-6)
*by [@diegocabezas01](https://x.com/diegocabezas01) · 4606 likes · [source](https://x.com/diegocabezas01/status/2072436501263339841)*

- Use Fable 5 with max reasoning as the main orchestrator model.
- Create two subagents: deep-reasoner pinned to Opus for complex reasoning, and fast-worker pinned to Sonnet for mechanical tasks.
- Install and add the OpenAI Codex plugin to Claude Code for peer review.

## 2026-06-30

### [Debugged year of crashes: found hardware issue and 18-year-old bug in open-source code](https://digestops.com/p/debugged-year-of-crashes-found-hardware-issue-and-18-year-39)
*by [@OpenAIDevs](https://x.com/OpenAIDevs) · 1018 likes · [source](https://x.com/OpenAIDevs/status/2071995642436800916)*

- Systematic debugging of data infrastructure crashes revealed one hardware issue.
- Another root cause was an unnoticed bug in open-source code for 18 years.
- The debugging process is detailed in the linked article.

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
*by [@Av1dlive](https://x.com/Av1dlive) · 2356 likes · [source](https://x.com/Av1dlive/status/2070507527213871594)*

- Download and install Claude Desktop and Obsidian Desktop.
- Create a new Obsidian vault and add .md files.
- Use Andrej Karpathy's prompt to instruct Claude Code to connect to the vault.

## 2026-05-18

### [Integrated Open Design canvas into Codex for AI agents to design, code, and animate in one workflow.](https://digestops.com/p/integrated-open-design-canvas-into-codex-for-ai-agents-to-8)
*by [@OpenDesignHQ](https://x.com/OpenDesignHQ) · 2036 likes · [source](https://x.com/OpenDesignHQ/status/2056309544997818507)*

- Open Design now works inside Codex, allowing agents to use the canvas directly.
- The integration supports design-to-code-to-motion in a single workflow.
