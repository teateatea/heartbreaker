---
aliases: [Combat]
tags: []
author: [Joseph Liao Gormley]
date: [2022-04-20]
template_version: [KETTLE-2022-04-06]
creation_date: [2022-04-20]
---
[[home|Home]] | [[Rules]] | Adventures | **Combat**
___
For the purpose of these rules:
- **Creature:** Any Player Character (PC), Non-Player Character (NPC), Monster, group of Monsters, or other agent of change that is participating in the combat.
- **Active Creature:** The Creature that is currently taking an Action, who is taking their turn.

___
### **Combat Order - Popcorn Initiative**
1. Roll Initiative
2. Take Action
3. Pass the Action
4. End of Round

___
### 1. Roll Initiative
**Roll 1d20+MOD:** At the start of each combat, each Creature rolls Initiative, modified by DEX or WIS *(see **[[Ability Scores]]**)*. <!--The referee may determine an initiative modifier for Monsters that are very fast or slow, instead of applying a DEX modifier.-->

**Winner:** The individual with the highest result acts first.

**Ties:** Players win ties, or both sides may roll again to determine a winner.

___
### 2. Take Action
The Active Creature performs their action, such as attacking, or casting spells, and may move if they wish.

See below for details.

___
### 3. Pass the Action
After completing their action, the Active Creature nominates the next Creature to take their turn. That Creature takes their Action, and then nominates who goes next.

Once every Creature has taken their Action, the last Creature will decide who acts first in the next round (and can choose themselves).

___
### 4. End of Round
The End of Round phase occurs, after the last Creature has acted, but before the next Round begins. Monsters must make a Morale Check, and combat effects may end (see below for details). Then the next Round will begin, and any Creature can be nominated to act.

##### Monster Morale
*See **[[Morale]]**.*

##### Effect Durations
All effects *(such as physical conditions, magical effects, or poisons)* reduce their Duration by 1. Any effect already at Duration 0 expires.

> Alice casts a spell that lasts 1 round on Bob. Alice is the last person to go that Round. After that, the End of Round phase occurs, so the Spell's Duration is reduced to 0. It continues through the entire next Round and expires in the End of Round phase at the end of the *next* round.

> An easy way to track it is to effects with Duration is with a d10. When Alice casts a spell that lasts 1 Round, put a d10 out set on “1.” At the End of Round, count down the effect. However, do not remove the die when it reaches 0. Instead, remove the die when it is already on 0 when a Round ends.

___
___
# Taking Action
___
## Readying an Action
Any creature may specify an action and a trigger condition. If the trigger condition appears, they may choose to take the readied action, or wait until it is triggered again by something else.

If that creature hasn't taken the readied action by the time they are nominated again, they lose that readied action (but may ready it again if they wish).


___
## Waiting
Any Creatures may choose to wait, instead of immediately taking action. They nominate another Creature to act, and are now considered "waiting". They must wait until they are nominated again to take their action.

If a waiting creature has been nominated, and all remaining creatures are also waiting, they can no longer wait and must act.


___
## Movement
### Outside of Melee
**Movement rate:** A character can move up to their encounter movement rate each round.

**Maximum duration:** Characters may move at this rate for at most 60 rounds.

### In Melee
When in melee with a foe, only the following forms of movement are possible:

* **Fighting withdrawal:** The character moves backwards at up to half their encounter movement rate. There must be a clear path for this movement.
* **Retreat:** The character turns and flees from melee, moving up to their full encounter movement rate. For a Duration of 1 Round, the character may not attack, and their opponents gain a +2 bonus to all attacks against the character and ignores any AC bonus due to the character’s shield (if applicable).

___
## Attacking
### Attack Rolls <!--*(AAC)*-->
1. **Roll 1d20**
2. **Apply modifiers:** STR for melee; DEX, range, cover for missile attacks.
3. **Determine hit AC:** Add the character’s attack bonus to the attack roll. The result is the ascending AC score that the attack hits.
4. **Result:** If the hit AAC is equal to or higher than the opponent’s AAC, the attack hits. Roll for damage.

### 1s and 20s
Unmodified attack rolls of 20 always hit. Unmodified attack rolls of 1 always miss.

### Invulnerabilities
Some monsters are immune to certain attacks. In this case, even if an attack hits, damage is not rolled.

### Attacks Per Round
PCs normally attack once per round. Some monsters have multiple attacks.

### Attacking and Moving
Movement and attacking may be combined in the same round.

### Slow Weapons
Characters with Slow weapons *(as indicated in the equipment description)* may only attack after all non-waiting creatures have taken their turn.

### Rolling for Damage <!-- *(Variable Weapon Damage)*-->
**PC attacks:** Inflict the damage indicated for the weapon in the equipment lists. Damage of melee attacks is modified by STR.

**Monster attacks:** Deal the damage indicated in the monster’s description.

**Minimum damage:** An attack which hits always deals at least one point of damage, even when damage modifiers reduce the number rolled to 0 or less.

**Death:** A monster reduced to 0 hit points or less is killed. For PCs reduced to 0 hit points, see **[[Healing & Death|Death]]**.


___
## Melee Attacks
Are possible when opponents are **5’ or less** from each other. See **''Attacking**''.

___
## Missile Attacks
Are possible when opponents are **more than 5’** from one another. See **''Attacking**''.

### Range Modifiers
All missile weapons have ranges, noted in the equipment lists. <!-- #Revisit -->

**Short range:** +1 bonus to attack rolls.

**Medium range:** No bonuses or penalties.

**Long range:** –1 penalty to attack rolls.

**Beyond long range:** Attack not possible.

### Targets Behind Cover
**Complete cover:** The target cannot be hit.

**Partial cover:** The referee may apply attack penalties of between –1 and –4 (e.g. a small table might incur a –1 penalty; dense woods might incur a –4 penalty).


___
## Spell Casting
**Freedom:** The character must be able to speak and move their hands. A spell caster cannot cast spells if gagged, bound, or in an area of magical silence.

**Sole action:** When casting a spell, no other actions may be taken in the round.

**No movement:** The character cannot move and cast a spell in the same round.

**Line of sight:** Unless noted in a spell’s description, the intended target (a specific monster, character, object, or area of effect) must be visible to the caster.

### Disrupting Spells
If a spell caster is successfully attacked or fails a saving throw before their turn ends, the spell being cast is disrupted and fails. It is removed from the caster’s memory as if it had been cast. This is usually as a result of a readied action.

___
***Source:*** [Combat - OSE SRD](https://oldschoolessentials.necroticgnome.com/srd/index.php/Combat)
- *Combat Sequence Per Round* is replaced by *Popcorn Initiative.*
- *Individual Initiative (Optional Rule)* is in use.
	- *Initiative bonus* can be Dexterity *or Wisdom.*
- *Monster Morale (Optional Rule)* and *Morale (Optional Rule)* are both in use.
- *Ascending Armour Class (Optional Rule)* is in use, and has been merged into *Attack Rolls.*
	- *"Referee rolls for damage."* changed to *"Roll for damage."*
- *Rolling for Damage:* PCs have 3 lifetime Death saves.
- *Variable Weapon Damage (Optional Rule)* is in use, and has been merged into *Rolling for Damage*.
***References:***
- [**Popcorn Initiave** by **The Angry GM**](https://theangrygm.com/popcorn-initiative-a-great-way-to-adjust-dd-and-pathfinder-initiative-with-a-stupid-name/)
<!-- Sources, read more, links, etc. -->
<!-- *Source: Entry by [[Mike Maxin]].* -->
<!-- Leave an empty line at the end, otherwise Exporter complains. -->
