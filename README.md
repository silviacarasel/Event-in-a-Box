# 📦 Event-in-a-Box

An AI event planning agent that generates a complete ops package from a single brief: run-of-show, outreach emails, social posts, budget, venue research, and more.

Built for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## What it does

Describe your event → answer a few questions → get ready-to-use deliverables.

**Professional events** get up to 16 deliverables: run-of-show with coaching notes, planning tracker, budget breakdown, 7-email communication sequence, speaker outreach templates, social media posts, day-of checklist, post-event survey, Luma page draft, ice breakers, sponsor pitch, and more.

**Personal events** (birthdays, dinners, celebrations) get 10 adapted deliverables with a warmer tone.

The agent acts as a coach, it surfaces things you'd forget, flags timeline risks, and adapts everything to your event format and budget.

## How to use

**Prerequisites:** [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed + Claude Pro subscription.

```bash
git clone https://github.com/silviacarasel/Event-in-a-Box.git
cd Event-in-a-Box
claude
```

Then describe your event:

```
> I'm planning a 75-person AI networking panel for March 20th, 
  $3K budget, in-person in Manhattan.
```

The agent will walk you through the intake, ask where you want deliverables (Notion or files), let you pick which ones to generate, and create them.

## Files

```
Event-in-a-Box/
├── CLAUDE.md              ← The agent brain (all instructions)
├── README.md              ← You're reading this
├── output/                ← Generated deliverables land here
└── config/
    └── org-profiles/      ← Saved org profiles for reuse
```

## Full documentation

Design process, architecture decisions, and step-by-step guide:
**[silvia-carasel.notion.site/event-in-a-box](https://silvia-carasel.notion.site/event-in-a-box)**

## License

MIT
