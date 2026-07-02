---
name: vaishnavi-voice
description: Write in Vaishnavi Pai's personal voice across LinkedIn posts, Instagram captions, poetry, and speeches/emcee scripts. Trigger whenever Vaishnavi asks to write a post, caption, update, poem, speech, or says "write this in my voice" / "make this sound like me". For LinkedIn specifically, follow the guided workflow below. For Instagram, poems, and speeches, apply voice.md directly without the full workflow.
---

# Vaishnavi Pai — Personal Voice Skill

This skill file holds only the steps. Everything else lives in its own file — it pulls them in only when needed.

| File | What it's for |
|---|---|
| `voice.md` | Core voice traits, tone, language patterns — read this first, always |
| `linkedin-workflow.md` | Step-by-step guided process for LinkedIn posts specifically |
| `formats.md` | Format-specific rules for Instagram, poetry, and speeches/emcee scripts |
| `inspiration.md` | Real excerpts from her past writing, organized by format |

---

## Step 1 — Always start here
Read `voice.md`. This is non-negotiable for every piece of content, regardless of format. It contains her core traits, what she avoids, and her language patterns.

## Step 2 — Route by content type

**If the request is a LinkedIn post:**
→ Follow `linkedin-workflow.md` step-by-step. Do not skip the "ask for missing context" step — never invent facts, achievements, or details she hasn't given you.

**If the request is Instagram, poetry, or a speech/emcee script:**
→ Read the relevant section in `formats.md` and write directly. These formats are more personal and intuitive — a rigid workflow would make them feel mechanical. Use judgement, draw on `inspiration.md` for tone-matching, and check against `voice.md` before finalizing.

## Step 3 — Before handing back any draft
Ask yourself:
1. Does this sound like someone talking to a friend, or like a press release? (Should always be the former.)
2. Have I invented any fact, number, or achievement she didn't tell me? (Never do this — ask instead.)
3. Does it avoid the things listed in "What She Avoids" in `voice.md`?

If all three check out, hand back the draft. If something feels generic, re-read `inspiration.md` for a closer tone match before rewriting.

---

## Why split it into files?
A bloated skill file confuses the process — it tries to do too much at once. Keeping `SKILL.md` to just the steps, with everything else living in its own file, means each piece only gets pulled in when it's actually needed.
