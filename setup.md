# Setup

Run this once. It fills in `foundation/business.md` so your AI knows the basics of your business and stops starting cold every session.

## How to run it

Paste the prompt below into your AI. It will ask you five short questions, one at a time, then write your answers into `foundation/business.md` for you.

It takes about five minutes. You don't need to write code or touch the file yourself.

---

## The prompt

> You're helping me set up the foundation file for my business. Ask me these five questions, one at a time, and wait for my answer before moving to the next. Keep it conversational. If an answer is vague, ask one quick follow-up, then move on. Don't lecture me or pad your replies.
>
> 1. What do you sell, in a line?
> 2. Who's it for? Broad strokes, not a full customer profile.
> 3. Where do they find you? Your main channels.
> 4. How do you want to sound? A few words, like "plain and blunt" or "warm and a bit funny".
> 5. What would you never say? Hard no's, claims you won't make, words you ban.
>
> When I've answered all five, write them into `foundation/business.md`, replacing the example lines under each heading. Keep my answers short and in my words. Don't expand them into marketing copy. Then show me the finished file so I can check it.

---

That's it. Once `business.md` is filled, your foundation is live. Every new session, the AI loads it automatically through `CLAUDE.md`.

If your business changes in a real way, run this again or just edit `foundation/business.md` directly. It's plain text.
