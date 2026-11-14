# The Wheel: Design Docs

> "The Wheel" is a placeholder title. See OQ-08 in [open-questions.md](open-questions.md).

This folder holds the design documentation for The Wheel, a two-player digital card game about history. Players build decks of historical leaders, events, tactics, and landmarks, then fight on a hex-grid battlefield to destroy each other's stronghold.

These docs are **clear enough to build from, but not final**. Expect them to change as prototyping teaches us things.

## How to read these docs

- Start with [vision.md](vision.md). It explains what the game is trying to be, and every other doc follows from it.
- Check [open-questions.md](open-questions.md) before you build anything that depends on an unsettled decision.
- On a conflict, a more specific doc beats a more general one, and an open question means the answer isn't decided yet.
- Anything marked `PROTOTYPE:` is a temporary choice, made only to unblock early development. Replace it before release.

## Index

| Doc | Status | What it covers |
| --- | --- | --- |
| [vision.md](vision.md) | Agreed | Pitch, design pillars, target experience, tone, and scope |
| [economy.md](economy.md) | Draft | Resources, income, capture points, costs, and fielding limits |
| [open-questions.md](open-questions.md) | Living | Unresolved design questions, in priority order |

## Conventions

- Use one focused topic per file, with lowercase-hyphenated file names.
- Write short sections, link to other docs instead of repeating them, and explain the reason behind each rule.
- Whenever you add or retire a doc, update this index.
