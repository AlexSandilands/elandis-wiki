---
cssclasses:
  - hide-header-underline-3
tags:
  - rulings
---
This page records how gameplay mechanics are handled at the [[The Bloody Nails|Bloody Nails]] table. It covers two kinds of entry: rulings, which clarify how the written 2024 rules work in ambiguous situations, and house rules, which are deliberate departures from or additions to the rules as written. When a new question comes up in play, the ruling made at the table is added here so it stays consistent from session to session.

## Rulings

### Innate Spellcasting and the One-Slot Rule

Does a spell cast innately — from a feat or species trait, without consuming a spell slot — conflict with the [one spell with a spell slot per turn](https://www.dndbeyond.com/sources/dnd/phb-2024/spells#OneSpellwithaSpellSlotperTurn) rule?

> [!check] Ruling
> No. The limit only counts spells that consume a spell slot, so an innate spell can be cast on the same turn as a slotted spell. For example, casting Fireball as an action with a spell slot and then Misty Step as a bonus action via the Fey-Touched feat is legal on the same turn.

Consequences of reading the rule this way:

- Counterspell consumes a spell slot even though it is a reaction. On your own turn, if you cast a slotted spell as your action, you cannot also use Counterspell to protect it from an enemy's Counterspell — that would be a second slotted spell in the same turn.
- Spell scrolls and magic items do not consume spell slots, so they can be used on the same turn as a slotted spell, action economy permitting.

References:

- Wizards of the Coast clarified the spells-per-turn limit in the [Sage Advice Compendium](https://www.dndbeyond.com/sources/dnd/sae/sage-advice-compendium#SAC-SpellCastingTime1).
- D&D Beyond forum discussions reaching the same conclusion: [thread one](https://www.dndbeyond.com/forums/dungeons-dragons-discussion/rules-game-mechanics/215808-limitation-on-casting-multiple-spells-per-turn-in), [thread two](https://www.dndbeyond.com/forums/dungeons-dragons-discussion/rules-game-mechanics/232588-casting-innate-spells-after-normal-spells-2024).

### Ranged Attacks in Melee with a Sniper Feat

How do ranged attacks work within 5 feet of an enemy for characters with [Sharpshooter](https://www.dndbeyond.com/sources/dnd/phb-2024/feats#Sharpshooter) or [Spell Sniper](https://www.dndbeyond.com/sources/dnd/phb-2024/feats#SpellSniper), and what happens against a prone target?

> [!check] Ruling
> A sniper feat removes the usual disadvantage on ranged attacks made within 5 feet of an enemy. Against a [prone](https://www.dndbeyond.com/sources/dnd/phb-2024/rules-glossary#ProneCondition) target, ranged attacks have disadvantage, but any attack roll made within 5 feet of a prone target — the rule does not say melee only — has advantage. For a sniper standing over a prone enemy the two cancel out, leaving a straight roll.

The prone condition is commonly read as granting advantage only to melee attacks within 5 feet, but the text explicitly applies to all attack rolls at that range, so rules as written the straight roll stands. Thematically this fits: a sniper should be able to stand over a downed enemy and shoot them point blank, since a creature on the ground can't disrupt their aim or spellcasting.

## House Rules

### Flanking

Do flanking rules apply?

> [!check] Ruling
> No. Flanking is not used at this table.

Flanking was only ever a variant rule in the 2014 books and was dropped entirely from the 2024 rules. In practice it ends up too fiddly — it gets brought up whenever someone is hunting for any possible advantage and ignored the rest of the time.

### Resurrection

What happens when a resurrection spell is cast?

> [!check] Ruling
> This table uses [Matt Mercer's resurrection rules](https://criticalrole.miraheze.org/wiki/Resurrection_in_Exandria). Any resurrection spell short of True Resurrection or Wish requires a check to succeed, and spells with a casting time longer than one action become a ritual involving a series of checks. Resurrection is never certain — death severs the bonds between spirit and body, and they can never be fully mended.

The resurrection ritual, for spells such as Raise Dead and Resurrection:

1. The caster begins the ritual with the appropriate spell.
2. Up to three party members can contribute to the ritual in any way they like — a prayer, an emotional appeal to the departed soul, an offering, a song — each rolling a contribution skill check. The DM picks an appropriate skill and DC for each contribution based on what the player describes. A successful contribution lowers the final DC, while a failed one raises it.
3. After the contributions, the DM rolls a final resurrection success check with no modifier. The base DC is 10, adjusted by the contribution results and the circumstances of the death.
4. If the final check fails, the soul is lost — permanently, barring True Resurrection or Wish.

Rapid resurrection, for Revivify and similar one-action effects: no contribution checks are allowed. Instead the caster alone makes a rapid resurrection check. If it fails, no further attempts can be made until someone performs a full ritual with a spell whose casting time is longer than one action.

Escalating difficulty: each time a character is successfully returned to life, the DC for any later resurrection of that character increases by 1, reflecting the soul's eroding connection to the physical world. Mercer notes this can be raised to +2 per death for a harsher campaign, though he has warned that this may be too punishing at low levels where deaths are common.
