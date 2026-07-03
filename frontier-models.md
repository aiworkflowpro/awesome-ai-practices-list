# Frontier Models — real-world best practices

> What people actually build the week a new model drops

Auto-curated from X by [DigestOps](https://digestops.com/t/frontier-models) · updated 2026-07-03 10:12 UTC · 10 practices

## 2026-07-02

### [Scrape sold homes, find shade-less patios, mail owners a pergola render](https://digestops.com/p/scrape-sold-homes-find-shade-less-patios-mail-owners-a-32)
*by [@everestchris6](https://x.com/everestchris6) · 3894 likes · [source](https://x.com/everestchris6/status/2072687270709309589)*

- Scrape every home sold in the metro in the last 12 months to target recent buyers.
- Use vision to skip 64% of homes that already have shade cover.
- Measure sun exposure per hour using Google satellite data and render a louvered pergola into the owner's actual backyard photo.

## 2026-07-01

### [Atomic Chat compared four frontier models on a physics demo task, measuring token cost and output quality.](https://digestops.com/p/atomic-chat-compared-four-frontier-models-on-a-physics-demo-1)
*by [@atomic_chat_hq](https://x.com/atomic_chat_hq) · 5698 likes · [source](https://x.com/atomic_chat_hq/status/2072446067962978411)*

- Fable 5 produced the highest quality physics demos but cost 6x more than Opus 4.8.
- GPT 5.5 was closest to Fable 5 in quality and cheaper, while GLM 5.2 was cheapest but lower quality.
- The benchmark used three specific HTML5 canvas scenes: train derailment, car collision, and monster truck crushing cars.

### [NYC cityscape recreated in Blender via Fable 5 in 20 minutes](https://digestops.com/p/nyc-cityscape-recreated-in-blender-via-fable-5-in-20-minutes-36)
*by [@ashen_one](https://x.com/ashen_one) · 393 likes · [source](https://x.com/ashen_one/status/2072432580419281391)*

- Fable 5 fetched building data from public sources before constructing the 3D model.
- Entire build is up to scale, replicating New York City's cityscape.

### [A trader used Claude Fable 5 to improve a Polymarket bot that achieved 531.8% ROI over 42 days.](https://digestops.com/p/a-trader-used-claude-fable-5-to-improve-a-polymarket-bot-5)
*by [@robrtcode](https://x.com/robrtcode) · 1119 likes · [source](https://x.com/robrtcode/status/2072389666871890002)*

- The bot executed ~30 trades per hour on short-term Bitcoin 'Up/Down' markets, averaging $6,878 daily profit.
- Strategy: wait for short-term pricing to deviate from fair value, enter before board rebalances, and repeat at scale.

## 2026-06-30

### [Atomic Chat benchmarked Claude Sonnet 5 against Opus 4.8 and GPT 5.5 on HTML5 canvas physics demos, finding Sonnet 5 competitive at lower cost.](https://digestops.com/p/atomic-chat-benchmarked-claude-sonnet-5-against-opus-4-8-3)
*by [@atomic_chat_hq](https://x.com/atomic_chat_hq) · 1629 likes · [source](https://x.com/atomic_chat_hq/status/2072099564870349267)*

- Claude Sonnet 5 used 15,047 tokens ($0.15) for three physics crash demos, outperforming Opus 4.8 (23,063 tokens, $0.58) and GPT 5.5 (31,152 tokens, $0.94).
- Sonnet 5 matched or beat Opus 4.8 and GPT 5.5 in wrecking ball and catapult tests, but had weaker detail and graphics.

### [Sonnet 5 built landing page in 2m 11s at $3.36 vs Opus 4.8 at $20.66](https://digestops.com/p/sonnet-5-built-landing-page-in-2m-11s-at-3-36-vs-opus-4-8-33)
*by [@markksantos](https://x.com/markksantos) · 923 likes · [source](https://x.com/markksantos/status/2072026366967738833)*

- Sonnet 5 used 20.9k input and 14.2k output tokens, costing $3.36 and taking 2m 11s.
- Opus 4.8 used 96.3k input and 73.8k output tokens, costing $20.66 and taking 20m 15s.
- Opus 4.8 produced higher quality output, but Sonnet 5 was faster and cheaper.

### [50 static ad concepts daily via Claude Code skill](https://digestops.com/p/50-static-ad-concepts-daily-via-claude-code-skill-35)
*by [@mikefutia](https://x.com/mikefutia) · 539 likes · [source](https://x.com/mikefutia/status/2071748670442381666)*

- Skill studies customer reviews, winning ads, and top comments to generate concepts in brand voice.
- Outputs 50 fresh static ad concepts every morning, ready for media buyers needing 30+ concepts weekly.
- Automates mining of customer language for hooks, angles, and pain points.

## 2026-06-27

### [$24,542/month from 2 AI girls built with Claude](https://digestops.com/p/24-542-month-from-2-ai-girls-built-with-claude-34)
*by [@Bober_smart](https://x.com/Bober_smart) · 651 likes · [source](https://x.com/Bober_smart/status/2070950267822969169)*

- Created Fanvue account with $9.99 subscription for AI girl, gained 1,265 subscribers in a month.
- Used Claude to analyze male preferences and generate photos/videos autonomously with timer posting.
- Streamed AI girl on TikTok, YouTube, and Kick with real-time appearance and voice changes via Claude.

## 2026-06-18

### [Anthropic tested Claude Opus 4.7 programming a robodog, achieving 20x speed improvement over human team with Opus 4.1.](https://digestops.com/p/anthropic-tested-claude-opus-4-7-programming-a-robodog-2)
*by [@AnthropicAI](https://x.com/AnthropicAI) · 2283 likes · [source](https://x.com/AnthropicAI/status/2067651699486200091)*

- Claude Opus 4.7 autonomously programmed a robodog ~20x faster than the best human team aided by Opus 4.1.
- The robodog still failed to fetch a beach ball, indicating limitations in physical task completion.

## 2026-05-29

### [Min Choi demonstrated Claude Code's dynamic workflow feature that spawns subagents and verifies results.](https://digestops.com/p/min-choi-demonstrated-claude-code-s-dynamic-workflow-4)
*by [@minchoi](https://x.com/minchoi) · 1496 likes · [source](https://x.com/minchoi/status/2060226858994565563)*

- Set /model to opus 4.8 and /effort to 'ultracode' to enable dynamic workflow.
- Use 'workflow' in the prompt to have Claude write an orchestration script, spawn subagents, verify results, and report back.
