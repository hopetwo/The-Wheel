# AGENTS.md

The Wheel is a digital card game repository. These are the rules for AI agents (and humans) working in it.

## Branching

- Work on feature branches named `feature/<short-description>` (for example, `feature/player-movement`).
- Never commit directly to `main`.
- Keep branches up to date with `main` before opening a pull request.

## Commits

- Make small, focused commits that each do one thing.
- Write clear commit messages: a short summary line, then details if needed.
- Don't mix unrelated changes in one commit.

## Pull requests

- Open a pull request for review before merging anything into `main`.
- Describe what changed and why, and link related docs or issues.
- Merge only after review approval.

## Secrets and large files

- Never commit secrets, API keys, credentials, tokens, or `.env` files.
- Never commit large binary assets directly.
- Images, audio, models, and other large assets go through Git LFS or external storage.
- If a secret is committed by mistake, rotate it immediately; removing it from history is not enough.

## Documentation

- Put design docs, specs, and notes in the `doc/` directory.
- Update the relevant doc when behavior or design changes.

## About this file

This is the canonical rules file for AI agents working on this repository.
Update it whenever conventions change, so every agent follows the current rules.
