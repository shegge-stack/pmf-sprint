# PMF Sprint

A Claude Code plugin that runs an adaptive product-market fit validation sprint. Adapts to your stage — whether you have 0 customers or 100.

Combines three frameworks:
- **Foundation Sprint** (Jake Knapp & John Zeratsky)
- **Design Sprint** (Knapp & Zeratsky)
- **Vohra PMF Engine** (Rahul Vohra, Superhuman)

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
| **Validator** | 1-10 customers | ~45 min | Anchor to real customers. Find more like them. |
| **Optimizer** | 10+ customers | ~30 min | Measure, segment, narrow. |

Then guides you through 6 phases — questions, coaching, and output adapt to your stage:

1. **The Basics** — Customer, problem, advantage, competition
2. **Differentiation** — Scale ratings, 2x2 positioning, decision principles
3. **Founding Hypothesis** — One-sentence bet + scorecard
4. **PMF Measurement** — Leading indicators / Vohra questions / Sean Ellis survey (by track)
5. **Next Actions** — Concrete tasks for this week
6. **Save Artifact** — Exports a PMF Sprint doc you update over time
