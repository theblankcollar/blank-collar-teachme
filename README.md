# Blank Collar Teachme

A guided, interactive teaching skill for AI assistants. Designed for adults with ADHD or anyone who learns better through metaphor, small loops, and explicit pacing.

## What this skill does

When installed, this skill changes how an AI assistant teaches. Instead of dumping long explanations, it does the things good human tutors do:

- Calibrates first (asks what you already know)
- Lays out a map of the whole topic before starting
- Teaches in small loops with checkpoints between each one
- Leads with metaphor, then unpacks the technical reality
- Compresses each idea into a one-line pattern you can remember
- Researches the current state of fast-moving topics before teaching, so it doesn't teach outdated information confidently
- Lets you pause without making it weird

It works for any topic. Tech, business, frameworks, languages, history, music theory, anything.

## Who this is for

People who:

- Lose interest fast when explanations get long, abstract, or assume prior knowledge
- Learn better when ideas are anchored in concrete metaphors before the technical detail
- Want a tutor that respects pacing and pauses without judgment
- Are tired of AI assistants that pattern-match to "be helpful" by overwhelming the user

If long uninterrupted walls of explanation make your eyes glaze over, this skill exists for you.

## Installation

This skill is distributed as a standard skill folder. Place the contents of this repository in the appropriate skills directory for your AI assistant.

For most setups that means dropping the folder into a `skills/` directory at user level or project level, depending on whether you want it available everywhere or only in specific projects.

The SKILL.md file contains the complete teaching protocol. Your AI assistant reads it when triggered.

## When the skill triggers

Phrases like:

- "Teach me X"
- "Explain X to me"
- "I want to learn X"
- "Help me understand X"
- "Walk me through X"
- "What is X really"
- "I'm a beginner at X"

It does **not** trigger on factual one-shot questions ("what's the capital of Albania") or deliverable requests ("write me a doc about X"). Those have their own right answers.

## The teaching style, briefly

Ten rules govern how the skill behaves. The full list lives in SKILL.md. The compressed version:

1. Always calibrate before teaching
2. Show the map before the journey
3. One concept per loop, then a checkpoint
4. Metaphor first, then unpack
5. Patterns over definitions
6. Always offer "pause" as a tap option
7. Use examples from the user's actual world when possible
8. No em dashes, no hyphens in compound modifiers
9. Pace check every few loops
10. End with consolidation

## Why these rules exist

They exist because they work. Each one is the answer to a specific failure mode of AI tutors: walls of text, missing context, no calibration, abstract jargon, no exit ramp.

Skip a rule and the failure mode comes back.

## Contributing

This is a skill. The shape is small on purpose. If you have a teaching pattern that consistently works for adults with ADHD or similar attention profiles, open an issue or a pull request.

Keep changes small. Keep the language plain. Keep the metaphors concrete.

## License

See LICENSE. Permissive use with attribution required.

## A note on style

You'll notice this README and the SKILL.md don't use em dashes or hyphenated compound modifiers. That's deliberate. It matches the rule the skill itself enforces.
