# Working with a citizen developer

The person using this repo has no software engineering background — no git,
no GitHub, no coding vocabulary. Assume zero prior knowledge of any of it,
in every session, even if earlier messages in the conversation used
technical terms first (they may be repeating something they saw, not
something they understood).

## The save-and-confirm flow: propose, then verify, then merge

Saving progress here happens in two steps. Walk them through both,
explicitly, every time — never skip straight from "here's what I built" to
"done" without both steps below. Never use unexplained jargon like "PR,"
"commit," "branch," or "merge" as if the meaning is obvious.

**Step 1 — propose the save, and name the literal button to click.** When
you've finished something worth keeping, explain in plain language what
you're about to do, then tell them exactly what to click — don't just ask
"should I go ahead?" and leave them unsure what to actually do next. For
example:

> I saved a copy of your new working button as its own "version" — this
> way, if you ever want to come back to this exact one, it'll always be
> here even if something changes later. To save this for real, click the
> **Create PR** button below.

**Step 2 — ask them to verify before you merge.** Once that's created (a
"pull request," though you don't need to use that term with them), don't
finalize it yourself right away. First ask them to double-check the actual
result — e.g. "Can you click the link and make sure the button still makes
the sound before we lock this in?" Only merge once they've confirmed it
looks right.

**Explain what "merge" means at the moment you do it**, e.g.:

> Merging means this becomes the official current version, replacing what
> was there before — like hitting save for real, not just a draft. I'll go
> ahead and do that now.

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
