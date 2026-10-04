---
name: feynman-blurting
description: Learn a lecture deeply by combining blurting (writing down everything you remember from memory) with the Feynman technique (explaining gaps simply and teaching them back), checked against the student's own lecture material. Use this skill whenever someone wants to study, revise or really understand a lecture, script, slide deck, chapter or their notes, prepare for an exam from course material, test what they remember, find their knowledge gaps, or mentions blurting, brain dump, free recall, active recall, retrieval practice or the Feynman technique. Prefer it over simply summarizing the material whenever the person's goal is to learn it rather than just to get a summary.
---

# Feynman × Blurting

A study session in four phases: the student writes down everything they remember (blurt), you check it against their material, you close the most important gaps with simple explanations they have to teach back (Feynman), and you finish with a short gap sheet and the next review date.

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

## Phase 2: Check

Compare the blurt with your map and reply in this format:

```
**Coverage:** You recalled [X] of [Y] core concepts (plus [Z] supporting details).

**Solid**
- [What they got right, specifically. Precise details they nailed.]

**Vague or incomplete**
- [What they wrote] → [what's missing to make it exam-precise] ([location])

**Incorrect**
- [What they wrote] → [the correct version] ([location]) [mark with "confident" if they did not put a "?" on it]

**Missing**
- [Concept name only, core concepts first] ([location])

**Your "?" items:** [which of their uncertain items were actually right, which were wrong]
```

Why this shape:
- **Count fairly.** A concept counts as recalled if the core idea is there, even if it's incomplete; list it under "Vague or incomplete" so the score stays honest without being harsh.
- **Missing items are names only.** The explaining happens in Phase 3, where the student works for it. A full explanation here would just be rereading.
- **Flag confident errors.** A mistake the student was sure about is the most valuable thing to fix. When corrected, these errors tend to be remembered especially well (the hypercorrection effect), and left alone they do the most damage in an exam.

Then propose the focus: pick up to three gaps, prioritizing confident errors and missing core concepts over details, and ask which to start with (default: the first).

## Phase 3: Feynman loop

Work through the chosen gaps one at a time. Three per session is plenty; more gets shallow. The student can always ask to continue.

1. **Try first.** For a missing concept, ask one quick question before explaining: "Before I explain: what do you think [X] is, or what is it for? A guess is fine." Attempting first, even wrongly, makes the explanation stick better. For an incorrect item they have already tried, so skip this.
2. **Explain simply.** Keep it under about 150 words:
   - Start with what happens or which problem it solves, and only then give the name. The name is a label for an idea, not the idea.
   - Plain words, short sentences, no jargon you haven't explained.
   - One concrete example, ideally from their material.
   - One everyday analogy, plus one sentence on where the analogy breaks, so they don't learn a wrong picture.
   - Anchor it to something they already got right in their blurt.
   - End with the exact term, definition or formula as their material states it, with the location, because the exam wants the precise version.
   - Only if the student asks for a visual: sketch a simple diagram or, if the app can render it (an artifact, a canvas, or a local HTML file), build a small graphic or interactive demo for this one concept. Keep it small and local, and still finish with the teach-back.
3. **Teach back.** "Now explain it back in 2–4 sentences in your own words, as if to a first-semester student." Then wait.
4. **Evaluate.** Say what is accurate. Point out anything missing, circular, or hiding behind jargon (using the term without explaining it is the classic sign of a gap). If the gap is still there, ask one targeted question instead of re-explaining, because finding it themselves sticks better. After two rounds, give a clear model answer and move on rather than let it turn frustrating.
5. **Close it.** Mark the gap as closed or "review again" and go to the next one.

Test for every explanation: could a first-semester student repeat it correctly after hearing it once?

## Phase 4: Wrap-up

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

If the student comes back with a gap sheet or says "round 2", run a new blurt: a full one, or only on the gap sheet topics if they're short on time. Then check it the same way and compare with last time ("Last round 6 of 11 core concepts, now 9 of 11"). Visible progress keeps people going.

## Quick variants

- **Quick (about 10 min):** blurt on one section, check only the top five core concepts, one Feynman gap, short gap sheet.
- **Exam mode:** same flow, but write the next-round questions in the style of their exam (definitions, calculations, "compare A and B", "explain why").
