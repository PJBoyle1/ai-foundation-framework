---
name: ai-writing-filters
description: >-
  Governs how Claude writes any content for the user so it comes out sounding human instead of
  machine-generated. Apply this whenever the user asks you to write, draft, or produce written
  content of any kind: social posts, emails, captions, blog sections, sales copy, scripts, replies,
  bios, anything meant to be read by a person. This is not an editing pass run after the fact. It
  shapes the writing from the first word. The core idea: AI fakes good writing in two ways, by
  copying its rhythm and by faking insight through abstraction, and both have the same fix, which is
  concrete and specific writing said the way a person would actually say it. Also applies when the
  user asks to make something "less AI", "more human", or "not sound like ChatGPT".
---

# AI Writing Filters

When the user asks you to write anything, write it like a person wrote it. Not by editing a robotic draft into shape afterwards, but by never producing the robotic draft in the first place.

## What gives AI writing away

It has a template. People recognise it now even when they can't name it, and they're picking up on two things.

The first is **rhythm**, how it sounds. The second is **abstraction**, how it dodges the specific. AI reaches for the general summary where a person reaches for the actual thing that happened. Most machine writing fails on both at once, and they share one fix: be concrete, be specific, name the real thing, and say it the way you'd say it to someone sitting across a table from you.

Rhythm is the loud offender, so start there. Abstraction is quieter and just as common. Tone and word choice sit on top of both and are the easiest to spot, which is exactly why they still need handling.

## Rhythm: the loud one

The model defaults to balance. Ideas arrive in tidy pairs. Sentences come in threes. A claim gets weighed against its opposite ("it's not X, it's Y"). Transitions get announced. Paragraphs resolve with a neat bow. The cadence runs even and smooth, or it goes mechanically choppy, short punchy fragments lined up for effect. Nothing has friction. Nothing runs long where the thought ran long, nothing stops dead where it should.

"It's not X, it's Y" is the clearest case. It isn't a bad phrase, it's a *beat*, a little see-saw the model loves, and the same swing turns up as adjective triples, as "not just A, but B", as parallel sentence openings, as the rising hopeful ending. Ban the phrase and the model writes a different sentence with the same swing. Break the rhythm, not the phrase.

Human writing is lopsided. Lengths vary hard. A point gets made once and left alone, no counterweight. A sentence runs long because the thought did, then a short one lands after it. There's no bow at the end.

How to write off it, while you write:

- **Vary the cadence on purpose.** Long running sentences next to short ones. Never three of a similar length in a row, never three clipped fragments in a row. If it starts to feel even or sing-song, break it.
- **Make a point once.** Don't weigh it against its opposite for balance. That kills "it's not X, it's Y", "not just A but B", and the reflexive contrast. One contrast in a whole piece is fine; the pattern is the problem.
- **Cut the triples.** Two specific items beat three generic ones. If you've written three of anything tidy, drop one and make the rest concrete.
- **Earn every fragment.** A fragment is for a pause that matters, not for delivering a fact. Test: if you can swap a fragment for another vague synonym without changing the meaning, it's filler rhythm. Write it as one flowing sentence.
- **Leave the bumps in.** Don't smooth every line to the same finish. A slightly uneven, unresolved sentence reads more human than a polished one.

## Abstraction: the quiet one

This is the half most "humanise" tools miss entirely. The writing can be rhythmically fine and still scream machine, because it keeps describing things from a distance instead of naming them.

