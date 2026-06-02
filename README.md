# AI Writing Filters

A free Claude skill that makes anything Claude writes for you come out sounding like a person wrote it, not a machine.

Made by [Growth Models](https://growthmodels.co).

## What it does

AI writing has a template. People can spot it now even when they can't name what they're spotting. This skill stops Claude producing that template in the first place.

It works on two fronts at once:

- **Rhythm.** The tidy pairs, the sentence threes, the "it's not X, it's Y" see-saw, the neat bow at the end. The skill breaks the cadence so the writing reads lopsided and human.
- **Abstraction.** The way AI describes a thing from a distance instead of naming it. The skill pushes for the concrete: the actual mechanism, the named symptom, the round number a person holds in their head.

It is not a clean-up pass you run on a finished draft. It shapes the writing from the first word. Set it up once and every "write me a post from this" comes out clean.

## What it doesn't do

It strips the robot. It does not hand your writing a personality. If you've given Claude your own voice or brand notes, it writes in that and stays out of the way. If you haven't, it writes plain and human. Sounding like a *specific person* is a bigger job, and that's what our paid [Content Agent](https://growthmodels.co) is for.

## Use it

Pick whichever route matches how you use Claude.

**Quickest: point Claude at the link**

Paste this into any Claude chat:

> Read https://raw.githubusercontent.com/PJBoyle1/ai-writing-filters/main/SKILL.md and follow it for everything you write from now on.

Claude pulls in the skill and applies it for the rest of that conversation.

**Persistent: Claude Code / Claude Desktop**

Save the skill into your skills folder so it loads every time:

```
~/.claude/skills/ai-writing-filters/SKILL.md
```

You can grab the file straight from this repo:

```
mkdir -p ~/.claude/skills/ai-writing-filters && \
curl -o ~/.claude/skills/ai-writing-filters/SKILL.md \
  https://raw.githubusercontent.com/PJBoyle1/ai-writing-filters/main/SKILL.md
```

**Claude Projects (claude.ai)**

Open your Project, go to project knowledge, and add the contents of `SKILL.md`. It applies to every chat in that Project.

## Get started

There's a short video walking through a real example at [growthmodels.co](https://growthmodels.co).

## Source and credit

The word and phrase flags draw on the public catalogue at Wikipedia, ["Signs of AI writing"](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing). The rhythm-and-abstraction approach is our own, built from years of editing AI output back into something a person would actually say.

## Licence

[CC BY 4.0](./LICENSE). Use it, share it, adapt it. Keep the credit to Growth Models.
