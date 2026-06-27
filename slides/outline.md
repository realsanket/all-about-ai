# 🎤 Presentation Outline — "Modern AI Models & Essential Terminology"

> A ready-to-deck outline mapping this repository's content to slides. Designed for a **45–60 minute talk or workshop**, easily trimmed to a 20-minute lightning version (use ⚡-marked slides only).

**How to use this:** Each slide lists a title, talking points, and the source section. The Mermaid diagrams in the linked docs paste cleanly into most slide tools (or export as images). Tables become bullet builds or screenshots.

---

## Suggested flow (24 slides)

### Opening
1. ⚡ **Title** — "Modern AI Models & the Terminology You Need" + your name + date. *(Note: landscape as of June 2026.)*
2. ⚡ **Why this talk** — Models change weekly; you need a *mental model*, not memorized specs. → [Intro](../docs/01-introduction.md)
3. ⚡ **The 30-second summary** — Two camps, reasoning is standard, multimodal default, context exploded, gap narrowing, no single "best." → [README](../README.md#-the-30-second-summary)

### Part 1 — Foundations (terminology)
4. ⚡ **What is an AI model?** — Next-token prediction; the pattern-engine analogy + diagram. → [Intro 1.1](../docs/01-introduction.md#11-what-is-an-ai-model)
5. ⚡ **The 5 must-know terms** — Token, Context Window, Parameters, Training vs. Inference. → [Glossary](../docs/02-terminology.md)
6. **Grounding & action terms** — RAG, MCP, Tool Calling, Agents (with the agent loop diagram). → [Glossary](../docs/02-terminology.md#agents)
7. **Reliability & control terms** — Hallucination, Temperature, System Prompt, Fine-tuning, Quantization. → [Glossary](../docs/02-terminology.md)

### Part 2 — The landscape
8. ⚡ **The ecosystem mindmap** — One slide, the whole field. → [README mindmap](../README.md#-the-ecosystem-at-a-glance)
9. ⚡ **Proprietary vs. Open-Weight** — The big table; "open-weight ≠ open-source." → [Landscape 3.1](../docs/03-model-landscape.md#31-the-two-big-camps-proprietary-vs-open-weight)
10. **Capability vs. openness quadrant** — Where each model sits. → [Landscape quadrant](../docs/03-model-landscape.md#31-the-two-big-camps-proprietary-vs-open-weight)
11. **Categories by capability** — Reasoning, multimodal, long-context, coding, local. → [Landscape 3.2](../docs/03-model-landscape.md#32-categories-by-capability)
12. ⚡ **The trade-off triangle** — Capability vs. cost vs. speed vs. control. → [Landscape 3.3](../docs/03-model-landscape.md#33-the-core-trade-offs-the-you-cant-have-it-all-triangle)

### Part 3 — The models (comparisons)
13. ⚡ **Frontier flagships table** — GPT-5.5, Claude Opus 4.8, Gemini 3.x, Grok 4.3. → [Comparisons 4.1](../docs/04-model-comparisons.md#41-flagship-frontier-models-proprietary)
14. ⚡ **Open-weight flagships table** — Llama 4, DeepSeek V4, Qwen 3.x, Mistral, Nemotron. → [Comparisons 4.2](../docs/04-model-comparisons.md#42-flagship-open-weight-models)
15. **Small/local models** — Phi-4, Granite, Qwen-30B, Nemotron Nano. → [Comparisons 4.3](../docs/04-model-comparisons.md#43-small--local-models-laptop--single-gpu)
16. **Context window chart** — 128K → 10M visual. → [Comparisons 4.5](../docs/04-model-comparisons.md#45-context-window-comparison)
17. **Pricing reality** — The 36× spread; cost levers (caching, batch, routing). → [Comparisons 4.6](../docs/04-model-comparisons.md#46-pricing-snapshot-per-1m-tokens-usd)

### Part 4 — Choosing
18. ⚡ **The master decision tree** — Start with your hardest constraint. → [Decision 6.1](../docs/06-decision-guides.md#61-the-master-decision-tree)
19. ⚡ **Best model by use case** — Coding / reasoning / vision / long-ctx / local / enterprise / cost. → [Decision 6.2](../docs/06-decision-guides.md#62-best-model-by-use-case)
20. **Model routing** — Don't use one model; route by difficulty. → [Decision 6.3](../docs/06-decision-guides.md#63-model-routing-use-more-than-one)

### Part 5 — Depth & wrap-up
21. **How it really works in production** — RAG + MCP + memory + guardrails diagram. → [Concepts](../docs/09-concepts-deep-dive.md#putting-it-all-together-a-typical-2026-ai-application)
22. **Benchmarks: trust but verify** — The 4 caveats; build your own eval. → [Benchmarks](../docs/08-benchmarks.md)
23. **Where it's heading** — Reasoning ambient, open closing in, agents maturing, efficiency is the frontier. → [Timeline 7.4](../docs/07-timeline.md#74-where-the-trend-lines-point)
24. ⚡ **Key takeaways + Q&A** — (see below) + link to this repo.

---

## Closing takeaways slide (copy-paste ready)

> - 🧩 **There is no single "best" model** — only the best fit for *your* task, budget, and constraints.
> - 🔓 **Open-weight is catching up fast** — and is often the cheaper, more private choice.
> - 🧠 **Reasoning + agents + multimodal** are the defining capabilities of 2026.
> - 📏 **Context and benchmarks are ceilings, not guarantees** — always test on your own data.
> - 🔄 **Build to swap models** — re-evaluate every quarter.

---

## Lightning version (20 min)
Use only the ⚡ slides: **1, 2, 3, 4, 5, 8, 9, 12, 13, 14, 18, 19, 24.**

## Workshop add-ons (hands-on)
- **Glossary quiz** — match terms to definitions from [Glossary](../docs/02-terminology.md).
- **"Pick a model" exercise** — give teams 3 scenarios; use the [Decision Guides](../docs/06-decision-guides.md).
- **Run a local model** — install Ollama and run Phi-4 or Qwen-30B live. → [References 10.4](../docs/10-references.md#104-tools-for-running-models-locally)
- **Build a 20-example eval** — apply [Benchmarks 8.5](../docs/08-benchmarks.md#85-build-your-own-evaluation-the-part-that-actually-matters).

---

## Speaker notes & tips
- **Lead with the trade-off triangle** — it reframes "which is best?" into "best for what?"
- **Show, don't list** — diagrams and the decision tree land better than spec tables; put detailed tables in a handout (link this repo).
- **Date every spec slide** — say "as of June 2026" out loud; it builds credibility and ages gracefully.
- **End on the eval message** — the most useful thing an audience can take away is "test on your own data."
