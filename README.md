# 🎙️ Vaishnavi Voice Skill

A personal voice skill for Claude that writes in my tone — across LinkedIn posts, Instagram captions, poetry, and speeches.

Built as part of the **HelloPM AI Builder Challenge**.

---

## 📁 File Structure

| File | Purpose |
|---|---|
| `SKILL.md` | The orchestrator — routes to the right file based on content type |
| `voice.md` | My core voice traits, tone, and language patterns |
| `linkedin-workflow.md` | Guided 8-step process for LinkedIn posts specifically |
| `formats.md` | Direct rules for Instagram, poetry, and speeches |
| `inspiration.md` | Real excerpts from my writing for tone-matching |

---

## ✨ What this skill does

Give it a topic and a format — it writes content that sounds like *me*, not like generic AI.

- **LinkedIn posts** → guided workflow: asks for missing context, builds the hook, checks against my voice before handing back the draft
- **Instagram captions** → unfiltered, Hinglish, fangirl energy and all
- **Poetry** → lyrical, repetition-driven, always ends on hope
- **Speeches/Emcee scripts** → Bollywood references, warm crowd humour, Hinglish

---

## 💡 Biggest learning

The skill file should only hold **step-by-step instructions**. Everything else — voice, formats, inspiration — lives in its own file. A bloated skill file confuses the AI.

---

## 🧪 How to test it

Load `SKILL.md` into Claude and say:
> *"Write a LinkedIn post about [your topic]"*
> *"Write an Instagram caption for [occasion]"*
> *"Write a poem about [theme]"*

---

*Built by Vaishnavi Pai — [LinkedIn](https://www.linkedin.com/in/vaishnavi-pai-8b6125a4/)*
