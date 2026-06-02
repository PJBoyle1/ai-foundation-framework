# AI Foundation Framework

This file is the foundation your AI loads before it does anything. It is deliberately thin. Its only job is to pull in the focused files below in the right order, so the model gets a clean, ordered brief instead of one giant wall of instructions it skims and half-ignores.

That ordering is the whole point. A single overloaded file gets cherry-picked. A small root file that loads focused pieces in sequence does not. This is the difference between a foundation and a prompt.

## Load order

Read these in order. Each one builds on the one before it.

@foundation/business.md
@foundation/hygiene.md
@foundation/writing.md

- **business.md** tells you who this person serves, what they sell, and how they sound. Without it you are guessing. Fill it once using `setup.md`.
- **hygiene.md** is how you work: push back, state assumptions, surface tradeoffs. It stops you being a yes-machine.
- **writing.md** governs how anything you write comes out, so it reads like a person wrote it and not a machine.

## Where the rest mounts

This is the chassis. It holds your context and your operating rules, and it makes everything you produce cleaner and more like you.

It does not include the production engine: the per-format content skills, the one-thought-into-a-week-of-posts multiplier, the deep voice work, or the quality-control pass. Those bolt onto this foundation. See `ARCHITECTURE.md` for where they go and how the handoffs work.

If you are reading this and you have not run the setup yet, open `setup.md` and run it first.
