# Feynman × Blurting

Learn a lecture by recalling it, not rereading it. You write down everything you remember, the AI checks it against your own lecture material, explains your gaps simply, and you teach them back.

## How a session works

1. **Blurt.** Close your notes and write down everything you remember about the lecture, as if explaining it to a classmate who missed it. Mark anything you're unsure about with "?".
2. **Check.** The AI compares your blurt with your material: what's solid, what's vague, what's wrong (with the page or slide where the correct version is), and what's missing.
3. **Feynman loop.** For your most important gaps, the AI explains each one in plain words with an example and an analogy. Then you explain it back in your own words until it holds.
4. **Gap sheet.** You get a short list of what to review, the misconceptions you fixed, questions for next time, and the date for your next round.

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

An excerpt from a session on a (made-up) lecture about gradient descent:

> **Coverage:** You recalled 5 of 8 core concepts (plus 3 supporting details).
>
> **Solid**
> - Gradient descent moves the parameters step by step in the direction that lowers the loss.
>
> **Incorrect**
> - "A bigger learning rate always converges faster" → too large a learning rate can overshoot and diverge (slide 14). *confident*
>
> **Missing**
> - Local vs. global minima (slide 18)
> - Stochastic vs. batch gradient descent (slides 20–22)

## Good to know

- Go through the lecture once before you blurt. Blurting tests your memory, it can't create it.
- One lecture or chapter per session works best.
- Your material stays in your chat. This skill doesn't store or upload anything.
