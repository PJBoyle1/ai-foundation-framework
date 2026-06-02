# AI Foundation Framework

A free foundation that makes AI actually useful in your business. It gives your AI the context, the operating rules, and the writing standards it needs so the output stops sounding generic and starts sounding like you, from the first session.

Made by [Growth Models](https://growthmodels.co).

## The problem this fixes

Most people use AI like a goldfish. Every new session you re-type who you serve, what you sell, how you sound. The AI forgets it all the next time. And whatever it gives back has the same generic template smell everyone else's AI has.

The usual fix is to dump every rule you can think of into one big instruction file. It works for a day, then the output degrades back to em-dash-filled slop. One overloaded file gets skimmed, not followed.

The fix isn't more rules. It's structure: the right files, loaded in the right order, each doing one job. That's this framework.

## What's in it

Think of it as the chassis of a car. It holds everything together and gives you something you can actually drive.

- **`CLAUDE.md`** is the root. It's thin. It loads the rest in order so the AI gets a clean brief instead of a wall of text.
- **`foundation/business.md`** holds the basics: who you serve, what you sell, how you sound. Fill it once and stop re-briefing.
- **`foundation/hygiene.md`** is how the AI works: push back instead of agreeing, state its assumptions, surface tradeoffs.
- **`foundation/writing.md`** governs how anything it writes comes out, so it reads human and not machine. It works on three fronts: rhythm, abstraction, and vocabulary.
- **`setup.md`** is a five-minute Q&A that fills in your business file for you.
- **`ARCHITECTURE.md`** explains how it all fits, and where the engine bolts on when you want more.

It also comes with a few working folders, empty to start: **`memory/`** (session notes so the AI doesn't forget what you did last time), **`inputs/`** and **`outputs/`** (raw material in, finished work out), and **`skills/`** (the mount where content skills bolt on). You fill them as you go.

## Install (about 15 minutes)

If you can edit a Google Doc, you can do this. No code, no terminal required.

**1. Get the files into your project**

Clone the repo into your working folder:

```
git clone https://github.com/PJBoyle1/ai-foundation-framework.git
```

Or in any Claude chat, paste:

> Read the files in https://github.com/PJBoyle1/ai-foundation-framework and set them up as my foundation, following the README and CLAUDE.md.

**2. Run the setup**

Open `setup.md` and follow it. It asks you five short questions, then writes your answers into `foundation/business.md`. Five minutes, done.

**3. Use it**

That's it. With `CLAUDE.md` in your project root, your AI loads the whole foundation every session. Ask it to write a post, draft an email, or think through a decision, and it already knows your business and stays clean.

Built around Claude Code because it's the easiest place to use it, but the architecture applies to any agentic AI (Codex and others).

## The chassis, and the engine

This framework is the chassis: context, operating rules, clean writing. It makes every individual thing your AI produces better and more like you.

It does not include the production engine: the per-format content skills, the part that turns one thought into a week of posts across every channel, the deep voice work, or the quality-control pass. Those bolt onto this foundation. That's our [Content Agent](https://growthmodels.co/social-ai-agent/).

You can drive the chassis as-is and it'll serve you well. When you want volume in your voice on autopilot, that's where the engine goes.

## Get started

There's a short video walking through the whole setup at [growthmodels.co](https://growthmodels.co).

## Source and credit

The writing word and phrase flags draw on the public catalogue at Wikipedia, ["Signs of AI writing"](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing). The rest, the architecture, the rhythm-and-abstraction approach, and the operating rules, is our own, built from running this inside real businesses.

## Licence

[CC BY 4.0](./LICENSE). Use it, share it, adapt it. Keep the credit to Growth Models.
