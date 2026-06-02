# The architecture

Most people trying to get better AI output do the same thing: they keep adding rules to one big instruction file. A line about em dashes here, a tone note there, a "please push back" at the bottom. Then the output degrades anyway, so they add more rules, which contradict the old ones, so they strip some out, and it gets worse.

The problem isn't the rules. It's that one overloaded file gets skimmed. The model reads it the way you read a long blog post: it cherry-picks. Overload the context and it gets confused about what matters, so it guesses, and you get inconsistent results.

What fixes it isn't better rules. It's structure. The right hierarchy, the right load order, and clean handoffs between pieces. That's what this framework is.

## The hierarchy

```
CLAUDE.md              the root. thin. loads the rest in order.
  foundation/
    business.md        who you serve, what you sell, how you sound
    hygiene.md         how the AI works: push back, assume out loud, show tradeoffs
    writing.md         how anything it writes comes out
```

`CLAUDE.md` does almost nothing itself. It points. It pulls in the focused files in a deliberate order, so the model gets a clean, sequenced brief instead of a wall of text. Each file does one job and does it in isolation, which is exactly why the model actually follows it.

This is the difference between a foundation and a prompt. A prompt is a thing you paste once. A foundation is loaded every session, in order, before any work starts.

## Load order matters

The order in `CLAUDE.md` is not decoration. Context first (business), then operating rules (hygiene), then output rules (writing). The model builds understanding in that sequence: it knows who it's working for before it learns how to behave, and it knows how to behave before it learns how to write. Reorder it and you weaken it.

## Handoffs

A foundation gets you a clean, well-briefed model. It does not, on its own, produce a week of content. Real work happens when focused skills hand off to each other in a chain.

The pattern looks like this:

```
[ research ]  ->  [ create ]  ->  [ quality check ]  ->  [ schedule / ship ]
```

Each stage is its own skill with its own narrow job. Research finds the angle and hands its output to creation. Creation drafts the piece and hands it to a quality check. The quality check either passes it on or kicks it back with specific fixes. Nothing moves forward until the stage before it is done properly.

This is why one mega-prompt can't compete. You're not asking one overloaded instruction to be researcher, writer, editor, and scheduler at once. You're building a line where each station does one thing well and passes clean work to the next.

## Where the engine mounts

This framework is the chassis. It holds your context and your standards, and it makes every individual thing the AI produces cleaner and more like you.

The chassis has empty mounts. They are the stages above:

- **The create stage** is a set of per-format skills: a LinkedIn post skill, a carousel skill, a shorts skill, each one tuned to what works on that platform.
- **The multiplier** is the part that takes one thought or one video and turns it into 40, 70, a hundred pieces across every channel, so you're omnipresent without the hours.
- **The deep voice work** is your tone of voice codified properly, tuned per platform, so the volume still sounds like you and not like a hundred AI posts.
- **The quality check** is the supervisor that reviews every piece against your standards before it ships, so you're never publishing slop.

Those are the engine and the tyres. They bolt onto this foundation. That's our Content Agent: [growthmodels.co/social-ai-agent/](https://growthmodels.co/social-ai-agent/).

You can drive the chassis as-is and it'll serve you well. When you want it producing volume in your voice on autopilot, that's where the engine goes.
