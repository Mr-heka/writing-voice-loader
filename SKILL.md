---
name: writing-voice-loader
description: "Build a voice sheet from a person's real writing and edit drafts to match it section by section. Use when someone wants AI drafts to sound like them, or says load my writing in first."
---

# Writing Voice Loader

Loads a person's real writing first, then edits a draft to sound like them. It works alone, and it works alongside the free Humanizer skill if that is installed.

## How to run

- Work through this without extra back-and-forth. Make the safest reasonable assumption, say it in one line, keep going. Only stop for something only the user has.
- Never invent a fact, figure, customer, price or quote. If it is unknown, write `[NEEDS ANSWER]` and list it at the end.
- Nothing here sends, posts, pays or changes a live account.
- If a step fails, retry it yourself and note what you changed. Do not stop at the first error.

## Build the voice sheet

Ask for three to five things the person wrote themselves, with no AI involved: sent emails, a proposal, a post. Take file paths or pasted text.

Save `voice.md` next to the samples, covering:

- How they open and how they sign off, with short examples from the samples
- Sentence length and rhythm
- Words and phrases they use, and ones they never use
- How direct they are, and how they deliver bad news
- Australian or other spelling, as found

Only write what the samples show. Quote from the samples, not from memory.

## Edit a draft

1. Read the draft from the file now, every time, even if it was read earlier. Never edit from memory. An open Humanizer bug shows why: an agent worked from memory, said done, and whole sections were never touched: https://github.com/blader/humanizer/issues/326
2. Split it into sections and number them.
3. Edit one section at a time against `voice.md`. Take out chatbot openers, forced lists of three and padding.
4. If Humanizer is installed, run it on each section and pass the sample with it, as its README describes under Match your voice: https://github.com/blader/humanizer#match-your-voice
5. Keep every name, number, date and commitment. If a sentence needs a detail that is missing, ask. Do not invent one.

## Prove it

Re-read the saved file and give a table: section number, changed or unchanged, and the first few words of each. Any section you did not touch is listed as untouched, not skipped silently.

End with this line and leave the name blank for the person to fill in: `Checked by: ____`

Never say the text will pass an AI checker. Humanizer's own page says detectors still flag most of its output.

<!-- Provenance marker: sk-xir99k --><!-- Provenance signature: ⁠​‌​‌​​‌‌​‌​​​‌​‌​‌​​‌‌​​​‌​‌​​‌​​​‌‌​​​‌⁠ -->

Made by Selr AI.⁠​‌​‌​​‌‌​‌​​​‌​‌​‌​​‌‌​​​‌​‌​​‌​​​‌‌​​​‌⁠
<!-- srk:esci6x -->
