# Frontier Models — real-world best practices

> What people actually build the week a new model drops

Auto-curated from X by [DigestOps](https://digestops.com/t/frontier-models) · updated 2026-07-04 04:26 UTC · 25 practices

## 2026-07-03

### [Saved tokens by letting Fable choose subagent model](https://digestops.com/p/saved-tokens-by-letting-fable-choose-subagent-model-84)
*by [@simonw](https://x.com/simonw) · 2511 likes · [source](https://x.com/simonw/status/2073117641020215566)*

- Instructing the model to use its own judgement to select a lower power model for coding tasks saves tokens.
- The approach delegates model selection to the agent, reducing overhead from always using the most powerful model.

### [Fable 5 prompt generates Grok videos matching seedance 2.5 quality at 6x lower cost](https://digestops.com/p/fable-5-prompt-generates-grok-videos-matching-seedance-2-5-99)
*by [@AYi_AInotes](https://x.com/AYi_AInotes) · 1333 likes · [source](https://x.com/AYi_AInotes/status/2073076344582234357)*

- Detailed prompt specifies character, location, visual style, camera aesthetic, and shot-by-shot timeline.
- Achieves documentary realism with DV camcorder aesthetic, handheld shake, auto-focus hunting, exposure fluctuations.
- Cost is 6x lower than seedance 2.5 for comparable output.

### [Manipulate objects in existing videos with Gemini Omni Flash text prompts](https://digestops.com/p/manipulate-objects-in-existing-videos-with-gemini-omni-87)
*by [@ComfyUI](https://x.com/ComfyUI) · 436 likes · [source](https://x.com/ComfyUI/status/2073059371723198725)*

- Gemini Omni Flash can modify objects and environments in existing videos using simple text prompts.
- Iteration and specific prompting may be needed to achieve desired results.
- The workflow is available for others to try.

### [Free Gemini 3.5 Flash with 1M context and 1500 requests/day](https://digestops.com/p/free-gemini-3-5-flash-with-1m-context-and-1500-requests-day-70)
*by [@CDGalpha](https://x.com/CDGalpha) · 1900 likes · [source](https://x.com/CDGalpha/status/2072928597573353947)*

- Gemini 3.5 Flash is free-tier eligible with no credit card required, offering 1M token context and 1500 requests/day.
- Setup takes 2 minutes: get a free API key from Google AI Studio, then point any OpenAI-compatible client (Cursor, Cline, Claude Code) at Gemini.
- Two models available: gemini-3.5-flash for strong performance, gemini-3.1-flash-lite for cheap high-volume calls.

## 2026-07-02

### [Automated YouTube workflow with Claude Code and find skills MCP](https://digestops.com/p/automated-youtube-workflow-with-claude-code-and-find-skills-86)
*by [@alextalksai](https://x.com/alextalksai) · 464 likes · [source](https://x.com/alextalksai/status/2072742391124009047)*

- Use 'find skills' MCP package to let Claude scan hundreds of Anthropic ecosystem skills and build the optimal workflow from a single prompt.
- The workflow includes script generation (Notion + Claude), b-roll selection (Veo 3), thumbnail (Sora), caption+scheduling (Buffer), and performance tracking (Typefully).
- One prompt triggers the entire content pipeline, requiring only the desired outcome as input.

### [Scrape sold homes, find shade-less patios, mail owners a pergola render](https://digestops.com/p/scrape-sold-homes-find-shade-less-patios-mail-owners-a-32)
*by [@everestchris6](https://x.com/everestchris6) · 5113 likes · [source](https://x.com/everestchris6/status/2072687270709309589)*

- Scrape every home sold in the metro in the last 12 months to target recent buyers.
- Use vision to skip 64% of homes that already have shade cover.
- Measure sun exposure per hour using Google satellite data and render a louvered pergola into the owner's actual backyard photo.

### [20-min video makes you a Claude Fable 5 expert with loop engineering and memory system](https://digestops.com/p/20-min-video-makes-you-a-claude-fable-5-expert-with-loop-100)
*by [@milesdeutscher](https://x.com/milesdeutscher) · 1194 likes · [source](https://x.com/milesdeutscher/status/2072570861761253871)*

- Covers loop engineering with demo, Fable 5 x Claude Skills, and 3 ways to build effective Skills.
- Includes building a local memory system for persistent context.
- Demonstrates visual capabilities and practical usage patterns.

## 2026-07-01

### [Atomic Chat compared four frontier models on a physics demo task, measuring token cost and output quality.](https://digestops.com/p/atomic-chat-compared-four-frontier-models-on-a-physics-demo-1)
*by [@atomic_chat_hq](https://x.com/atomic_chat_hq) · 5718 likes · [source](https://x.com/atomic_chat_hq/status/2072446067962978411)*

- Fable 5 produced the highest quality physics demos but cost 6x more than Opus 4.8.
- GPT 5.5 was closest to Fable 5 in quality and cheaper, while GLM 5.2 was cheapest but lower quality.
- The benchmark used three specific HTML5 canvas scenes: train derailment, car collision, and monster truck crushing cars.

### [NYC cityscape recreated in Blender via Fable 5 in 20 minutes](https://digestops.com/p/nyc-cityscape-recreated-in-blender-via-fable-5-in-20-minutes-36)
*by [@ashen_one](https://x.com/ashen_one) · 395 likes · [source](https://x.com/ashen_one/status/2072432580419281391)*

- Fable 5 fetched building data from public sources before constructing the 3D model.
- Entire build is up to scale, replicating New York City's cityscape.

### [Anthropic's official guide to prompting Fable 5 for autonomous work](https://digestops.com/p/anthropic-s-official-guide-to-prompting-fable-5-for-57)
*by [@kirillk_web3](https://x.com/kirillk_web3) · 1187 likes · [source](https://x.com/kirillk_web3/status/2072415570624983471)*

- Use /loop for autonomous multi-step tasks instead of step-by-step commands.
- Add a memory file so Fable 5 learns from past runs.
- Spin up 50+ subagents for complex tasks; treat Fable 5 as a consultant, not a chatbot.

### [A trader used Claude Fable 5 to improve a Polymarket bot that achieved 531.8% ROI over 42 days.](https://digestops.com/p/a-trader-used-claude-fable-5-to-improve-a-polymarket-bot-5)
*by [@robrtcode](https://x.com/robrtcode) · 1274 likes · [source](https://x.com/robrtcode/status/2072389666871890002)*

- The bot executed ~30 trades per hour on short-term Bitcoin 'Up/Down' markets, averaging $6,878 daily profit.
- Strategy: wait for short-term pricing to deviate from fair value, enter before board rebalances, and repeat at scale.

## 2026-06-30

### [Atomic Chat benchmarked Claude Sonnet 5 against Opus 4.8 and GPT 5.5 on HTML5 canvas physics demos, finding Sonnet 5 competitive at lower cost.](https://digestops.com/p/atomic-chat-benchmarked-claude-sonnet-5-against-opus-4-8-3)
*by [@atomic_chat_hq](https://x.com/atomic_chat_hq) · 1629 likes · [source](https://x.com/atomic_chat_hq/status/2072099564870349267)*

- Claude Sonnet 5 used 15,047 tokens ($0.15) for three physics crash demos, outperforming Opus 4.8 (23,063 tokens, $0.58) and GPT 5.5 (31,152 tokens, $0.94).
- Sonnet 5 matched or beat Opus 4.8 and GPT 5.5 in wrecking ball and catapult tests, but had weaker detail and graphics.

### [Sonnet 5 built landing page in 2m 11s at $3.36 vs Opus 4.8 at $20.66](https://digestops.com/p/sonnet-5-built-landing-page-in-2m-11s-at-3-36-vs-opus-4-8-33)
*by [@markksantos](https://x.com/markksantos) · 924 likes · [source](https://x.com/markksantos/status/2072026366967738833)*

- Sonnet 5 used 20.9k input and 14.2k output tokens, costing $3.36 and taking 2m 11s.
- Opus 4.8 used 96.3k input and 73.8k output tokens, costing $20.66 and taking 20m 15s.
- Opus 4.8 produced higher quality output, but Sonnet 5 was faster and cheaper.

### [GeneBench-Pro benchmark for agents navigating messy biological data](https://digestops.com/p/genebench-pro-benchmark-for-agents-navigating-messy-54)
*by [@OpenAI](https://x.com/OpenAI) · 4426 likes · [source](https://x.com/OpenAI/status/2072004836674167294)*

- Introduced GeneBench-Pro, a research-level benchmark for evaluating agents on biological data analysis.
- Benchmark tests agents' ability to navigate messy data, choose analysis paths, and make judgment calls.

### [40 AI marketing agents for $500/month replacing $50k human team](https://digestops.com/p/40-ai-marketing-agents-for-500-month-replacing-50k-human-69)
*by [@Zephyr_hg](https://x.com/Zephyr_hg) · 2255 likes · [source](https://x.com/Zephyr_hg/status/2071996301311381827)*

- Built a team of 40 AI marketing agents operating under one human.
- AI bill is $500 per month versus $50,000 for a human team.
- One person can run the entire marketing function alone with the right setup.

### [4-second text-to-image at $0.034 per image with nano banana 2 lite](https://digestops.com/p/4-second-text-to-image-at-0-034-per-image-with-nano-banana-55)
*by [@GoogleAIStudio](https://x.com/GoogleAIStudio) · 2761 likes · [source](https://x.com/GoogleAIStudio/status/2071989578672595413)*

- nano banana 2 lite generates 1K-resolution images in 4 seconds
- Cost is $0.034 per image, making it suitable for high-velocity pipelines
- Available via AI Studio and Gemini API for easy integration

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

## 2026-06-26

### [14-hour portable AI workstation from strapping battery to Mac Mini](https://digestops.com/p/14-hour-portable-ai-workstation-from-strapping-battery-to-56)
*by [@gippp69](https://x.com/gippp69) · 2723 likes · [source](https://x.com/gippp69/status/2070581743929672037)*

- Attached a battery to a Mac Mini to create a portable workstation with 14-hour runtime.
- Replaces cloud rental costs by running local AI tasks like transcription and summarization.
- Setup enables running Claude-connected automation from a backpack.

### [22x cheaper bug fixing with GLM 5.2 vs Claude Opus 4.8](https://digestops.com/p/22x-cheaper-bug-fixing-with-glm-5-2-vs-claude-opus-4-8-85)
*by [@gmi_cloud](https://x.com/gmi_cloud) · 907 likes · [source](https://x.com/gmi_cloud/status/2070317987299741957)*

- GLM 5.2 used 17k–38k fewer tokens than Opus 4.8 for bug fixing tasks.
- GLM 5.2 cost 15x to 22x less than Opus 4.8 in two tests.
- Opus 4.8 finished a few seconds faster but at much higher cost.

## 2026-06-24

### [AI animation ad generator turns product photos into 3D explainer videos in 4-12 min](https://digestops.com/p/ai-animation-ad-generator-turns-product-photos-into-3d-98)
*by [@Mho_23](https://x.com/Mho_23) · 1371 likes · [source](https://x.com/Mho_23/status/2069838139171250629)*

- System analyzes brand, pitches 4 ad concepts with hooks and shot lists, then renders end-to-end.
- Replaces $200+ per video editor workflow; each 30s ad costs under $1 in API fees.
- Uses Gemini Omni, GPT Images 2, and Claude Code for scripting, rendering, and stitching.

### [First AI chip Jalapeño built from ground up with Broadcom for LLM workloads](https://digestops.com/p/first-ai-chip-jalape-o-built-from-ground-up-with-broadcom-53)
*by [@OpenAI](https://x.com/OpenAI) · 22753 likes · [source](https://x.com/OpenAI/status/2069770172802773292)*

- Designed and built a custom AI chip named Jalapeño in collaboration with Broadcom.
- Chip is purpose-built for LLM workloads powering ChatGPT, Codex, API, and future agentic products.
- Building own chip expands full-stack platform from products to models to infrastructure.

## 2026-06-22

### [73.7 SWE-Bench Pro from Fugu Ultra routing multiple frontier models](https://digestops.com/p/73-7-swe-bench-pro-from-fugu-ultra-routing-multiple-97)
*by [@VaibhavSisinty](https://x.com/VaibhavSisinty) · 3667 likes · [source](https://x.com/VaibhavSisinty/status/2068923914299068553)*

- Sakana Fugu is a coordinator that routes API calls to the best frontier model for each subproblem.
- Fugu Ultra scores 73.7 on SWE-Bench Pro, beating Claude Opus 4.8 (69.2) and GPT-5.5 (58.6).
- The model pool is swappable, allowing routing around export-controlled providers.

## 2026-06-18

### [Anthropic tested Claude Opus 4.7 programming a robodog, achieving 20x speed improvement over human team with Opus 4.1.](https://digestops.com/p/anthropic-tested-claude-opus-4-7-programming-a-robodog-2)
*by [@AnthropicAI](https://x.com/AnthropicAI) · 2284 likes · [source](https://x.com/AnthropicAI/status/2067651699486200091)*

- Claude Opus 4.7 autonomously programmed a robodog ~20x faster than the best human team aided by Opus 4.1.
- The robodog still failed to fetch a beach ball, indicating limitations in physical task completion.

## 2026-05-29

### [Min Choi demonstrated Claude Code's dynamic workflow feature that spawns subagents and verifies results.](https://digestops.com/p/min-choi-demonstrated-claude-code-s-dynamic-workflow-4)
*by [@minchoi](https://x.com/minchoi) · 1496 likes · [source](https://x.com/minchoi/status/2060226858994565563)*

- Set /model to opus 4.8 and /effort to 'ultracode' to enable dynamic workflow.
- Use 'workflow' in the prompt to have Claude write an orchestration script, spawn subagents, verify results, and report back.
