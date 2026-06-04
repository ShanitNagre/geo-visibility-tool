# GEO Visibility Analyzer

A working mini-app that simulates how your brand shows up in AI-generated search answers — and where competitors are beating you.

Built as a hands-on exploration of **GEO (Generative Engine Optimization)** and **AEO (Answer Engine Optimization)** — the emerging discipline of optimizing brand presence in AI search results from tools like ChatGPT, Perplexity, and Google AI Overviews.

> 🔗 **Live demo:** [shanitnagre.github.io/geo-visibility-tool](https://shanitnagre.github.io/geo-visibility-tool)

---

## What it does

- Takes your brand, competitors, industry, and buyer persona as inputs
- Simulates **5 real B2B research queries** that your target buyers would ask an AI assistant
- Scores each brand's **AI answer presence (0–100)** per query
- Shows a **query-level bar chart breakdown** with competitive context
- Provides an **executive summary** of your brand's AI visibility vs competitors
- Surfaces **3 specific, actionable GEO recommendations** tailored to your brand

---

## Why this matters

89% of B2B buyers now use AI for research. If your brand isn't surfacing in those AI-generated answers, you're invisible at the top of the funnel — before a buyer ever visits your website.

Traditional SEO optimizes for search engine rankings. GEO optimizes for *AI answer presence* — a fundamentally different challenge that requires:

- Citation earning (getting referenced by authoritative sources)
- Content freshness signals for LLM training data
- Structured, answer-friendly content formats
- Reddit and community engagement for organic AI citations
- Brand entity clarity across the web

---

## Tech stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML/CSS/JS — zero dependencies, single file |
| AI engine | Anthropic Claude API (`claude-sonnet-4-20250514`) |
| Icons | Tabler Icons |
| Hosting | GitHub Pages |

The entire app is a **single `index.html` file** — no build step, no framework, no backend.

---

## How to run locally

```bash
git clone https://github.com/shanitnagre/geo-visibility-tool.git
cd geo-visibility-tool
open index.html
```

> The app calls the Anthropic API directly from the browser. To run locally, you'll need to inject your own API key into the `fetch` headers in `index.html`.

---

## Product context

This tool was built to demonstrate a working understanding of the GEO/AEO problem space — specifically the core value proposition of platforms like [Writesonic](https://writesonic.com): tracking brand AI search visibility, identifying competitive gaps, and executing content fixes to improve presence in AI-generated answers.

The scoring model in this prototype simulates AI answer presence using an LLM-as-judge approach — a lightweight proxy for what a production system would derive from real query sampling across ChatGPT, Perplexity, Gemini, and similar engines.

---

## About

Built by **Shanit Nagre** — AI Product Manager with experience shipping LLM pipelines, NLP systems, and agentic workflows in production.

- Portfolio: [shanitnagre.github.io](https://shanitnagre.github.io)
- LinkedIn: [linkedin.com/in/shanit-nagre-b1060917b](https://www.linkedin.com/in/shanit-nagre-b1060917b/)
