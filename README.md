# Blank Collar Teachme

> A teaching system that finally meets your brain where it lives.

Built for people with ADHD, beginners who feel patronized by docs, and anyone who has ever closed a tutorial halfway through because it assumed too much, moved too fast, or felt like a wall of text.

This is the system I wished existed when I was learning. Now it does.

---

## What this is

A teaching prompt that reshapes how any capable AI tutor responds. You drop it into your AI assistant of choice, tell it what you want to learn, and the AI follows the system instead of defaulting to wall-of-text mode.

Works with Claude, ChatGPT, Gemini, Cursor, and most other modern AI assistants. The format is plain markdown with a YAML header, which any capable language model can read and follow.

No long lectures. No assumed knowledge. No "you should already know this."

Instead, you get:

- **Research first.** Before teaching anything that can change over time (products, tools, frameworks, markets), the AI checks current state automatically. No more learning yesterday's reality.
- **Calibration first.** Two or three quick questions before any teaching, so the AI understands where you actually are.
- **A map of the journey.** Before the first concept, you see the full path. Every layer, every part. Your brain stops worrying about what comes next because it can see the shape.
- **Tiny loops.** One concept, one pattern to remember, one checkpoint. Never more than that without asking how you're doing.
- **Metaphors first.** Kitchen analogies, restaurant analogies, traffic analogies. The technical unpacking comes after the metaphor has taken hold.
- **Permission to pause.** "Brain full" is always one of the options. ADHD does well when stopping is normalized, not penalized.
- **Resume-friendly.** When you come back, the AI opens with the map, a quick recap, and asks where you want to start.

---

## Who this is for

- Adults with ADHD who learn slowly but retain deeply
- Beginners in any technical field who keep bouncing off intro material
- Pattern recognition learners who need the whole map before details land
- Anyone who has ever said "explain it like I'm five" and meant it
- Founders, operators, and creators who want to actually understand the systems they use, not just chat their way through them

---

## What you can learn with it

Anything. The teaching style is the product. The topic adapts.

People have used variations of this approach to learn:

- AI agents, skills, MCPs, and the modern AI tooling stack
- Docker, Git, the terminal, Linux basics
- Python, JavaScript, web frameworks
- Cybersecurity concepts and compliance frameworks
- Startup finance: valuation, dilution, cap tables
- Music theory, languages, philosophy

If a topic exists, this system can teach it. The structure is universal.

---

## How to use it

The teaching system works with any capable AI assistant that can follow detailed instructions. Pick your platform.

### Claude (claude.ai, Claude Desktop, Claude Code)

For Claude Code or any Claude environment that supports skills:

```bash
git clone https://github.com/YOUR-USERNAME/blank-collar-teachme.git ~/.claude/skills/blank-collar-teachme
```

For Claude Desktop with Projects: open a Project, paste the contents of `SKILL.md` into the Project's custom instructions.

For claude.ai web: paste the contents of `SKILL.md` at the start of any fresh chat.

### ChatGPT

**As a Custom GPT (recommended):** create a new GPT, paste the contents of `SKILL.md` into the Instructions field, save. Now any conversation with that GPT follows the teaching system.

**As a one-off in any chat:** paste the contents of `SKILL.md` at the start of a fresh chat with this opener:

> The following is a teaching system I want you to follow for the rest of this conversation. After you read it, I'll tell you what I want to learn.

Then paste `SKILL.md`, then ask your learning question.

### Gemini

**As a Gem (recommended):** create a Gem in Gemini, paste `SKILL.md` into the instructions, save.

**As a one-off:** paste `SKILL.md` at the start of a fresh chat with the same opener as above.

### Cursor or other AI coding assistants

Paste `SKILL.md` into your custom rules, system prompt, or AGENTS.md file (depending on what your assistant supports).

### Any other AI assistant

If your AI of choice can read and follow detailed text instructions, it can use this system. Paste `SKILL.md` at the start of a conversation with the opener above. Most modern assistants will respect it.

---

## What a session actually looks like

Real example. User says: *"teach me APIs, I keep hearing about them and getting lost."*

