# Feynman × Blurting

Learn a lecture by recalling it, not rereading it. You write down everything you remember, the AI lists what you left out, you add what you know about it, then it reviews everything against your own lecture material, teaches what's missing or wrong, and quizzes you on the three most critical points.

## How a session works

1. **Blurt.** Close your notes and write down everything you remember about the lecture, as if explaining it to a classmate who missed it. Mark anything you're unsure about with "?".
2. **Left-out topics.** The AI lists only the names of the topics you didn't mention. You write down whatever you know about them, even a guess.
3. **Review and teach.** The AI reviews everything you wrote against your material: what's solid, vague, wrong (with the page or slide of the correct version) or still missing. Then it teaches you what's open, in plain words with examples.
4. **Feynman questions.** For the three most critical aspects, the AI asks you to explain or apply them in your own words, and probes until they hold.
5. **Gap sheet.** You get a short list of what to review, the misconceptions you fixed, questions for next time, and the date for your next round.

Why this works, with the research behind it: [references/method.md](references/method.md).

## Use it

| Where | How |
|---|---|
| **Claude Code** | `/plugin marketplace add flo-kohl/skills`, then `/plugin install study@flo-kohl-skills`. Point it to your material and say "let's do a blurting session on this lecture". |
| **Claude.ai / Claude app** | Download this `feynman-blurting` folder as a ZIP and upload it under Settings → Capabilities → Skills. Then attach your material in any chat and ask for a blurting session. No skills on your plan? Use the prompt below. |
| **ChatGPT** | Paste the prompt from [PROMPT.md](PROMPT.md) into a new chat and attach your material. To reuse it, create a custom GPT and put the prompt in its instructions. |
| **Gemini** | Paste the prompt from [PROMPT.md](PROMPT.md) into a new chat and attach your material. To reuse it, create a Gem with the prompt as its instructions. |
| **Any other chatbot** | Paste the prompt from [PROMPT.md](PROMPT.md) and attach or paste your material. |

Works best with a model that can read PDFs including images, since slides often hold content in figures and tables.

## What a check looks like

An excerpt from the review step of a session on a (made-up) lecture about gradient descent:

> **Coverage:** You recalled 5 of 8 core concepts (plus 3 supporting details).
>
> **Solid**
> - Gradient descent moves the parameters step by step in the direction that lowers the loss.
>
> **Incorrect**
> - "A bigger learning rate always converges faster" → too large a learning rate can overshoot and diverge (slide 14). *confident*
>
> **Still missing** (after your second pass on the left-out topics)
> - Stochastic vs. batch gradient descent (slides 20–22)

## Good to know

- Go through the lecture once before you blurt. Blurting tests your memory, it can't create it.
- One lecture or chapter per session works best.
- Your material stays in your chat. This skill doesn't store or upload anything.
