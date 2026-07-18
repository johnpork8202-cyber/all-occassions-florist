# AI / Anthropic / platform news digest

Living digest so Claude knows events past its training cutoff (Jan 2026).
Newest entries at the top. Append dated sections; never delete old ones.
Maintained by a daily scheduled routine + manual updates during sessions.

---

## 2026-07-17 — Initial seed

### Claude 5 family: Fable 5 & Mythos 5
- **June 9, 2026**: Anthropic released **Claude Fable 5**, the first model in a new "Mythos-class" tier that sits *above* the Opus line — its most capable generally available model, state-of-the-art on nearly all tested benchmarks (software engineering, knowledge work, vision, scientific research). ([Anthropic announcement](https://www.anthropic.com/news/claude-fable-5-mythos-5), [CNBC](https://www.cnbc.com/2026/06/09/anthropic-mythos-claude-fable-5.html))
- **Claude Mythos 5** is the same underlying model with safeguards lifted in some areas, available only to approved orgs (cyberdefenders, infrastructure providers) initially via **Project Glasswing** with the US government; strongest cybersecurity capabilities of any model. Fable 5 = the safe-for-general-use version.
- Pricing: **$10 / M input tokens, $50 / M output** — less than half the price of Claude Mythos Preview.
- **June 12**: US government applied export controls to Fable 5 / Mythos 5 shortly after launch. **June 30**: controls lifted; Fable 5 available globally from July 1. ([CNBC](https://www.cnbc.com/2026/06/30/anthropic-says-trump-admin-has-lifted-export-controls-on-claude-fable-5-and-mythos-5.html), [Al Jazeera](https://www.aljazeera.com/economy/2026/7/1/us-lifts-restrictions-on-powerful-ai-models-fable-mythos-anthropic-says), [Anthropic: "Redeploying Claude Fable 5"](https://www.anthropic.com/news/redeploying-fable-5))
- **Claude Sonnet 5** is now the default model for Pro, Team Standard, and Enterprise seats — top-tier coding/tool use at Sonnet pricing, native 1M-token context window, adaptive thinking on by default. ([Releasebot](https://releasebot.io/updates/anthropic/claude))

### Usage limits / token resets ("the reset this week")
- **July 16, 2026**: Anthropic refilled Claude's 5-hour and weekly usage buckets for users; same day, OpenAI Codex users got a quota top-up and Cursor doubled included usage on paid plans — industry-wide retention gestures, not permanent upgrades. ([ExplainX](https://www.explainx.ai/blog/claude-codex-cursor-usage-limits-reset-july-2026))
- **July 10, 2026**: earlier full reset of Claude Code's 5-hour + weekly limits for all users, after a rough stretch of outages. ([Startup Fortune](https://startupfortune.com/anthropic-resets-claude-code-usage-limits-again-after-a-rough-week-of-outages/))
- Background: May 6 — 5-hour limits permanently doubled for Pro/Max/Team/Enterprise, peak-hour throttling removed; the +50% weekly-limit promotion has been extended to **July 19**. ([Help Net Security](https://www.helpnetsecurity.com/2026/07/13/claude-code-weekly-limits-promotion-extended/), [TECHSY](https://techsy.io/en/blog/claude-2x-usage-limits-explained))

### Dario Amodei (recent appearances)
- **July 15, 2026**: Council on Foreign Relations CEO Speaker Series — US AI leadership, strategic competition, frontier outlook; explained Anthropic's Responsible Scaling Policy as analogous to biosafety levels (currently ASL-2-equivalent framing in that talk). ([CFR event](https://www.cfr.org/event/ceo-speaker-series-dario-amodei-anthropic))
- **June 17, 2026**: Bloomberg video profile "Inside the Mind of Anthropic CEO Dario Amodei". ([Bloomberg](https://www.bloomberg.com/news/videos/2026-06-17/inside-the-mind-of-anthropic-ceo-dario-amodei-video))
- 2026 Dwarkesh Patel podcast appearance (widely discussed, e.g. [Zvi's writeup](https://thezvi.substack.com/p/on-dwarkesh-patels-2026-podcast-with)); also a CBS interview on the **Pentagon feud** ([CBS News](https://www.cbsnews.com/video/full-interview-anthropic-ceo-dario-amodei-pentagon-feud/)).

### Claude Code / Cowork
- **July 7, 2026**: **Claude Cowork expanded to mobile and web** — sessions/files follow you across devices; background work, scheduled tasks, shared projects, mobile approvals. ([TechCrunch](https://techcrunch.com/2026/07/07/the-coding-agent-wars-are-spilling-into-the-rest-of-the-office-claude-cowork/))
- Recent Claude Code releases: screen reader mode, vim insert remaps, mouse support, smarter `/doctor`, background sessions for `/fork`, improved `/resume`/`/background`, hardened WebSearch/subagent/Bash safeguards. ([Releasebot](https://releasebot.io/updates/anthropic/claude-code), [What's new](https://code.claude.com/docs/en/whats-new))
- Controversy: Claude Code's "hidden tracker" was called an "experiment" by Anthropic. ([Malwarebytes](https://www.malwarebytes.com/blog/news/2026/07/claude-codes-hidden-tracker-was-an-experiment-says-anthropic))
