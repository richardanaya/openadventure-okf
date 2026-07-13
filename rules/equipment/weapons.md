---
type: "Equipment"
title: "Weapons"
description: "Weapon rules, properties, costs, combat modifiers, ammunition, and accessories."
tags: ["open-adventure", "fantasy", "core-rules", "equipment", "weapons"]
license: "CC0-1.0"
source_uri: "https://www.openadventurerpg.com/coc"
source_artifact: "Open-Adventure-Fantasy-Core-Rules-Text-v1.0.md"
source_revision: "v1.0"
source_sha256: "7f48d6312e365ffbf25abc1597e076e1dd5d5d3ec61c91e440147490b146993f"
source_start_line: 2902
source_end_line: 2991
derivation: "transformed-extract"
---
# Weapons

The weapon lists include the following information:

* **Name**: Weapon name.
* **Cost**: Weapon cost.
* **PA**: Primary Attribute added to the Action Score when performing an Attack Check with this weapon. Some weapons list more than one Attribute, in which case the attacker may choose which Primary Attribute to use when determining their Action Score.
* **Attack**: A modifier to the character’s Action Score (+# AS) or the Difficulty Score (+# DS) when making an Attack Check using this weapon. Weapons that increase the Difficulty Score for Attack Checks are difficult to wield properly.
* **Parry**: If a character wields a rigid weapon and the Adventure Guide allows it, the player may choose to have their character Parry an attack. Some weapons are especially well-suited for this purpose and add a Benefit to the character’s Body Defense when parrying. If the weapon provides a Benefit, the column will list +1. A dash in the parry column means the weapon may be used to Parry but provides no additional Benefit. A listing of NA means the weapon may not be used to Parry. For more information, see [Defenses](/rules/attributes/defenses.md).
* **Effect**: A modifier added to the Effect of a successful Attack Check made with this weapon.
* **Properties**: A list of the weapon’s special properties.

Note that the Attack and Defense scores listed in NPC statblocks already include the Benefits and Drawbacks of their weapons.

## Weapon Properties

Many weapons have special properties with distinct game effects.

* **Ammunition (type)**: The weapon requires ammunition of the type listed, such as arrows or bullets.
* **Dangerous**: The weapon is especially difficult to wield. If the attacker suffers a critical failure on their Attack Check, the weapon injures the wielder, inflicting d6 Body Points of damage. Armor (Body) reduces the damage.
* **Fragile**: If the attacker suffers a critical failure on their Attack Check, the weapon breaks and is ruined.
* **[Grab](/actions/grab.md)**: If the attacker wishes, they may perform a [Grab Check](/actions/grab.md) with this weapon instead of an Attack Check.
* **Hybrid**: The weapon may be used as a ranged weapon or as a melee weapon.
* **Light**: The weapon may be used as an off-hand weapon providing a +1 Benefit to the character’s Body Defense when parrying an attack.
* **Loading**: Loading this weapon requires a Minor Action.
* **Long**: The weapon may be used to attack Targets Across the Room, but it cannot be used to attack foes at Reach.
* **Non-Lethal**: This is a non-lethal weapon. Wounds caused by this weapon do not trigger a Death Check.
* **Piercing**: The Effect of a successful Attack Check ignores 1 point of Armor (Body).
* **Range**: The weapon may be used for Ranged Attack Checks. The weapon’s short and long ranges are listed, separated by a slash. The ranges are Reach (R), Across the Room (AR), Stone’s Throw (ST), or Bow Shot (BS). Add a +1 Drawback to the Difficulty Score for Attack Checks against targets closer than short range or at long range. You may not use this weapon to make Ranged Attack Checks against opponents farther away than the listed long range. Unless this weapon also has the Hybrid property, it may not be used as a melee weapon.
* **Slow-Loading**: Loading this weapon requires a Major Action, although no Action Check is required.
* **Two-Handed**: The weapon must be wielded with two hands.
* **Versatile**: The weapon may be used with a one-handed or two-handed grip when making melee Attack Checks. Add +1 to the Effect of successful Attack Checks when this weapon is used two-handed in melee.

## Weapon Table

| **Name** | **Cost** | **PA** | **Attack** | **Parry** | **Effect** | **Properties** |
| --- | --- | --- | --- | --- | --- | --- |
| ***Swords and Daggers*** |  |  |  |  |  |  |
| Dagger | 5 sp | Cor | - | - | - | light, range AR/ST, hybrid |
| Shortsword | 6 sp | Cor | - | - | +1 | light |
| Scimitar | 20 sp | Str | +1 AS | - | +1 | light |
| Rapier | 100 sp | Cor | +2 AS | +1 | - | light, fragile |
| Longsword | 100 sp | Str/Cor | +1 AS | +1 | +1 | versatile |
| Greatsword | 200 sp | Str | +1 DS | - | +3 | two-handed |
| ***Axes*** |  |  |  |  |  |  |
| Handaxe | 10 sp | Str/Cor | - | - | +1 | light, range AR/ST, hybrid |
| Battleaxe | 100 sp | Str | +1 DS | - | +2 | versatile |
| Greataxe | 150 sp | Str | +2 DS | - | +3 | two-handed |
| ***Clubs, Maces, and Flails*** |  |  |  |  |  |  |
| Club | 1 cp | Str | - | - | - | light, non-lethal |
| Light hammer | 3 sp | Str | +1 AS | - | - | light, range AR/ST, hybrid |
| Mace | 10 sp | Str | +1 AS | - | +1 | - |
| Quarterstaff | 1 sp | Str | +1 AS | +1 | - | two-handed, non-lethal |
| Flail | 50 sp | Cor | +2 DS | NA | +2 | grab |
| Greatclub | 30 sp | Str | - | - | +2 | two-handed, non-lethal |
| Morningstar | 100 sp | Str | +1 AS | - | +2 | - |
| War hammer | 50 sp | Str | - | - | +2 | versatile |
| Whip | 10 sp | Cor | +2 DS | NA | - | long, grab, dangerous |
| ***Spears and Polearms*** |  |  |  |  |  |  |
| Spear | 3 sp | Str/Cor | - | - | - | versatile, range AR/ST, hybrid |
| Trident | 50 sp | Cor | - | - | +1 | versatile, range AR/ST, hybrid |
| Halberd | 40 sp | Str | - | NA | +2 | long, two-handed |
| Lance (long spear) | 6 sp | Str/Cor | - | NA | - | long |
| ***Simple Ranged Weapons*** |  |  |  |  |  |  |
| Dart | 5 cp | Str/Cor | - | NA | +1 | range AR/ST |
| Sling | 2 cp | Cor | - | NA | - | ammunition (sling bullet), loading, range AR/ST |
| Shortbow | 10 sp | Cor | - | NA | +1 | ammunition (arrow), range AR/BS, loading, two-handed |
| Crossbow, light | 50 sp | Cor | +1 AS | NA | +2 | ammunition (quarrel), range AR/BS, slow-loading, two-handed, piercing |
| Javelin | 8 sp | Str/Cor | - | NA | +1 | range AR/BS |
| ***Martial Ranged Weapons*** |  |  |  |  |  |  |
| Blowgun | 10 sp | Cor | +1 DS | NA | - | ammunition (blowgun needle), range AR/ST, loading |
| Crossbow, hand | 30 sp | Cor | +1 AS | NA | - | ammunition (quarrel), range AR/ST, light, loading |
| Longbow | 90 sp | Cor | - | NA | +1 | ammunition (arrow), range AR/BS, loading, two-handed |
| Crossbow, heavy | 100 sp | Cor | +1 AS | NA | +2 | ammunition (quarrel), range AR/BS, slow-loading, two-handed, piercing |
| Net | 100 sp | Cor | - | NA | NA | grab, range R/AR, hybrid |
| ***Ammunition and Accessories*** |  |  |  |  |  |  |
| **Name** | **Cost** | **PA** | **Attack** | **Parry** | **Effect** | **Properties** |
| Arrows (24) | 16 sp | - | - | NA | - | - |
| Blowgun needles (50) | 1 sp | - | - | NA | - | - |
| Quarrels (20) | 6 sp | - | - | NA | - | - |
| Sling bullets, lead (10) | 1 sp | - | - | NA | +1 | - |
| Sling bullets, stone (10) | 1 cp | - | - | NA | - | - |
| Quiver | 1 sp | - | - | NA | - | - |
| Scabbard, dagger | 5 sp | - | - | NA | - | - |
| Scabbard, sword | 10 sp | - | - | NA | - | - |
