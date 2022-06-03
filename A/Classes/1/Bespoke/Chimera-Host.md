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
### Chimeric Forms
*A Chimera-Host's mind has multiple Forms, any one of which can take charge of the shared body. Each Form has distinct preferences, mannerisms, and interests from the others.*

Chimera-Hosts may have up to $L \div 2$ Forms, rounding down *(where $L$ is the Character's total number of Levels)*. <!-- Confusion Alert: Careful, this is *total* levels, rather than Levels in Chimera specifically. Revisit for consistency if this is ever an issue -->

| Level | Maximum Number of Forms |
| ----- | ------------- |
| 1-3   | 1             |
| 4-5   | 2             |
| 6-7   | 3             |
| 8-9   | 4             |
| 10+   | 5             |

> *Jo: What is the best name for the different personas? Heads? Minds? Forms? Beasts? Avoid Personalities to differentiate from DID.*
___
#### Shifting Forms
*Each Form believes they know the best way to accomplish everything, and eagerly wrestles to exert their will upon the world.*

When you roll a d20 for an Ability Check or Saving Throw, note the result.
- **If the result is equal to or less than $L$,** complete all relevant actions, then ***Shift Forms:***
	- **The active Form gains +1 Stress.**
		- **Check for *Ambition,* and *Burn Out.***
	- **If the result is an even number,** choose which Form takes control. You may choose to keep the active Form in control.
	- **If the result is an odd number,** roll to randomly determine which Form takes control.
		- **If the active Form remains in control,** roll a **save vs Spells** for each inactive Form that isn't Burned Out.
			- On any number of failures, roll ***Spell Catastrophe,*** as the other Forms in your mind petulantly sabotage your efforts.

<!-- DO WE LIKE SPELL CATASTROPHE? THIS IS LIKELY ON THE CHOPPING BLOCK. NVM WE HAVE TO DISCOURAGE NOT SHIFTING. The result on the d20 is the number of Turns that this Form will keep control *(A Turn is 10 minutes)*. ***Shifting*** again is prevented until that duration expires.-->

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
> He attempts to strike a foe with his dagger, rolling a d20 to attack. He rolls a 5, missing the attack and triggering a ***Shift.***
>
> Because it's an odd number, Karkemish rolls a d3 to determine which Form will take control: He rolls a 2, shifting from "The Belligerent" to "The Mendicant" as soon as he finishes his swing *(who promptly apologizes for the violence).*
<!-- The Mendicant stays in charge for 50 minutes, and then ***Shifting*** becomes possible again.-->
<!-- If he had rolled a 2, 4, or 6, a ***Shift*** would have been triggered, but he could have chosen to remain in the same form to continue fighting violently.-->

___
##### Voluntary Hand-Off
*Sometimes, the active Form recognizes that they're ill-equipped to handle the situation before them. They know which Form is best suited for the task, but the hand-off doesn't always go as smoothly as planned.*

To voluntarily initiate a ***Shift,*** roll d20.
- **If the result is equal to or less than $L$ + Stress**, ***Shift*** as if you rolled an even number:
	- Gain +1 Stress, then choose which Form takes control.
- **If the result is greater than $L$ + Stress,** ***Shift*** as if you rolled an odd number:
	- If this occurs during combat, on your next Round you may only move *or* act, not both.
	- Gain +1 Stress, then randomly determine which Form takes control.
		- If the active Form remains in control, **save vs Spells** to prevent *Spell Catastrophe.*

___
#### Stress
<!-- > *Jo: Is this the best name for this concept? Discord? Reverse it and call it Resolve?*-->

*The active Form is constantly enduring pressure from the other Forms in the Chimera-Hosts mind, all of whom would gladly dethrone one another. While generally manageable, the stress can be overwhelming during critical or volatile situations.*

Track Stress for each Form separately. The active Form gains Stress for the following events:
- ***Shifting Forms:*** +1 Stress.
- **Taking damage:** +1 Stress.
- **The active Form's Aversion:** +1 Stress immediately, and every 10 minutes.
- **Time passes:** +$F$ Stress every 10 minutes *(where $F$ is the number of inactive Forms that aren't Burned Out.)*

> To track this, it'd be nice to have little bowls of different colours for each Form, and stress tokens.
___
#### Burn Out
The Chimera-Host's Stress Limit is $L$ *(where $L$ is the Character's total number of Levels)*. <!-- This could be called Exhaustion.   Confusion Alert: Careful, this is *total* levels, rather than Levels in Chimera specifically. Revisit for consistency if this is ever an issue --> 
___
When a ***Shift*** is triggered, and the active Form's Stress is **equal to or over the Stress Limit,** they ***Burn Out.***
- **Roll for *Burn Out* Duration:** d6 + [Stress over Limit] Turns. 
	- For this duration, the Form cannot be chosen for a ***Shift***, doesn't contribute to Stress when time passes, and doesn't inflict *Spell Catastrophes.*
	- At the end of this duration, they remove all Stress, and become available to be chosen for a ***Shift.***

___
#### Ambition
If all other Forms are Burned Out when a ***Shift*** is triggered, ignore it and gain **Ambition** until another Form becomes available.

**Ambition:** You may choose to make any roll with advantage. Gain +1 Stress each time you do this.

<!-- Roll $X$d6, where $X$ is the current Form's Stress. The current Form is Burned Out for that many turns *(A Turn is 10 minutes)*. -->
___
___
#### Aversions & Focuses
Each Form has an Aversion, something that they find intolerable. When the active Form experiences their Aversion, they gain +1 Stress. If the Aversion continues, they gain +1 Stress every 10 minutes.

Each Form has their own Focuses, the methods they use to manage Stress. When the active Form performs a Focus, they lose -1 Stress.

> Karkemish's Aversion is "Getting Wet." When he tumbles down a waterfall, he immediately gets +1 Stress. He gains another +1 Stress when it takes 10 minutes for the tropical sun to thoroughly dry him off.
> 
> Later that night, he cooks up a boar, happily humming to himself: -1 Stress. Before bedtime, he burns some incense: -1 Stress. He much prefers this side of life!
___
#### Creating a New Form
When creating a new Form, use the following instructions.

> Jo: How much do you want to be in control here? Want to roll for these or choose them? I might make a table to roll on.

##### 1. Choose Maestro Specialty and Forsaken Schools.
Their Specialty cannot be a school that has been Forsaken by any other Form.
- Each Form has 2 Spells from their Speciality that only they can cast.
- All other Spells that the Chimera-Host learns can be cast by any Form.

##### 2. Choose an Aversion
This should be a brief, general idea, rather than a very specific pet-peeve.

***Examples:**
- *Getting wet.*
- *Getting insulted.*
- *Being told what to do.*
- *Losing something.*
- *Lying.*

##### 3. Choose three Focuses
1. **A Quiet Action**
	- A slower, calm activity *(~10 minutes)*: meditation, reading, cooking, etc.
2. **A Loud Action**
	- A burst of high energy activity, or a combat action *(less than 1 minute)*: singing, running, charging, etc.
3. **A Consumeable**
	- Use something up: specific food or drink, burning wood or candles, etc.







___
<!--*See also:* 
*References:*
*Source:* -->
<!-- Sources, read more, links, etc. -->
<!-- *Source: Entry by [[Mike Maxin]].* -->
<!-- Leave an empty line at the end, otherwise Exporter complains. -->
