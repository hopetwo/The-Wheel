# Open Questions

A living list of unresolved design questions. A question is only marked resolved once the project owner agrees. When that happens, move it to **Resolved** along with where the answer now lives.

Priority levels:

- **P1** blocks the prototype.
- **P2** must be answered before content production.
- **P3** can wait.

## Active

### OQ-01: Board size vs. match length (P1)
The strongholds are about 14 hexes apart on a 16x16 map. Infantry moves 1 hex per turn, so it takes them more than 12 turns just to make contact, while matches are meant to run about an hour. Map size, starting positions, and movement values probably need to be tuned together.

### OQ-02: Resource model complexity (P2)
Partly answered in [economy.md](economy.md). Troop counts come in steps of 1,000, and income comes from base income plus captured points. Whether juggling four resources is too much for younger players is still open and will be judged in playtesting.

### OQ-03: Sources of randomness and early-game reliability (P1)
The target is roughly MTG-level variance with no decisive turn-1 swings. Randomness currently comes from both card draws and combat dice. If every unit needs a Leader card, a hand with no Leaders can leave a player unable to act. That's the same kind of failure as mana screw in MTG.

### OQ-04: Deck identity (P1)
What splits the card pool, the way colors do in MTG? Options include civilizations, eras, regions, or nothing at all. The answer shapes deckbuilding rules, set structure, and art direction.

### OQ-05: Combat resolution (P1)
Combat uses dice (d20 or d100?) with crits and fumbles. Attacker and defender deal damage at the same time. It isn't settled how unit type, troop count, Leader, and Equipment feed into damage. A typical unit should die in one or two fights.

### OQ-06: Stronghold health and direct attacks (P2)
What is the starting stronghold HP? How does attacking the stronghold work, and can landmarks or effects defend or repair it?

### OQ-07: Leader lifecycle (P2)
What happens to a Leader card when its unit is destroyed? Can a Leader be reassigned, retreat, or come back?

### OQ-08: Final title (P3)
"The Wheel" is a placeholder. Candidates so far are The Weave, Chronicle, and Arc.

### OQ-09: Hoarding stalemate (P1)
Because resources stockpile and units must march a long way, passing and letting the opponent commit first can look like the best move. The current fix is contested income plus a one-unit-per-turn fielding limit (see [economy.md](economy.md)). It needs playtest confirmation.

### OQ-10: Capture point design (P1)
Which point types exist (village, mine, farmland, and so on)? What does each one yield, how many are on the map, and where are they placed?

### OQ-11: Surround consequences (P2)
Being surrounded blocks fielding. Should the surrounding player also get an attack bonus against the stronghold?

### OQ-12: Simultaneous turns (P1)
Should both players plan in secret and then resolve their moves at the same time, instead of alternating turns? This affects turn structure, Tactics, combat, and the surround rule.

## Resolved

None yet.
