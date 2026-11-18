# Turn Structure

Status: Draft · Last updated: 2026-11-15
Related: [economy.md](economy.md), [open-questions.md](open-questions.md)

## Overview

Each round has two phases. In **Input**, both players plan their actions in
secret at the same time. In **Resolution**, those actions resolve one at a
time, alternating between players. Planning well means predicting your
opponent.

## Core principles

These are heuristics for designing and writing the game's rules, not rulebook
text. When a new card or rule raises an edge case, use these to help answer it.
Card text overrides them.

1. **The board decides.** An action resolves against the board as it is when
   that action resolves, not as it was when it was queued.
2. **Do what you can.** An action does as much as it legally can. An action
   that can do nothing **fizzles**.
3. **Fizzles are free.** A fizzled action refunds its costs. Fizzled cards,
   however, are still discarded after playing.
4. **No source, no action.** If a unit or card leaves play, its queued actions
   fizzle.

A unit's **turn ends** when it can take no further actions this round.

## Input phase

1. Both players gain income and receive any Horses and Ordnance ordered last
   round.
2. Both players draw 1 card.
3. Each player queues actions in the order they want them to resolve. Queued
   actions appear on the board as ghosts and in a sidebar, where they can be
   reordered.
4. Costs are paid when an action is queued.
5. The phase ends when both players press **End Turn**, or when the timer runs
   out. `PROTOTYPE:` 5-minute timer.

Queueable actions: Field, Move, Shoot, Surround, play an Event, activate a
Leader or Equipment ability, order Horses or Ordnance.

## Resolution phase

1. Players alternate resolving their next queued action, starting with the
   **first player**. When one queue is empty, the other resolves the rest of
   its actions in order.
2. Before each action resolves, a Tactics window opens (see Tactics).
3. After every action has resolved, control of special hexes is updated (see
   [battlefield.md](battlefield.md)), and each player discards down to 7
   cards.

**First player.** In round 1, a coin flip decides. In each later round, the
first player is whoever would have resolved next when the last round ended.

## Tactics

Tactics are played from the hand in response to actions, like a stack.

- Before an action resolves, the player who is not acting may play a Tactic
  first. Then players alternate chances to respond.
- When both players pass in a row, the most recent Tactic resolves first, and
  so on down to the original action.

## Zone of control

Infantry and cavalry exert a **zone of control (ZoC)** over the six hexes
adjacent to them. Ranged units have no ZoC.

A unit that moves out of a hex in an enemy's ZoC provokes an **opportunity
attack** from that enemy. The moving unit takes damage and deals none.

> **Note:** A battle is not movement. A unit battles first and moves only if
> it wins. Two example situations:
>
> - Two enemy units engaged with each other never provoke opportunity attacks
>   by fighting.
> - A flanked attacker is opportunity-attacked by the flanking enemy only if
>   it eliminates its target and moves into the freed hex.

## Actions

### Field

Place a new unit on an empty hex adjacent to your stronghold. Each player may
Field at most one unit per round (see [economy.md](economy.md)). If the chosen
hex is occupied when Field resolves, the player may choose another legal hex
or cancel the Field during the Resolution phase. If no legal hex exists, Field
fizzles.

### Move

A Move declares a starting hex, a path, and a destination. If the unit is not
on its starting hex when the Move resolves, the Move fizzles. A unit may split
its movement across several Moves, and it always tries to travel the full
path it was given.

- **Allies.** A unit may move through allies but must end on an empty hex. If
  it can't, it stops on the last legal hex of its path.
- **Enemies.** Moving into an enemy's hex starts a **battle**, and both units
  deal damage. If the enemy is eliminated, the unit enters the hex and
  continues its move. If not, the unit stays in the hex it attacked from, and
  its turn ends.

Battles happen only when a unit moves into a hex an enemy holds at that
moment. If the enemy has left, the unit simply keeps moving.

### Shoot

Only units that can attack from more than 1 hex away can Shoot. Target an
enemy within range. The target takes damage and deals none back. The shooter
never moves, even if the target is eliminated. Shoot ends the unit's turn.

### Surround

Choose an enemy and a **lead unit** adjacent to it. Every allied unit adjacent
to that enemy attacks it together as one action. If the enemy is eliminated,
the lead unit moves into its hex. Surround ends the turn of every unit that
took part. *(Damage math: open, see OQ-14.)*

## Open items

- Battle, Shoot, and opportunity attack damage math (OQ-05).
- Surround damage math, and whether adjacent ranged units can take part (OQ-14).
