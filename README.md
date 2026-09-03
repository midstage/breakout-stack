# The Breakout Stack

![14 skills](https://img.shields.io/badge/skills-14-8B5CF6) ![4 phases](https://img.shields.io/badge/phases-4-8B5CF6) ![6 reference guides](https://img.shields.io/badge/reference%20guides-6-8B5CF6) ![Claude + ChatGPT](https://img.shields.io/badge/works%20with-Claude%20%26%20ChatGPT-8B5CF6)

Most AI-native "stacks" (gstack included) are about how to build an early-stage product — 0 to 1, ship fast, find PMF. This one starts after that: **how to lead a startup that's already working but has plateaued** — how a founder turns a mediocre, founder-bottlenecked company into an extraordinary one, one real breakthrough per quarter, stacked on the last.

This repo is the actual product: not PDFs to read, 14 skills you install into Claude or ChatGPT and run.

## Install it

**Claude Code / Claude Desktop:** copy the `skills/` folder into your own `.claude/skills/` directory (or point Claude at this repo directly). Each skill activates automatically when you describe what you're trying to do.

**ChatGPT:** paste the contents of a skill's `SKILL.md` into a Custom GPT's instructions, or straight into a chat when you want to run that specific step.

Don't know where to start? Run **`find-your-blindspot`** — tell it about your startup and it'll tell you what's actually stuck, before you know the vocabulary. Already know the rhythm? Start with **`start-here`** instead — it routes you straight to the right phase.

## The rhythm: Stuck → Stock → Stick → Stack

1. **Stuck** — *Are you feeling stuck?* The recognition moment. Something isn't moving the way it should, and it's not yet clear why.
2. **Stock** — *Take stock of your flywheel.* Turn the vague "stuck" feeling into a real diagnosis: the actual constraint, and the one 25%+ move worth committing the quarter to.
3. **Stick** — *Stick to one priority breakthrough.* Cascade it into team rocks, decision authority, and a weekly rhythm — then hold the line against distraction.
4. **Stack** — *Stack those breakthroughs over time.* Close the quarter, bank the win, start the next cycle. One breakthrough is a good quarter. Four in a row is a different company.

## Every skill in the stack

| # | Skill | Phase | What it does |
|---|---|---|---|
| — | [`find-your-blindspot`](skills/find-your-blindspot/SKILL.md) | Intake | The true entry point — diagnoses your blind spot from a plain "tell me about your startup" answer, before you know any of this vocabulary. |
| — | [`start-here`](skills/start-here/SKILL.md) | Router | Figures out where you are in the Stuck→Stock→Stick→Stack cycle and routes you to the right skill. |
| 1 | [`breakout-cleverness-ceiling-assessment`](skills/breakout-cleverness-ceiling-assessment/SKILL.md) | Stuck | Diagnoses whether the founder's own speed has trained the team to stop deciding independently. |
| 2 | [`breakout-interview-analysis`](skills/breakout-interview-analysis/SKILL.md) | Stuck | Reads anonymous team-interview responses and surfaces the real constraint and unsaid grievances underneath them. |
| 3 | [`breakout-flywheel-mapping`](skills/breakout-flywheel-mapping/SKILL.md) | Stuck | Maps the 3-4 core systems producing revenue and finds which one is the actual bottleneck. |
| 4 | [`breakout-identify-quarterly-breakthrough`](skills/breakout-identify-quarterly-breakthrough/SKILL.md) | Stock | Commits to ONE 25%+ move for the quarter instead of a laundry list of priorities. |
| 5 | [`breakout-breakthrough-narrative`](skills/breakout-breakthrough-narrative/SKILL.md) | Stock | Turns the chosen breakthrough into a real story the team, board, or customers will actually rally behind. |
| 6 | [`breakout-quarterly-rocks`](skills/breakout-quarterly-rocks/SKILL.md) | Stock | Cascades the breakthrough into 3-5 measurable quarterly rocks with leading indicators. |
| 7 | [`breakout-team-thinking-audit`](skills/breakout-team-thinking-audit/SKILL.md) | Stick | Diagnoses whether the founder's management style is training the team to think, or to wait. |
| 8 | [`breakout-authority-map`](skills/breakout-authority-map/SKILL.md) | Stick | Designs a decision-authority map — what a team member can decide without founder sign-off. |
| 9 | [`breakout-leader-handoff`](skills/breakout-leader-handoff/SKILL.md) | Stick | Prepares the founder to hand off one decision domain to a named person, including how to back them when they get it wrong. |
| 10 | [`breakout-weekly-rocks-review`](skills/breakout-weekly-rocks-review/SKILL.md) | Stick | Reads a week's rocks-progress report and surfaces the real pattern underneath the checkmarks. |
| 11 | [`breakout-bottleneck-check`](skills/breakout-bottleneck-check/SKILL.md) | Stick | Checks whether the original constraint is still the real one, or has silently shifted. |
| 12 | [`breakout-micro-breakthrough`](skills/breakout-micro-breakthrough/SKILL.md) | Stick | Finds a real, provable small win to keep the team's energy up mid-quarter. |

Each skill is self-contained — run any of them standalone — but `start-here` and `find-your-blindspot` are what turn 12 narrow tools into one system.

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
│   ├── breakout-flywheel-mapping/SKILL.md                /
│   ├── breakout-identify-quarterly-breakthrough/SKILL.md  \
│   ├── breakout-breakthrough-narrative/SKILL.md            } Stock
│   ├── breakout-quarterly-rocks/SKILL.md                  /
│   ├── breakout-team-thinking-audit/SKILL.md               \
│   ├── breakout-authority-map/SKILL.md                      \
│   ├── breakout-leader-handoff/SKILL.md                      } Stick
│   ├── breakout-weekly-rocks-review/SKILL.md                /
│   ├── breakout-bottleneck-check/SKILL.md                  /
│   └── breakout-micro-breakthrough/SKILL.md                /
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
