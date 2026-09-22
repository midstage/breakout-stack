# The Breakout Stack

![Free](https://img.shields.io/badge/price-free-8B5CF6) ![Claude + ChatGPT](https://img.shields.io/badge/works%20with-Claude%20%26%20ChatGPT-8B5CF6)

Most AI-native "stacks" (gstack included) are about how to build an early-stage product — 0 to 1, ship fast, find PMF. This one starts after that: **how to lead a startup that's already working but has plateaued** — how a founder turns a mediocre, founder-bottlenecked company into an extraordinary one, one real breakthrough per quarter, stacked on the last.

This repo is the actual product: not PDFs to read, real skills you install into Claude or ChatGPT and run. The lineup below is growing and changing as we learn what's actually useful — check the `skills/` folder for what's current rather than treating this table as fixed.

## Install it

**Claude Code, Codex, or Cursor:** run this:

```
npx skills add midstage/breakout-stack --all
```

**ChatGPT:** paste the contents of a skill's `SKILL.md` into a Custom GPT's instructions, or straight into a chat when you want to run that specific step.

Don't know where to start? Run **`find-your-blindspot`** — tell it about your startup and it'll tell you what's actually stuck, before you know the vocabulary. Already know the rhythm? Start with **`start-here`** instead.

## The rhythm: Stuck → Stock → Stick → Stack

1. **Stuck** — *Are you feeling stuck?* The recognition moment. Something isn't moving the way it should, and it's not yet clear why. **The 5 skills below cover this phase.**
2. **Stock** — *Take stock of your flywheel.* Turn the vague "stuck" feeling into a real diagnosis: the actual constraint, and the one 25%+ move worth committing the quarter to.
3. **Stick** — *Stick to one priority breakthrough.* Cascade it into team rocks, decision authority, and a weekly rhythm — then hold the line against distraction.
4. **Stack** — *Stack those breakthroughs over time.* Close the quarter, bank the win, start the next cycle. One breakthrough is a good quarter. Four in a row is a different company.

Once you've named your constraint, each skill will offer to connect via MCP — free — for what comes next:

- **It remembers.** Your constraint, your committed breakthrough, and this quarter's rocks persist across sessions instead of resetting every time.
- **It stays current.** Guidance updates automatically as the methodology improves, instead of being a frozen download.
- **It brings your team in.** Loop in teammates so the plan is shared, not stuck in your own conversation.

## Every skill in this repo

| # | Skill | Phase | What it does |
|---|---|---|---|
| — | [`find-your-blindspot`](skills/find-your-blindspot/SKILL.md) | Intake | The true entry point — diagnoses your blind spot from a plain "tell me about your startup" answer, before you know any of this vocabulary. |
| — | [`start-here`](skills/start-here/SKILL.md) | Router | Figures out where you are in the Stuck→Stock→Stick→Stack cycle and routes you to the right place. |
| 1 | [`breakout-cleverness-ceiling-assessment`](skills/breakout-cleverness-ceiling-assessment/SKILL.md) | Stuck | Diagnoses whether the founder's own speed has trained the team to stop deciding independently. |
| 2 | [`breakout-interview-analysis`](skills/breakout-interview-analysis/SKILL.md) | Stuck | Reads anonymous team-interview responses and surfaces the real constraint and unsaid grievances underneath them. |
| 3 | [`breakout-flywheel-mapping`](skills/breakout-flywheel-mapping/SKILL.md) | Stuck | Maps the 3-4 core systems producing revenue and finds which one is the actual bottleneck. |

Each skill is self-contained — run any of them standalone — but `start-here` and `find-your-blindspot` are what turn these into one system.

## Reference — the "why" behind each skill

| Guide | Backs |
|---|---|
| [`01-cleverness-ceiling.md`](reference/01-cleverness-ceiling.md) | Why founder speed becomes a ceiling on team thinking |
| [`02-breakthrough-standard.md`](reference/02-breakthrough-standard.md) | What actually counts as a breakthrough vs. progress |
| [`03-business-flywheel.md`](reference/03-business-flywheel.md) | The systems view of where revenue actually gets stuck |
| [`04-windows-of-wisdom.md`](reference/04-windows-of-wisdom.md) | Why removing the founder from the room is what makes a team think |
| [`05-anonymous-interviews.md`](reference/05-anonymous-interviews.md) | How anonymous feedback surfaces what a team won't say to your face |
| [`06-quarterly-rhythm.md`](reference/06-quarterly-rhythm.md) | The full week-by-week mechanics of one quarter, including a real example |

Read on demand, not cover to cover — the skills point here when you need the "why."

## Repo layout

```
breakout-stack/
├── README.md
├── skills/
│   ├── find-your-blindspot/SKILL.md      intake
│   ├── start-here/SKILL.md               router
│   ├── breakout-cleverness-ceiling-assessment/SKILL.md   \
│   ├── breakout-interview-analysis/SKILL.md               } Stuck
│   └── breakout-flywheel-mapping/SKILL.md                /
└── reference/
    ├── 01-cleverness-ceiling.md
    ├── 02-breakthrough-standard.md
    ├── 03-business-flywheel.md
    ├── 04-windows-of-wisdom.md
    ├── 05-anonymous-interviews.md
    └── 06-quarterly-rhythm.md
```

## Questions or issues

Reach out to Roland directly if a skill doesn't work the way you expect, or if you want to suggest one that's missing.