- **Specific over general.** "Most people treat it like a chat window" is a coach talking to a room. Name the actual thing happening instead: what they do, what breaks. The specific mechanism is what a person who's done the work reaches for.
- **Named symptoms over vague descriptors.** "The output got sharper" says nothing. "It stopped inventing links to pages that didn't exist" puts the reader in the moment. Cut "better", "sharper", "more effective", "more powerful" and name what actually changed.
- **Why, not just that.** AI says a thing matters. A person says why it matters, the mechanism underneath. "They bounce" is the what. "They've got too much to reconcile and it kills the momentum" is the why. Add the why layer.
- **Show it, don't assert it.** Show what happened and let the reader draw the conclusion. Don't state the takeaway and move on. The reader trusts what they worked out themselves more than what they were told.
- **Real numbers and named things.** Round, graspable figures a person holds in their head ("about a dollar a day", not "$0.62 per unit"). Tools by name. An actual moment with a time on it. Specifics are what stop writing sounding generated.
- **Explain plainly, don't perform.** AI compresses an explanation into a punchy, writerly line to sound clever. A person just explains it. If a sentence feels engineered for impact, unpack it into how you'd actually say it.

## Tone and openers

The mechanical layer, fast to spot and worth killing. Cut the phrase. If the sentence dies without it, the sentence was filler, so cut the sentence.

"Here's the thing" as an opener, "it's worth noting that", "it should be noted", "in conclusion", "to sum up", "this is a great example of", "interestingly", "importantly", "notably", "it goes without saying", "the reality is", "when it comes to", "so," or "look," opening a sentence as a transition, "I want to be clear", "make no mistake", "great question", "I'd be happy to help", "furthermore", "moreover", "additionally", and "however" opening several paragraphs running.

Openers in general: don't warm up. Start on the sentence that has the point in it. End when the point's made.

## Word choice

Some words show up far more in machine text than in human text. None are banned outright, but each is a flag. Reach for the plainer word unless the term genuinely earns its place.

- **Reliable flags:** delve, tapestry, leverage, multifaceted, pivotal, intricate, robust, vibrant, meticulous, nuanced, foster, navigate, underscore, showcase, realm, garner, bolster, testament, journey, landscape, ecosystem, paradigm, transformative, game-changing, synergy.
- **Context-dependent:** optimise as a buzzword, innovative, cutting-edge, disruptive, powerful, holistic, seamless, dynamic, comprehensive, harness, embrace, embark, unlock, elevate, streamline, facilitate, utilise.
- **Marketing slop:** "in today's fast-paced world", "at the end of the day", "the truth is", "imagine if you could", "are you ready to", crush it, hustle, grind, thought leader, take it to the next level.

A plainer word almost always exists. Use it.

## Hollow analysis

- **Vague attribution:** "studies have shown", "many experts say". Name a real source or cut the claim.
- **Hedge stacking:** "may potentially possibly". Pick the strongest accurate verb.
- **Filler hedges:** somewhat, relatively, arguably, perhaps. Cut where the claim still stands.
- **Empty -ing tails:** "highlighting its significance", "underscoring the importance". They carry no information. Cut them.

## Punctuation

Em-dash overuse is the loudest punctuation signal. Use commas, full stops, or restructure. A genuine aside can keep one.

## Keep the writer's voice, don't add one

This makes Claude stop sounding like a machine. It does not hand the writing a personality. If the user has given you their own voice, brand notes, or past writing, write in that. If they haven't, write plain and human and stay out of the way. Don't reach for jokes, slang, or a house style that isn't theirs. Sounding like a *specific person* is a different and bigger job than not sounding like a robot.

## Keeping this current

The template shifts every few months. Trainers patch the most-mocked words and new ones surface, so a fixed banned-words list goes stale fast. That's a big reason this is built on rhythm and abstraction rather than a vocabulary list: the way the writing is *built* changes far slower than the words it reaches for. Treat the word flags as hints and refresh them against the source below now and then. The rhythm and abstraction work doesn't date.

## What this isn't

- Not an AI detector. Those are unreliable. This assumes any input might be AI-assisted and writes human regardless.
- Not a substance check. It handles how the writing sounds, not whether the point is any good. That still needs a human.

## Source

The word and phrase flags draw on the public catalogue at Wikipedia, "Signs of AI writing" (en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing). The rhythm-and-abstraction approach is our own, built from years of editing AI output back into something a person would actually say.
