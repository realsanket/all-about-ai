# Contributing

Thanks for helping keep **All About AI** accurate and useful! Because the model landscape changes weekly, corrections and fresh numbers are especially valuable.

## What we welcome

- 🔢 **Updated specs** — new context windows, pricing, licenses, or model versions.
- 🆕 **New models** — flagship releases from the providers we cover (or notable new providers).
- 🐛 **Corrections** — anything outdated, wrong, or unclear.
- 🎨 **Better visuals** — clearer diagrams, tables, or decision guides.
- 🌍 **Translations** and accessibility improvements.

## Ground rules

1. **Cite an official source.** Every factual change should link to the provider's docs, model card, or an official announcement. Add it to [docs/10-references.md](docs/10-references.md) if it's new.
2. **Date your claims.** This repo uses "as of <month year>" framing. Update the snapshot date when you revise a section.
3. **Stay beginner-friendly.** Favor plain language, analogies, tables, and diagrams over academic depth.
4. **Round sensibly.** Where vendors are vague, use approximate figures (`~`) rather than false precision.
5. **Keep it neutral.** Compare models on the merits; avoid hype and vendor marketing language.

## How to contribute

1. Fork the repo and create a branch (`fix/gemini-pricing`, `add/new-model-x`).
2. Make your change. Diagrams use [Mermaid](https://mermaid.js.org/) so they render on GitHub.
3. Verify Markdown tables and links render correctly (preview on GitHub).
4. Open a pull request describing **what changed and your source**.

## Style quick reference

- Pricing is per **1M tokens (USD)**, input/output, standard tier.
- Context windows in tokens (`K`/`M`).
- MoE models: cite **active / total** parameters.
- Use the existing emoji/section conventions for consistency.

Not sure about something? Open an issue and ask. 🙌
