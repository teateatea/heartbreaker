---
aliases: [Chimera-Host]
tags: [Parasite]
author: [Joseph Liao Gormley]
date: [2022-06-03]
template_version: [HEARTBREAKER-2022-04-22]
creation_date: [2022-06-03]
---
[[home|Home]] | **Chimera-Host** | [[Magic-User]]
___
*Your mind is a many-headed beast, each more exceptional than the last. You might grow into a one-man army, if your mind doesn't mutiny against itself. For now, you're just a fledgling Chimera, awkwardly wielding your gangly mind.*

**Class Proficiencies, Level Progression, and Combat as Magic-User (Maestro).**
___
**Hit Dice:** 1d4<br>**Armour:** None<br>**Weapons:** Dagger<br>**Languages:** Common
___
![[Magic-User#Magic-User Level Progression]]
___
![[Magic-User#Combat]]
___
### Paradigm: Maestro

___
### Forms
> *Jo: What is the best name for the different personas? Heads? Minds? Forms? Beasts? Avoid Personalities to differentiate from DID.*

*Chimera-Hosts have multiple Forms, any one of which can take charge of the shared body. Each Form has distinct preferences, mannerisms, and interests from the others.*

Chimera-Hosts may have up to $L \div 2$ Forms, rounding down *(where $L$ is the Character's total number of Levels)*. <!-- Confusion Alert: Careful, this is *total* levels, rather than Levels in Chimera specifically. Revisit for consistency if this is ever an issue -->

| Level | Maximum Number of Forms |
| ----- | ------------- |
| 1-3   | 1             |
| 4-5   | 2             |
| 6-7   | 3             |
| 8-9   | 4             |
| 10+   | 5             |

___
#### Shifting Forms
*Each Form believes they know the best way to accomplish everything, and eagerly wrests control to exert their will upon the world.*

When you roll a d20 for an active Ability Check or Saving Throw, note the result on the die.
- **If the result is equal to or less than $L$,** complete all relevant actions, then ***Shift:***
	- **The active Form gains +1 Stress.**
		- **Check for *Burn Out & Ambition.***
	- **If the result is an even number,** choose which Form takes control. You may choose to keep the active Form in control.
	- **If the result is an odd number,** roll to randomly determine which Form takes control instead.
- If a ***Shift*** is triggered, but the active Form remains in control, roll a **save vs Spells**. On a fail, roll *Spell Catastrophe,* as the other Forms in your mind petulantly sabotage your efforts.

<!-- The result on the d20 is the number of Turns that this Form will keep control *(A Turn is 10 minutes)*. ***Shifting*** again is prevented until that duration expires.-->

<!-- > *Jo:  Cooldown duration is a really useful dial to control how unpredictable the Chimera is. Shifting every combat round seems too volatile, while lasting days without Shifting seems dull. I think shifting every 10-60 minutes is a happy medium?-->

<!-- ALTERNATIVELY, BURN OUT. DURATION IS HOW LONG THAT FORM CANNOT BE CHOSEN. I think this is a good balance? You can expect  to Shift every 10-60 minutes most of the time. (Younger Chimera's flit back and forth between their 2 Forms every 10-20 minutes lol, while Veteran Chimera Forms might hold on 1-2 hours!)-->

<!--After ***Shifting,*** roll *Duration* to determine how long this Form keeps control.
| d12   | Duration                 |
| -----: | ------------------------ |
| 12    | d6 Days *(1-6 days)*       |
| 10-11 | d6 Turns *(10-60 minutes)* |
| 1-9   | d6 Rounds *(6-36 seconds)* |-->

<!--
> ALTERNATIVE:
> The result on the d20 roll is the number of Turns *(10 minutes)* that this Form will keep control. After ***Shifting,*** this Form keeps control fouse the following formula to determine how long this Form keeps control:
> d20 result $\times$ -->
___
> For example, Karkemish is a 6th level Chimera-Host, with 3 Forms.
> 
> He attempts to strike a foe with his dagger, rolling a d20 to attack. He rolls a 5 *(missing the attack)*, triggering a ***Shift.***
>
> Because it's an odd number, Karkemish rolls a d3 to determine which Form will take control: He rolls a 2, shifting from "The Belligerent" to "The Mendicant" as soon as he finishes his swing *(who promptly apologizes for the violence).*
<!-- The Mendicant stays in charge for 50 minutes, and then ***Shifting*** becomes possible again.-->
<!-- If he had rolled a 2, 4, or 6, a ***Shift*** would have been triggered, but he could have chosen to remain in the same form to continue fighting violently.-->
___
#### Stress
> *Jo: Is this the best name for this concept? Discord? Reverse it and call it Resolve?*

*Each Form is contantly enduring pressure from the other Forms in the Chimera-Hosts mind, all of whom would gladly dethrone one another. The stress is generally manageable, but can become overwhelming during critical or volatile situations.*

Track Stress for each Form separately. The active Form gains Stress for the following events:
- ***Shifting Forms.*** +1 Stress.
- **Taking damage.** +1 Stress.
- **The active Form's Aversion.** +1 Stress immediately, and every 10 minutes.
- **Time passes.** +$F$ Stress every 10 minutes *(where $F$ is the number of inactive Forms that aren't Burned Out.)*


___
#### Burn Out & Ambition
The Chimera-Host has a Stress Limit up to $L$ *(where $L$ is the Character's total number of Levels)*. <!-- Confusion Alert: Careful, this is *total* levels, rather than Levels in Chimera specifically. Revisit for consistency if this is ever an issue --> 
___
When the active Form's Stress is equal to or over the Stress Limit, and a ***Shift*** is triggered, they **Burn Out.**
- **Roll for Burn Out Duration:** [d6 $\times$ Stress] Turns. 
	- For that duration, they cannot be chosen for a ***Shift***, and don't contribute to Stress when time passes.
	- At the end of that duration, they remove all their Stress, and are available to be chosen for a ***Shift.***

___
If all other Forms are Burned Out when a ***Shift*** is triggered, gain **Ambition** until another Form becomes available. 

**Ambition:** You may choose to make any roll with advantage.

<!-- Roll $X$d6, where $X$ is the current Form's Stress. The current Form is Burned Out for that many turns *(A Turn is 10 minutes)*. -->

___
### Aversions & Focuses
Each Form has their own Focuses, the methods they use to manage Stress. When the active Form performs a Focus, they lose -1 Stress.

Each Form has an Aversion, something that they find intolerable. When the active Form experiences their Aversion, they gain +1 Stress. If the Aversion continues, they gain +1 Stress every 10 minutes.

> Karkemish's Aversion is "Getting Wet." When he tumbles down a waterfall, he immediately gets +1 Stress. He washes up on the river bank, and stumbles into the jungle. He gains another +1 Stress because it takes 10 minutes for the tropical sun to thoroughly dry him off.
> 
> Later that night, he cooks up a boar, happily humming to himself: -1 Stress.
___
### Creating a New Form
When creating a new Form, use the following instructions.

##### 1. Choose their Maestro Specialty and Forsaken Schools.
Their Specialty cannot be a school that's been Forsaken by any other Form.
##### 2. Choose an Aversion
This should be a general idea rather than a very specific pet-peeve.

##### 3. Choose three Focuses
1. **A Quiet Action**
	- 10 minutes, Low energy activity: meditation, reading, cooking, etc.
2. **A Loud Action**
	- 6 seconds, High energy activity, or combat action: singing, running, charging, dodging, etc.
3. **A Consumeable**
	- Use something up: specific food or drink, burning wood or candles, etc.







___
<!--*See also:* 
*References:*
*Source:* -->
<!-- Sources, read more, links, etc. -->
<!-- *Source: Entry by [[Mike Maxin]].* -->
<!-- Leave an empty line at the end, otherwise Exporter complains. -->
