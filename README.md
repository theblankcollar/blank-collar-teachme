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
- **One setup tap, then flow.** Right at the start, one tappable question: should the AI use your personal context (memory, projects, prior conversations) to tailor every example, or keep it general with strong universal examples? Pick once and the rest of the session respects it.
- **Calibration in conversation.** Two quick questions about your level and how deep you want to go. Plain text, no buttons interrupting the start.
- **A map of the journey.** Before the first concept, you see the full path. Every layer, every part. Your brain stops worrying about what comes next because it can see the shape.
- **Tiny loops.** One concept, one pattern to remember, one checkpoint. Every checkpoint is a sentence, not a card. Type "next", "pause", "ask", or anything else.
- **Metaphors first.** Kitchen analogies, restaurant analogies, traffic analogies. The technical unpacking comes after the metaphor has taken hold.
- **Permission to pause.** "Brain full" is always a normal response. ADHD does well when stopping is normalized, not penalized.
- **Resume-friendly.** When you come back, the AI opens with the map, a quick recap, and asks where you want to start.
- **Whitepaper export, your way.** At the end of any session you can ask the AI to convert the whole thing into a polished, shareable whitepaper. Choose tailored (uses your context for examples), generalized (universal examples, ready to share with anyone), or both at once. Choose the system's clean default design or apply your own brandbook (colors, fonts, logo, tagline).

---

## Two modes for examples: pick one at the start

The first thing you tap when a session opens is the setup card. It has two options.

**Use my context.** Every metaphor, every "imagine you..." example, and every walked-through scenario draws from your actual world. Your projects, your work, things you've discussed before. Best when the topic connects to something you're already building or thinking about.

**Keep it general.** Universal references only. Kitchens, factories, post offices, generic small businesses. No mention of your specific situation. Best when learning a topic for its own sake or when you want neutral ground.

The choice locks for the whole session. You can switch when you come back next time.

---

## The whitepaper export

At the end of every session, after the consolidation summary, the final tap card includes one option that goes beyond saving and resuming: **turn this into a whitepaper**.

Pick it and you get a clean, editable document containing the cover, an intro, the map, every part written up with its concept and metaphor and pattern, an action section for the week, suggested next topics, and a closing line. Roughly 4 to 8 pages. Polished enough to share with a colleague who asked the same question, durable enough to revisit yourself in three months.

The export then asks you two independent questions, back to back. Content scope first, then design.

### Content scope: who's this whitepaper for?

This is the choice that decides how the examples read.

- **Tailored** — the whitepaper uses your memory and personal context. Examples reference your projects, company, prior work, and known situation. Best for personal reference, internal company use, or anyone who already shares your background. Reads like it was written for your team specifically.
- **Generalized** — personal context is stripped out and replaced with universal examples. Reads naturally for someone who has no idea who you are or what you do. Best for sharing publicly, with friends outside work, with new people, or anyone who lacks your context.
- **Both, two files** — produces two whitepapers in one go. One tailored version for keeping or sharing internally, one generalized version for sharing externally. Same teaching content, same map, same patterns, just two different example layers in two separate files.

Why this matters: the same topic almost always needs to land twice in real life. Once for you and your team, where everyone already knows the backstory. Once for everyone else, where nothing can be assumed. The "Both" option does both passes in one shot so you don't have to ask the AI to redo the document later.

This choice is independent of the setup choice you made at the start of the session. You can learn in **use my context** mode and still produce a generalized whitepaper to share. You can learn in **keep it general** mode and still produce a tailored version with your personal frame layered in.

### Design: system default or your own brandbook

After the content scope, you pick how the document looks.

- **System design.** Neutral, minimal, professional. No setup required, ready in one shot.
- **Your own brandbook.** Drop in a primary color, a font, a logo, and an optional tagline. The AI applies them to the cover, headings, and footer. If you have a brand guide PDF, paste it in and the AI extracts what it needs.

When you choose "Both" for content, the same design is applied to both files unless you explicitly ask for different treatments. Most people want consistent visual identity across the internal and external versions.

### Output

The output file is a Word document by default (editable, shareable, easy to print to PDF). If your environment only supports PDF or markdown, the AI falls back gracefully. Iterations are free: ask for changes and the AI regenerates. If you got two files, you can ask the AI to update just one of them.

This turns every learning session into something that lives past the chat window, and lets you serve two audiences from one session.

---

## Who this is for

- Adults with ADHD who learn slowly but retain deeply
- Beginners in any technical field who keep bouncing off intro material
- Pattern recognition learners who need the whole map before details land
- Anyone who has ever said "explain it like I'm five" and meant it
- Founders, operators, and creators who want to actually understand the systems they use, not just chat their way through them
- Teams who want one person's learning to compound across the org through shared whitepapers
- People who often need to explain the same thing to two audiences (their team and the outside world) and don't want to write the doc twice

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
git clone https://github.com/theblankcollar/blank-collar-teachme.git ~/.claude/skills/blank-collar-teachme
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