The AI responds:

```
Good topic. Two quick calibration taps first.

[How comfortable are you with code in general?]
- I write code daily
- I can read code but not write it
- Almost no exposure
- What is code

[How deep do you want to go today?]
- Just enough to follow conversations about APIs
- Enough to use one in a project
- Full mental model, all the way down
```

After you answer, the AI shows the map:

```
[ ] Part 1: The restaurant metaphor
[ ] Part 2: What an API actually is, technically
[ ] Part 3: How requests and responses work
[ ] Part 4: Authentication and keys
[ ] Part 5: Try one for real
```

Then it teaches Part 1, drops a pattern to remember, and offers a checkpoint:

> Pattern: An API is a waiter. You don't talk to the kitchen. You talk to the waiter.

```
[How is this landing?]
- Got it, ready for Part 2
- One question first
- Explain that differently
- Pause, save for later
```

That's the whole pattern. Repeat for each Part. Stop whenever your brain says stop. Resume whenever you want.

---

## Why this style

ADHD brains and beginner brains share two traits:

1. **They lose information fast when overwhelmed.**
2. **They retain deeply when concepts arrive in the right shape.**

Most tutorials optimize for completeness. This system optimizes for landing. A concept that lands once and sticks is worth ten concepts that wash over you.

The pacing rules, the metaphors, the maps, the explicit permission to pause, all exist to lower the cost of learning so you actually finish.

---

## Customizing it

The system is yours once you install it. Common edits people make:

- **Change the example metaphors** to match your industry or hobbies
- **Add a "speak to me in [language]" instruction** at the top of the body
- **Adjust pacing** if you want fewer checkpoints or more
- **Add a banned words list** if the AI uses phrases you don't like

Edit `SKILL.md` directly. Your changes take effect on the next session.

---

## Installation paths summary

| Where you use AI | What to do |
|---|---|
| Claude Code | Clone into `~/.claude/skills/blank-collar-teachme` |
| Claude Desktop with Projects | Paste `SKILL.md` content into a Project's instructions |
| claude.ai web | Paste `SKILL.md` at the start of a fresh chat |
| ChatGPT Custom GPT | Paste `SKILL.md` into the GPT's Instructions |
| ChatGPT one-off | Paste `SKILL.md` at the start of a fresh chat |
| Gemini Gem | Paste `SKILL.md` into the Gem's instructions |
| Gemini one-off | Paste `SKILL.md` at the start of a fresh chat |
| Cursor / VS Code AI | Paste into custom rules or system prompt |
| Any other AI assistant | Paste `SKILL.md` at the start of a fresh chat |

---

## Origin

This system came out of frustration with chatting AI assistants to success instead of learning real foundations. While learning a new field from scratch with ADHD, the pattern that finally worked got captured here.

It's now a public artifact so other beginners can skip the trial and error.

Made as part of [The Blank Collar](https://theblankcollar.com), an AI transformation practice with one belief:

> Work is for bots. Life is for humans.

---

## License

Custom license: free to use with attribution.

You can use, modify, and redistribute this system for personal or commercial purposes. The only requirement: keep the credit visible.

When you share, fork, embed, or build on this system, include this line somewhere reasonable (a footer, a credits section, an "About" page, the README of your fork):

> Based on Blank Collar Teachme by Kristian Kabashi. https://github.com/YOUR-USERNAME/blank-collar-teachme

That's it. No payment, no permission requests, no other strings. Just the credit.

See `LICENSE` for the full text.

---

## Contributing

Found a teaching style improvement? A pacing rule that should be added? A scenario the system handles badly? Open an issue or a pull request.

Especially welcome:
- More example scenarios for the README
- Translations of `SKILL.md` into other languages
- Tweaks for specific neurodivergence profiles beyond ADHD
- Examples of teaching outputs in different domains
- Confirmation reports of which AI assistants this works well with

---

## Credits

Made by [Kristian Kabashi](https://www.linkedin.com/in/kabashi).
Inspired by everyone who ever felt slow and wasn't.
