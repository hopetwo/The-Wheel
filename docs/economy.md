# Economy

> **Status:** Draft (2026-11-14). The numbers are starting points for playtesting.
> Related: [vision.md](vision.md) | [open-questions.md](open-questions.md)

## Purpose

The economy decides what a player can afford each turn. It's designed so that **acting beats waiting**. Income comes from contested territory, and fielding is throttled, so a player can't win by hoarding and then dumping everything at once.

## Resources

| Resource | Gained by | Spent on |
| --- | --- | --- |
| Food | Base income, captured points, cards | Troops, card costs |
| Gold | Base income, captured points, cards | Troops, Horses, Ordnance, card costs |
| Horses | Buying with Gold | Cavalry troops, some card costs |
| Ordnance | Buying with Gold | Ranged troops, some card costs |

- **All resources stockpile.** Nothing resets at the end of a turn.
- Troops, Horses, and Ordnance are counted in units of **1,000**.

## Income

- **Base income:** each player gains `1 Gold + 1 Food` during their Income step. `PROTOTYPE:` this is an arbitrary starting value.
- **No starting stockpile.** On turn 1, a player's only resources are that turn's base income.
- **Income does not ramp up automatically.** Growth comes from captured points on the battlefield and from cards, mainly Landmarks and certain playstyles.

## Capture points

- The battlefield contains key points, such as villages, mines, and farmland, that grant resources or other bonuses.
- **Capturing:** move a unit onto the point.
- **Holding:** the point stays yours until an enemy unit moves onto it. You don't need to keep a unit there, but guarding a contested point stops the opponent from simply walking in.
- The specific point types, their yields, and how they're placed on the map are still undecided (see OQ-10).

## Costs

| Purchase | Cost |
| --- | --- |
| 1,000 infantry | 1 Gold + 1 Food |
| 1,000 cavalry | 1 Gold + 1 Food + 1,000 Horses |
| 1,000 ranged | 1 Gold + 1 Food + 1,000 Ordnance |
| 1,000 Horses | 1 Gold |
| 1,000 Ordnance | 1 Gold |

- A unit's size is any multiple of 1,000 troops.
- Horses and Ordnance are used up when the unit is created.
- Cards may also cost Food or Gold, and occasionally Horses or Ordnance.

## Fielding limits

- A player can field **one unit per turn**.
- New units must be placed on an empty hex **adjacent to the player's stronghold**.
- **Surround:** if all six hexes around a stronghold are held by enemy units, its owner can't field units. This isn't an instant loss, because units already out on the map can still fight. It's meant to put the defender in serious danger. For now there is no extra bonus for the attacker (see OQ-11).

## Design notes

- Contested income plus one unit per turn addresses the hoarding stalemate (OQ-09). That needs to be confirmed in playtesting.
- Board size stays at 16x16 for now. Faster movement is the first lever to pull if matches drag (OQ-01).