A note on the whitepaper export: it works best in environments where the assistant can produce files directly (Claude Desktop, Claude Code, ChatGPT with file output enabled). In assistants that can't write files, the AI falls back to producing clean markdown that you can save and convert yourself.

---

## What a session actually looks like

Real example. User says: *"teach me APIs, I keep hearing about them and getting lost."*

The AI responds with one tap card right at the start:

```
[Quick setup before we start]
- Use my context (tailor examples to your actual projects)
- Keep it general (universal examples, no personal context)
```

After you tap, the AI asks two things in plain text:

> Two quick things before I lay out the map:
> Where would you put yourself with code in general, total beginner, can read but not write, or write code daily?
> And how deep do you want to go, just enough to follow conversations, enough to use one in a project, or full mental model?

You type a short answer. Then the AI shows the map:

```
[ ] Part 1: The restaurant metaphor
[ ] Part 2: What an API actually is, technically
[ ] Part 3: How requests and responses work
[ ] Part 4: Authentication and keys
[ ] Part 5: Try one for real
```

Then it teaches Part 1, drops a pattern to remember, and offers a checkpoint as a sentence:

> Pattern: An API is a waiter. You don't talk to the kitchen. You talk to the waiter.

> Solid? Say "next" for Part 2, or ask anything that didn't land.

You type back. The AI continues. No tap cards interrupt the flow. The vibe is conversation, not a form.

After a few parts, the AI checks pace in one line:

> We've covered three parts. Energy still good, or want to wrap here? Either is fine.

When the session reaches a clean stopping point, the AI consolidates:

```
[X] Part 1: The restaurant metaphor
[X] Part 2: What an API actually is, technically
[X] Part 3: How requests and responses work
[ ] Part 4: Authentication and keys
[ ] Part 5: Try one for real

Summary: APIs are waiters between two systems. You send a request,
you get a response, and the format is always predictable. Most APIs
speak JSON over HTTP. The hard part is usually authentication and
reading docs, not the concept itself.

Tiny thing this week: pick one API doc page and read it just for
shape, not to use it.
```

And the cards come back, briefly:

```
[What now?]
- Save a memory note so we can resume cleanly
- Move on to Part 4
- Just wrap up, no save
- Turn this session into a whitepaper
```

If you pick the whitepaper, two more cards in sequence:

```
[Who's this whitepaper for?]
- Tailored to me / my company
- General, shareable with anyone
- Both, give me two files
```

```
[How should it look?]
- Use the system design
- Use my own brandbook
```

If you picked "Both" and "Use my own brandbook", the AI then asks (in conversation) for your brand colors, font, logo, and tagline, and generates two files. If you picked simpler options, it generates the document or documents straight away. You get a Word file (or two) back. Done.

That's the full pattern. One setup card at the start, full flow in the middle, cards return only at the end, and you walk away with something you can keep, share, or both.

---

## Why this style

ADHD brains and beginner brains share two traits:

1. **They lose information fast when overwhelmed.**
2. **They retain deeply when concepts arrive in the right shape.**

Most tutorials optimize for completeness. This system optimizes for landing. A concept that lands once and sticks is worth ten concepts that wash over you.

The pacing rules, the metaphors, the maps, the conversational checkpoints, the explicit permission to pause, all exist to lower the cost of learning so you actually finish. The whitepaper export, in tailored or generalized or dual form, exists to make sure that what you finished doesn't evaporate the next day, and that you can hand it to whoever else needs it.

---

## Customizing it

The system is yours once you install it. Common edits people make:

- **Change the example metaphors** to match your industry or hobbies
- **Add a "speak to me in [language]" instruction** at the top of the body
- **Adjust pacing** if you want fewer or more pace checks
- **Add a banned words list** if the AI uses phrases you don't like
- **Pre-load a brandbook** in the file itself if you always want whitepapers in your colors, so the AI skips the design card
- **Default the content scope** if you always want tailored or always want generalized, so the AI skips that card too

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

> Based on Blank Collar Teachme by Kristian Kabashi. https://github.com/theblankcollar/blank-collar-teachme

That's it. No payment, no permission requests, no other strings. Just the credit.

See `LICENSE` for the full text.

---

## Contributing

Found a teaching style improvement? A pacing rule that should be added? A scenario the system handles badly? A whitepaper layout that works better than the default? Open an issue or a pull request.

Especially welcome:
- More example scenarios for the README
- Translations of `SKILL.md` into other languages
- Tweaks for specific neurodivergence profiles beyond ADHD
- Examples of teaching outputs in different domains
- Whitepaper template variations
- Confirmation reports of which AI assistants this works well with

---

## Credits

Made by [Kristian Kabashi](https://www.linkedin.com/in/kabashi).
Inspired by everyone who ever felt slow and wasn't.
