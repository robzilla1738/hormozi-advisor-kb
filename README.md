# Hormozi Advisor Knowledge Base (unofficial)

> **Not endorsed by Alex Hormozi.** This is an unofficial, fan-made project with no affiliation to Alex Hormozi, Leila Hormozi, or Acquisition.com. All ideas belong to their original creators; every note links its source video.


An **unofficial, fan-made** distillation of **470 public Alex Hormozi YouTube videos** into decision playbooks with citations. It's built so you, or an AI bot, can make business decisions the way Hormozi teaches.

> Not affiliated with Alex Hormozi or Acquisition.com. All ideas belong to him. Every note links its source video. See [NOTICE.md](NOTICE.md).

## Layout

| Path | What it is |
|---|---|
| `INDEX.md` | Start here. A "which decision are you facing?" router, a stage router, the top 25 videos, and a catalog of all 470 notes rated by signal. |
| `decisions/01–13-*.md` | 13 decision files: what to start, offers, pricing, lead gen, sales, retention, hiring, ops and scaling, marketing, cash, deals and equity, mindset, quit or pivot. Each has rules with numbers, playbooks, anti-patterns, metrics, and cited videos. |
| `principles.md`, `playbooks.md`, `anti-patterns.md`, `quotes-and-formulas.md` | Ranked principles, step-by-step playbooks, mistakes to avoid, and formulas and quotes. |
| `notes/<videoId>.md` | One structured note per video: core thesis, frameworks, decision rules, playbook, mistakes, examples, notable lines. |
| `manifest.json` | Video id → title, URL, duration. |
| `build/findings.md` | One line per video: `id \| signal \| tags \| takeaway`. |
| `SKILL-hormozi-advisor.md`, `bot-system-prompt.md` | Instructions for an AI advisor bot. |

## Using it with a bot

```bash
git clone https://github.com/robzilla1738/hormozi-advisor-kb.git /workspace/hormozi
```

Then have the bot follow `SKILL-hormozi-advisor.md`, or use `bot-system-prompt.md` as its system prompt. Lookup order: INDEX → decisions → notes → (optionally) the video's captions.

## Trust notes

- Every claim cites the video id and URL.
- Synthesis, math, or reconciliation that isn't his words is marked `[inference]`.
- Segments featuring Leila Hormozi or guests are flagged.
- **Transcripts are not included** (copyright). Quotes are verified against each note's "Notable lines". To check wording further, pull captions from the linked video.
