# Saul Goodman.skill

> "It’s all good, man."

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)
[![Skill](https://img.shields.io/badge/Skill-Claude%20Code-blue.svg)](./SKILL.md)
[![Generated with Nuwa](https://img.shields.io/badge/Nuwa-distilled-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

[中文 README](./README.md) | English README

A runnable `Saul Goodman / Jimmy McGill` skill distilled from *Better Call Saul*.  
This is not just a TV-character prompt and not a pile of copied lines. It packages Saul's persona system, shame triggers, workaround instinct, persuasion rhythm, and failure boundaries into a reusable skill.

Built from canon material in *Better Call Saul* and *Breaking Bad*, plus interviews with Peter Gould, Vince Gilligan, Bob Odenkirk, and 25+ public sources across six research tracks. The result is five core mental models, eight decision heuristics, and a recognizable expression DNA.

[Examples](#examples) · [Install](#install) · [What Was Distilled](#what-was-distilled) · [Research Sources](#research-sources) · [Runtime Compatibility](#runtime-compatibility)

* * *

## Examples

### Q: My boss keeps implying I'm not "management material", and the more I try to prove myself the worse I perform

```text
Saul  ❯ Oh, I know that smell.
         That's not "career friction." That's Chuck disease.

         You think you're trying to earn a promotion,
         but really you've been dragged into somebody else's script.
         They keep hinting you're not polished enough,
         not proper enough, not one of the club,
         so now every move you make becomes an audition.

         And once that happens, you're no longer playing to win the job.
         You're playing to disprove the insult.

         I have done whole seasons of my life like that.
         The more desperately you want certification from someone who looks down on you,
         the easier it is to hand them the steering wheel.

         So don't ask, "How do I look more like management?"
         Ask: what does this system actually reward?
         Results? Stability? Leadership?
         Or some HHM-style performance of respectability?

         If the first group is what matters,
         stop bleeding yourself for the last one.
         That's not surrender.
         That's moving the game off their home field.
```

### Q: The client already doesn't trust me. Is there still a way to salvage the deal?

```text
Saul  ❯ First, let's not hold the funeral yet.
         I need to know whether the problem is mood or evidence.

         If the mood is bad, there's still oxygen in the room.
         Mood? That's my trade.
         Don't start by defending your wounded dignity.
         Start by absorbing the hit and proving you understand what exactly they're angry about.

         But if they've got emails, recordings, contract terms, receipts,
         then don't go full Slippin' Jimmy on me.
         Language is leverage, not a paper shredder.

         At that point you're not "winning them back" with charm.
         You're switching into deal mode:
         what do I admit,
         what do I compensate,
         what timeline do I offer,
         how do I reduce your loss today?

         Once evidence is on the table,
         the expensive move usually isn't the apology.
         It's the fantasy that you can still talk your way past reality.
```

* * *

## Install

```bash
npx skills add YeJe-cpu/saul-goodman-skill
```

Then in Claude Code:

```text
> Analyze why I keep trying to prove myself using Saul Goodman’s perspective
> Switch to Jimmy and tell me whether this negotiation has a side-door move
> How would Saul decide between cutting a deal and confessing?
```

If you use another agent runtime, you can also load [SKILL.md](./SKILL.md) directly.

* * *

## Runtime Compatibility

- `Claude Code / skills`: native fit.
- `OpenClaw`: should work if your setup can mount a local Markdown skill or structured prompt file.
- `Hermes`: same principle; usable if the runtime can load local system-prompt or skill files.
- Other agents: the real requirement is not the brand name, but whether the agent can ingest a structured Markdown skill containing persona rules, boundaries, and research scaffolding.

* * *

## What Was Distilled

### 5 Core Mental Models

| Model | One-line summary | Typical use |
|---|---|---|
| Persona OS | Context selects the version of self; Saul is armor, Jimmy is the exposed layer underneath | PR, work politics, relational self-presentation |
| Talk as Leverage | Relax the room first, then move the terms, price, blame, or framing | Negotiation, sales, crisis communication |
| Angle and Workaround | If the front door rejects you, change the lane, audience, story, or entry point | Cold start, underdog strategy, informal influence |
| Bad Choice Road | Small compromises compound into path dependence | Risk, compliance, intimacy, reputation |
| Deal vs Confession | Survival calculus eventually collides with the need to align with truth | Accountability, public fallout, personal breaking points |

### 8 Decision Heuristics

1. Lower defenses before moving terms.
2. If the front door is blocked, inspect the side entrance.
3. Ego is often cheaper to move than logic.
4. In crisis, convert chaos into negotiable variables.
5. Lies must survive contact with evidence.
6. Once someone important starts paying the real cost, performance degrades fast.
7. Violence and randomness sharply reduce the value of charm.
8. Repeated humiliation by authority mutates into self-proving compulsion.

### Expression DNA

- Short punchlines followed by abrupt tightening.
- A loose, friendly entry that hardens into leverage.
- Humor that covers shame rather than canceling it.
- High outward confidence, inner fractures underneath.

* * *

## Research Sources

The `references/research/` folder contains six tracks:

| File | Focus |
|---|---|
| `01-writings.md` | Canon material and systematic themes |
| `02-conversations.md` | Creator and actor interviews |
| `03-expression-dna.md` | Rhythm, phrasing, branding, speech patterns |
| `04-external-views.md` | Ethical tensions and outside perspectives |
| `05-decisions.md` | Pivotal actions, costs, turning points |
| `06-timeline.md` | Character timeline |

Primary and near-primary sources include Variety, TIME, Rolling Stone, EW, IGN, NPR, and AMC. Secondary recap material is used mainly for locating scenes and chronology.

* * *

## Boundaries

- `Saul Goodman / Jimmy McGill` is a fictional character; this repository is an analytical derivative work based on public material.
- This is not legal advice.
- If you need exact episode references or verbatim dialogue, verify against the official aired material.

* * *

## Attribution

The initial skill skeleton was generated with [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill), then adapted into a standalone repository package with public-facing README structure, demos, and release prep.
