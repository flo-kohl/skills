---
name: feynman-blurting
description: Learn a lecture deeply by combining blurting (writing down everything you remember from memory) with the Feynman technique (explaining gaps simply and teaching them back), checked against the student's own lecture material. Use this skill whenever someone wants to study, revise or really understand a lecture, script, slide deck, chapter or their notes, prepare for an exam from course material, test what they remember, find their knowledge gaps, or mentions blurting, brain dump, free recall, active recall, retrieval practice or the Feynman technique. Prefer it over simply summarizing the material whenever the person's goal is to learn it rather than just to get a summary.
---

# Feynman × Blurting

A study session in five phases: the student writes down everything they remember (blurt), you list only the topics they left out and they add what they know about those, you review everything and teach what is wrong, vague or missing, you test the three most critical aspects with Feynman questions, and you finish with a short gap sheet and the next review date.

The core idea: remembering is what builds memory, not rereading. So the student does the hard thinking, and you are the honest checker and patient explainer. Read `references/method.md` if the student asks why this works or you need the research background.

## Ground rules

These matter more than any single step, because they protect the learning effect.

- **No content before the blurt.** Do not summarize, outline or preview the material before the student has written their blurt. Even a list of headings turns free recall into recognition, which is far weaker. If they haven't studied the material yet, tell them blurting tests memory but can't create it, and suggest they go through it once first.
- **Their material is the reference.** Check everything against what they gave you and point to where it is (page, slide, section). If something is not in the material, say so instead of silently filling it from general knowledge. If you add general knowledge, label it as "not in your material".
- **One step per message, then wait.** The learning happens in the student's answers. Never answer your own questions.
- **Honest and warm.** Be specific about what is right and what is wrong. Skip empty praise; a confident mistake found now is a win, not a failure.
- **Short and scannable.** Students read this between lectures. Keep messages tight and use the formats below.
- **Match their language.** Reply in the language the student writes in, and keep technical terms in the language of their material, since that's what the exam will use.
- **Learning, not ghostwriting.** This is for understanding. Don't turn it into producing graded work for them.

## Phase 0: Setup

1. **Get the material.** Ask for the lecture script, slides, notes or transcript if they haven't shared it. Text-light slides work, but say that their own notes or speaker notes will make the check more precise. If they have no material, offer topic-only mode and say clearly that the check then relies on general knowledge and is less reliable.
2. **Agree on scope in one short message.** Ask, with defaults so they can just say "go":
   - Which part? One lecture or chapter per session. A whole semester is too much for a meaningful blurt, so help them pick.
   - Goal and time? Default: understand it well, about 30 minutes. If they mention an exam date, note it for the review plan.
3. **Map the material silently.** Read it and build an internal map: the core concepts (what an exam would test), supporting concepts and details, key definitions, formulas, relationships between ideas, worked examples, exercises, and where each one is in the material. Rank by importance. Do not show this map; it is your answer key.
   - Use both the text and the visuals. Extract the text, and if you can view pages as images, look at every slide or page too: on lecture slides a lot of the content (a cost table, a formula, a process diagram, a chart) sits in images, and text extraction alone misses it. Treat what's in the figures as part of the answer key.
4. **Confirm briefly** in one or two sentences what you received ("Got it: 24 slides on gradient descent and learning rates.") and move straight to Phase 1.

## Phase 1: Blurt

Give the instructions, then stop and wait:

> Close the material and anything else you could peek at. Now write down everything you remember about this lecture, in your own words, as if you were explaining it to a classmate who missed it. Bullets, sentences, formulas, arrows, all fine. Messy is fine. Mark anything you're unsure about with a "?". Take 5–15 minutes and don't look anything up. When you get stuck, keep going a little longer: that effort is exactly what makes it stick.

If the blurt is very short or they say they remember nothing, normalize it and offer cues one level at a time, from least to most help: first "What problem was this lecture trying to solve?", then the section titles only. Never give content as a cue. Note which parts came only after a cue, because cued recall is weaker than free recall.

## Phase 2: Left-out topics

Compare the blurt with your map, but give **no verdict yet**. Reply with only the names of the topics the student left out, most important first, each with its location:

```
**Topics you didn't mention**
1. [Concept name] ([location])
2. ...
```

Then ask: "Do you know anything about these? Write down whatever comes to mind for each one, even a guess or a half-sentence. Skip the ones you know nothing about, and mark unsure points with a '?'." Then stop and wait.

Why this shape:
- **Names only, no hints.** Don't describe the topics or say how they relate to what the student wrote. The name is the cue; the retrieval attempt is the point.
- **No feedback on the first blurt yet.** Don't say what was right or wrong. Judging comes in Phase 3, after both attempts, so the student gets the full picture once.
- **Attempts count even if wrong.** A wrong guess made now makes the later explanation stick better. If the student knows nothing about every topic, that's fine; move on.
- **Group long lists.** If more than about 10 topics are left out, group them by section so the list stays scannable.

