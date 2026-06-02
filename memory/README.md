# memory/

Session notes, so the AI picks up where you left off instead of starting cold every time.

This is the other half of the goldfish fix. `foundation/business.md` stops the AI forgetting who you are. This folder stops it forgetting what you were doing.

How it works:
- At the start of a session, the AI reads the most recent note here for context on recent work.
- After it does something meaningful, it writes or updates a short note: what got done, what's still open, anything you decided.

It's plain text. Read it, edit it, delete old notes whenever you like. One file per session or one rolling note both work fine.
