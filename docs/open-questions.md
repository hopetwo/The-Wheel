# Open Questions

A living list of unresolved design questions. A question is only marked resolved once the project owner agrees. When that happens, move it to **Resolved** along with where the answer now lives.

Priority levels:

- **P1** blocks the prototype.
- **P2** must be answered before content production.
- **P3** can wait.

## Active

### OQ-01: Board size vs. match length (P1)
The strongholds are about 14 hexes apart on a 16x16 map. Infantry moves 1 hex per turn, so it takes them more than 12 turns just to make contact, while matches are meant to run about an hour. Map size, starting positions, and movement values probably need to be tuned together.

### OQ-02: Resource model complexity (P1)
There are four resources (Food, Gold, Horses, Ordnance), and players also choose how many troops go into each unit. That's a lot of bookkeeping for younger players and for the time target. What job does each resource do that the others can't? How is income determined?

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

## Resolved

None yet.
