# AI course authoring guide

This public repository is a **source-led Italian course**, maintained in small verified updates.

## Scope: exactly two sources

1. *Nuovo Espresso 1*: primary A1 textbook, ten lessons; main course/reviews through p. 144, exercises begin at p. 145. The selected source **Nuovo_Espresso_1.pdf** has **239 pages**; its exercise section begins on p. 145. An alternate scan named *Nuovo_Espresso_1(2).pdf* has **150 pages** and is truncated during the exercise section.
2. *Nuovo Espresso 1 Glossario*: Italian–Persian glossary, 65 pages, organized by matching lessons.

Do not incorporate any other textbook or invent supplementary page mappings. The glossary is a reference, not permission to reproduce its full contents.

## Incremental publishing

- Edit **one lesson at a time**. Inspect its actual textbook and glossary pages before adding claims or detailed source references.
- Main navigation: `README.md` → `a1/README.md` → `a1/lesson-NN/lesson.md`.
- Lezioni 1–7 have exactly four files each; Lezioni 8–10 remain drafts. Each migrated lesson has exactly four files: `lesson.md`, `grammar.md`, `vocabulary.md`, and `exercise.md`. Keep related topics together and link all four from `lesson.md`.
- Migrate and verify only **one lesson at a time**; unmigrated chapters remain draft files.
- **Lesson 2 covers PDF pp. 17–32**, including **Facciamo il punto 1** on pp. 30–32; include end-of-unit review pages in source maps rather than treating them as unrelated to the lesson.
- Keep the lesson **self-contained**: book pages, communication goals, grammar, selective vocabulary, short original examples, practice with collapsible solutions, speaking task and next-step link.
- Lessons not yet fully examined are **drafts**. Do not present them as finished or mastered.
- Publish small, original summaries and examples; do not copy source pages, publisher exercises, large glossary tables, video/audio or exam papers.
- Verify committed links and GitHub readback after each update.

## Lesson 3 page boundary

- When users describe Lesson 3 as PDF **pp. 33–47**, include p. 47 in the source map as a **transition**: Lesson 3 itself occupies **pp. 33–46** and p. 47 opens **Lezione 4 — Tempo libero**.
- Lesson 3 vocabulary is drawn from the glossary's **Lezione 3**, approximately PDF pp. **17–25**, with boundaries shared by adjacent chapters.

## Lessons 4 and 5 page boundaries

- Lesson 4 requested PDF pp. **47–59**; **Tempo libero** itself runs pp. **47–58**, and p. **59** opens Lesson 5.
- Lesson 5 requested PDF pp. **59–75**; **In albergo** itself runs pp. **59–71**, **Facciamo il punto 2** is on pp. **72–74**, and p. **75** opens Lesson 6.
- Keep review pages visibly mapped and don't confuse them with a new chapter.

## Lesson 6 and 7 boundaries

- Lesson 6 requested pages **75–89**: the unit is **75–88** and p. **89** opens Lesson 7. Supplementary **Esercizi 6** begins on p. **174** in the longer scan.
- Lesson 7 requested pages **89–105**: the unit is **89–101**, **Facciamo il punto 3** is **102–104**, and p. **105** opens Lesson 8. Supplementary **Esercizi 7** begins on p. **180**.
- Base picture-referencing practice on the actual source pictures, but don't redistribute publisher artwork in this public repo. Use verified freely reusable Commons photographs plus credits for independently displayed images.

## Memory and recall teaching standard

For grammar and vocabulary add a concise **Remember it** section per lesson:
- Prefer **clear, recognizable real photographs** for concrete vocabulary and real-world situations. Select files whose licenses permit redistribution/reuse (e.g. Wikimedia Commons), and record author, license, original file and modifications in `a1/PHOTO_CREDITS.md`.
- Do not use abstract icons/SVG object grids as vocabulary images when an appropriate real photograph is available. Do not imply a real portrait depicts a named fictional person or that an intact hotel room has a visible defect.
- Match picture-based exercises and answer keys to **what the selected photos visibly contain**; remove outdated numbering when replacing graphics.
- Grammar, spelling and number-form rules should use accurate text/tables; a contextual photo is not evidence of a rule.
- Prioritize a **real, correctly matched, openly licensed online photograph** in a compact thumbnail for **each concrete vocabulary word**; use an **emoji only as a fallback** when no suitable reusable photograph can be found, particularly for abstract concepts. Add a visual beside **every core vocabulary term** in each Italian–English–Persian vocabulary table, without sacrificing the example sentence, attribution, or narrow-screen readability. Explain that the cue is a mnemonic rather than the term's exact meaning.
- Build vocabulary practice as picture → Italian chunk → complete sentence → question/answer → short dialogue.
- Explicitly label **English bridges** as explanations and name where literal translation misleads (for example, Italian `ho ... anni` versus English “I am ... years old”).
- Separate a **mnemonic** from an actual grammar rule; note useful exceptions and false friends.
- Add active recall with answers that remain hidden until attempted; interleave past content and suggest adjustable spaced retrieval.
- Call reading aloud **read-aloud/repetition**, not *shadowing*, unless there is genuinely accessible recorded Italian audio for simultaneous imitation.
- Do not publish private learner work or publisher illustrations/audio.

## Privacy — mandatory

The repository is public. Never publish personal goals, dates, exam plans, learner level, scores, mistakes, answers, conversations, schedule or confidential details anywhere in repo content or commits. A private destination must be verified before saving individualized learning results.
