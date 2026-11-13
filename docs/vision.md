# Vision

> **Status:** Agreed for now (2026-11-12). This is the first doc to read. Every other design doc should support it.

## Pitch

The Wheel is a two-player digital card game about history. Each player leads a stronghold at one end of a hex-grid battlefield. They field armies led by historical figures, call on historical events, tactics, and landmarks, and try to destroy the enemy stronghold.

It combines a traditional trading card game (deckbuilding, hand management, instant-speed responses) with a turn-based tactics game (moving units across terrain, positioning, and combat). The point is to restage history's most dramatic conflicts and play out "what if" matchups between legends from different eras and regions.

## Player fantasy

- **Clever:** finding interactions between cards, troop types, and terrain that the opponent didn't see coming.
- **Powerful:** outplaying the opponent through better decisions, positioning, and hidden information.
- **Excited:** opening a rare card, or getting a lucky roll that saves the game, as an occasional highlight rather than the usual way games are won.

## Design pillars

These are ranked. When two of them conflict, the higher one wins.

1. **Skill decides, luck thrills.** Randomness creates memorable moments but should rarely decide a game on its own. The target is about MTG or Pokémon levels of variance. Avoid Hearthstone-style random effects and Yu-Gi-Oh-style games decided on turn 1.
2. **Legends, grounded in history.** Figures are heroic and larger than life, but each ability traces back to what they really did or stood for. For example, Joan of Arc can draw on her sainthood, but she doesn't get an unrelated gold bonus.
3. **Cards and board are one puzzle.** The best plays combine both layers. Neither one should feel like a side game.
4. **Easy to learn, deep to master.** Middle schoolers can play competently and win with practice. High schoolers can master it. Deep synergies can stay hidden until players go looking for them.
5. **Built to expand.** Rules, data, and content structure stay open to new sets, eras, and mythology. Prototype shortcuts are allowed but must be labeled `PROTOTYPE:`.

## Target experience

- **Match length:** about 1 hour as the target, where shorter is better as long as the depth survives. Close or complex games can run up to about 2 hours.
- **Pacing:** early turns are quick and simple. Complexity and tension build as armies make contact, peaking in a climax that produces a clear winner, after which a player may concede. Aggro decks speed matches up and control decks slow them down.
- **Depth:** on par with Magic: The Gathering, plus a chess-like positional layer.

## Tone and art direction

- **Style:** history told as heroic fantasy, in the vein of Dynasty Warriors, Romance of the Three Kingdoms, and Fire Emblem. Figures should feel mythic, but still like people who really lived.
- **Villains:** infamous figures are still stylized as larger than life, with dark or sinister symbolism. Dong Zhuo as the gluttonous tyrant is the model.
- **Later eras:** the style can shift for modern history toward semi-realistic, fantastical takes on historical hardware and icons, like Kantai Collection or Azur Lane, without breaking from the core look.
- **Quality bar:** a small indie studio.

## Content scope

- **Who can be a card:** any historically or culturally significant person, event, tactic, place, or artifact. That includes infamous figures.
- **Only firm exclusion:** people who are still alive.
- **Depicting Muhammad:** use symbolic art only, never a human likeness.
- **Legendary and mythic figures** (Robin Hood, Beowulf, Zeus, Nezha) are welcome in later sets but not the core set.
- **Core set:** premodern history. A modern expansion covering the World Wars and the Cold War is a likely later step.
- **Approval:** the project owner reviews all cards and art.

## Audience and platform

- **Players:** competitive and semi-competitive casual players who like cerebral games such as MTG and Fire Emblem.
- **Platform:** desktop first. Mobile or physical versions are possible later but aren't design drivers yet.

## Scope and business model

- **Roadmap:** playable prototype first, then a small playable release, then possibly a larger release. Design for growth without counting on it.
- **Content model:** one core set, followed by expansion sets.
- **Monetization:** free to play with optional card packs, like Hearthstone or Shadowverse. This is deferred until the game is playable and reasonably polished.
- **Team:** one human (the project owner) working with AI agents.

## Not decided here

Open design problems are tracked in [open-questions.md](open-questions.md), and the title is still a placeholder (OQ-08).
