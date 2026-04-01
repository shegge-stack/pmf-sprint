# PMF Sprint

A Claude Code plugin that runs an adaptive product-market fit validation sprint. Adapts to your stage — whether you have 0 customers or 100.

Inspired by three publicly available frameworks:
- **Foundation Sprint & Design Sprint** by Jake Knapp & John Zeratsky (Character Capital)
- **PMF Engine** by Rahul Vohra (Superhuman), building on the **Sean Ellis Test**

## Install

```
/plugin install shegge-stack/pmf-sprint
```

## Usage

```
/pmf-sprint:pmf-sprint
```

## How it works

The sprint starts with a quick triage to determine your track:

| Track | You have | Sprint takes | Focus |
|-------|----------|--------------|-------|
| **Explorer** | 0 customers | ~60 min | Everything is a hypothesis. Validate the problem. |
| **Validator-Explore** | 1-10 customers, unclear ICP | ~60 min | Early customers are clues, not conclusions. Compare markets. |
| **Validator-Narrow** | 1-10 customers, clear pattern | ~45 min | Anchor to real customers. Find more like them. |
| **Optimizer** | 10+ customers | ~30 min | Measure, segment, narrow. |

Then guides you through adaptive phases — questions, coaching, and output adapt to your stage:

1. **The Basics** — Customer, problem, advantage, competition
2. **Market Comparison** (Validator-Explore only) — Score candidate segments before committing
3. **Differentiation** — Scale ratings, 2x2 positioning, decision principles
4. **Founding Hypothesis** — One-sentence bet + scorecard
5. **PMF Measurement** — Leading indicators / Vohra questions / Sean Ellis survey (by track)
6. **Next Actions** — Concrete tasks for this week
7. **Save Artifacts** — Exports positioning report, market comparison, and sprint doc

## Disclaimer

This tool is an independent synthesis inspired by publicly available frameworks. It is **not affiliated with, endorsed by, or officially connected to** Jake Knapp, John Zeratsky, Character Capital, Rahul Vohra, Superhuman, or Sean Ellis.

The underlying strategic frameworks (Foundation Sprint, Design Sprint, PMF Engine, Sean Ellis Test) belong to their respective creators and are publicly taught methodologies intended for broad use. The adaptive triage system, market comparison framework, HTML report generation, and conversational coaching format are original to this plugin.
