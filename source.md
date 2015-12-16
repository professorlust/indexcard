# IndexCard RPG

Minimal tabletop RPG rules which fit on 5x3 inch index cards.

Materials required: paper, writing utensil, six-sided die.

Please offer elegant summaries of these rules!

## Core Card (core rules of gameplay)

Characters start with 3 HEARTS, 1 BAM, 1 EVADE, and fourteen points to distribute. Every point into HEARTS adds three HEARTS.

  1. Player with highest EVADE rolls first
    * Roll 6: +2 BAM bonus
    * Roll 5: +1 BAM bonus
    * Roll 1: miss
  2. Defender rolls up to their EVADE times, if roll 6 don’t take damage
  3. Defender loses HEARTS equal to attacker's BAM plus possible bonuses
  4. Start at step #1, but rotate players in order of EVADE

Rules for creating supplement cards:

  * Must fit on index card (5x3 inches)
  * 8 point Courier New font
  * List required supplements on top, e.g., `REQUIRED: Usable Items`

## Supplement Card: Usable Items

Characters start with one item:

  * CANDY: restore `ROLL * 3` `HEARTS`; do not attack
  * SODA: +ROLL BAM bonus; unevadable attack
  * TOKEN: acts as a roll of 6; can attack
  * MOLOTOV: Damage is 3x roll; unevadable
  * THROWING STARS: Roll thrice, the total is unevadable damage.

Must announce which item used *before* rolling.

## Supplement Card: Crazy Crits

`crit` is a new stat. Each point invested in `crit` adds two points. `crit` starts at 2. Rolling six or five makes the total bonus BAM your `crit` value.

## Supplement Card: Novel

`REQUIRES: Usable Items`

A novel is a series of cards which have a scenario and options. Write the story, where each option may have `REQUIREMENTS` and `EVENTS`.

Option `REQUIREMENTS`:
  * `USE x`: Item `x` is required for this option.
  * `CHECK stat x FAIL y`: Option requires `stat` + `roll` to at least be `x`, else `FAIL` event `y`. Example: use for conversation, `"You're looking pretty!" CHECK HEARTS 20 FAIL BATTLE`

Option `EVENTS`:
  * `OPEN`: Get item #ROLL from the chest on the back of this path card
  * `BATTLE`: Battle monster on the back of this path card
  * `NEXTCARD`: select random path card from this novel

Preface non-required things which require a supplement with `SUPPLEMENT supplement card name`.

Use die roll to determine who the monster attacks.
  
### Example Novel

#### Path Card: Sleeping Ugly (Front)

You are in a room with a slumbering troll, a locked door, and a treasure chest.

To get to the chest, you must either tip-toe around the troll or fight it.

- Sneak around Troll and `OPEN` the chest (`CHECK evade 14 FAIL BATTLE`)
- `BATTLE` the Troll and `OPEN` the chest
- Go to door and `USE key` (`NEXTCARD`)

#### Path Card: Sleeping Ugly (Back)

Troll
  - H: 16 (48)
  - B: 14
  - E: 1
  - `SUPPLEMENT crazy crits` C: 4 (8)
Drops: Key

Treasure Chest
  1. KEY
  2. TOKEN
  3. MOLOTOV
  4. THROWING STARS
  5. CANDY
  6. SODA

#### Path Card: Monk Up Your Mind (Front)

You come across a meditating monk sitting in front of two doors.

  - "Philosophical banter here" CHECK STAT HEARTS 17 FAIL GAME OVER
  - BATTLE MONK
  - LEFT DOOR
  - RIGHT DOOR

#### Path Card: Monk Up Your Mind (Back)

MONK
  - H: 20
  - B: 5
  - E: 24
  - C: 12
Drops: Girly Magazine