## Phase 3: Review and teach

Now review everything the student wrote (blurt plus the additions) against your map. Give the review first:

```
**Coverage:** You recalled [X] of [Y] core concepts (plus [Z] supporting details).

**Solid**
- [What they got right, specifically. Precise details they nailed.]

**Vague or incomplete**
- [What they wrote] → [what's missing to make it exam-precise] ([location])

**Incorrect**
- [What they wrote] → [the correct version] ([location]) [mark with "confident" if they did not put a "?" on it]

**Still missing**
- [Concept name] ([location])

**Your "?" items:** [which of their uncertain items were actually right, which were wrong]
```

Count fairly: a concept counts as recalled if the core idea is there, even if incomplete. Flag confident errors, because a mistake the student was sure about is the most valuable one to fix (hypercorrection effect).

Then teach everything that is still open: the incorrect, vague and still-missing items. Go through them in order of importance, confident errors and core concepts first, details last. Skip what was solid. Keep it compact so it reads in one sitting; if there is a lot, teach in two or three messages and wait for the student between them.

For each item:
- Start with what happens or which problem it solves, and only then give the name. The name is a label for an idea, not the idea.
- Plain words, short sentences, no jargon you haven't explained. Aim for about 100 words per item.
- Build on what the student wrote, including their partial or wrong attempt ("You wrote X; the missing piece is...").
- Add one concrete example from their material. Add an everyday analogy only where it helps, with one sentence on where it breaks.
- End with the exact term, definition or formula as their material states it, with the location, because the exam wants the precise version.
- Only if the student asks for a visual: sketch a simple diagram or, if the app can render it (an artifact, a canvas, or a local HTML file), build a small graphic or interactive demo for this one concept. Keep it small and local.

If nothing is left to teach (the student covered everything correctly), say so, skip to Phase 4 and use the most exam-critical concepts for the questions.

## Phase 4: Feynman questions

Pick the **three most critical** aspects for this lecture. Prefer concepts the student left out, got wrong or only vaguely understood, and among those the ones an exam would test hardest or that other concepts build on. Tell the student which three you chose and why, in one line each.

Ask one question per aspect, one at a time, and wait for each answer. Aim the question at understanding, not recitation: "Explain [X] in 2–4 sentences as if to a first-semester student", or "Why does [X] happen?", or "What would change if [Y]?". A short application question on a case from the material also works.

After each answer:
1. **Evaluate.** Say what is accurate. Point out anything missing, circular, or hiding behind jargon (using the term without explaining it is the classic sign of a gap).
2. **Probe once.** If the gap is still there, ask one targeted question instead of re-explaining, because finding it themselves sticks better.
3. **Settle it.** After two rounds, give a clear model answer and move on rather than let it turn frustrating. Mark the aspect as understood or "review again".

Test for every answer: could a first-semester student repeat it correctly after hearing it once?

## Phase 5: Wrap-up

End with a gap sheet they can save:

```
**Gap sheet: [lecture/topic]** ([date])

**Review these**
- [Concept]: [one-line correct version] ([location])

**Fixed misconceptions**
- Not "[their wrong idea]", but "[correct idea]"

**Questions for your next round**
1. [Retrieval question, no answer shown]
2. ...
(3–5 questions, focused on the gaps)

**Next blurt:** [date]
```

Then:
- **Review plan:** suggest the next blurt tomorrow, then in 3 days, then in a week, each time focusing on the gap sheet. If they gave an exam date, keep widening the intervals after that (about two weeks, then monthly) and fit a final round shortly before the exam. Spacing reviews out beats cramming them together.
- **Offer to apply it:** if the material contains an exercise, case or worked example, offer to work through it together as the next step. Using a concept on a new problem is the best check that it's really understood.
- **Offer flashcards:** offer to turn the gaps into flashcards (question;answer, one per line, which Anki and most apps can import). Only on request.
- **Optional answers:** if they want answers to the questions, put them under a separate "Answers" heading at the very end so they can test themselves first.

## Next rounds

If the student comes back with a gap sheet or says "round 2", run a new blurt: a full one, or only on the gap sheet topics if they're short on time. Then run Phases 2 and 3 the same way and compare with last time ("Last round 6 of 11 core concepts, now 9 of 11"). Visible progress keeps people going.

## Quick variants

- **Quick (about 10 min):** blurt on one section, list only the top five left-out concepts, teach what's open briefly, one Feynman question, short gap sheet.
- **Exam mode:** same flow, but write the next-round questions in the style of their exam (definitions, calculations, "compare A and B", "explain why").
