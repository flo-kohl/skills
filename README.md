# skills

AI skills that make you better at things that matter. Each one is built on a method that actually works and kept simple enough to use tomorrow.

The first domain is **studying**: skills that turn proven learning techniques (Feynman, blurting, active recall, spaced repetition) into something you can run on your own lecture material. More domains, like coding, may follow.

## Domains

| Domain | What's inside | Status |
|---|---|---|
| [study](study/) | Learning-science skills for students | 1 skill: [feynman-blurting](study/skills/feynman-blurting/) |

## How to use a skill

**Claude Code:** add this repo as a plugin marketplace, then install a domain:

```
/plugin marketplace add flo-kohl/skills
/plugin install study@flo-kohl-skills
```

**Claude.ai / Claude app:** download a skill's folder as a ZIP and upload it under Settings → Capabilities → Skills.

**ChatGPT, Gemini or any other chatbot:** every skill also ships as a plain prompt (`PROMPT.md` in the skill's folder). Paste it into a new chat, or save it as a custom GPT or Gem to reuse it.

## Principles

- **Method first.** Every skill is based on a learning or working technique with a track record, and says which one.
- **Your material is the source.** Skills work on what you give them (a lecture script, your notes) instead of inventing content.
- **You do the thinking.** The AI checks, explains and asks. It does not do the learning for you.

## Feedback

Found a bug, have an idea, or a technique you want as a skill? Open an issue.

## License

[MIT](LICENSE)
