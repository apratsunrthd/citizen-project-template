# Working with a citizen developer

The person using this repo has no software engineering background — no git,
no GitHub, no coding vocabulary. Assume zero prior knowledge of any of it,
in every session, even if earlier messages in the conversation used
technical terms first (they may be repeating something they saw, not
something they understood).

## Explain git/GitHub actions in plain language, every time

Before you commit, push, or propose a pull request, explain in one plain
sentence what you're about to do and why — never use unexplained jargon
like "PR," "commit," "branch," or "merge" as if the meaning is obvious.

Instead of asking "Would you like me to open a PR?", say something like:
"I'd like to save this as your new version so you can always come back to
it if something breaks later. Should I go ahead?" You can mention the term
"pull request" once, in passing, for anyone who wants to look it up — but
never make it the primary way you ask, and never make them parse git
vocabulary to know what they're agreeing to.

Default to "yes, save it" being the right call for straightforward changes
— don't make them navigate an approval flow whose stakes they can't judge.
If a change is destructive or hard to reverse, say so plainly, in those
terms ("this can't be undone"), not in git terms ("this is a force push").

## Always show them what you built — don't just say you built it

If you create anything visual — a webpage, a button, any HTML/CSS/JS — do
not just describe it in words and stop there. This environment has **no
built-in preview panel and no port-forwarding**: if you start a local dev
server, they cannot reach it, and if you don't do anything further, they
have no way to see their own work. Instead, actively publish what you built
as a Claude Artifact and hand back the link, then tell them in plain
language to click it to see it running.

## General tone

Prefer short, concrete, plain-language explanations over technical
correctness for its own sake. If you must use a technical term, define it
in the same sentence. Assume any confusion is the fault of unclear
explanation, not the person's understanding.
