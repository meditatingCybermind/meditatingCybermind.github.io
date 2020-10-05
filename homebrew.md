head (
# Houserules
A collection of rule adjustements and additional feat options.
-
)

# General Changes

* All class feats with a level requirement of 2 now have a level requirement of 1.
* All multiclass archetype feat level requirements reduced by 2, to a minimum of 1.
* Additional Spell levels gained from Basic, Expert, and Master spellcasting multiclass feats are available 2 levels sooner.
* All characters have an additional class feat at level 1.
head(
-
)

# Classes
## Alchemist
note (
# Alchemist's Alchemical DC Adjustments
* Remove the Potent Poisoner Feat
* Remove the Powerful Alchemy Feat
)
note (
# Toxicologist
Replace the second sentence with: "You gain the poison weapon feat, even if you don't meet the prerequisites for it. You gain additional poisons from this feat equal to your Intelligence modifier."
)


### Class Features
note (
# Infused Reagents
* The DC of your alchemical items crafted with infused reagents is equal to your alchemist class DC.
* "Each day during your daily preparations, you gain a number of batches of infused reagents equal to your level + your Intelligence modifier + 3."
)
head(
-
)
# Skills
## General
note (
# Recall Knowledge
* Lore skills adjust difficulty down by 2 steps (CRB 503). This is a rules clarification.
* Recall Knowledge can still be attempted if the previous attempt failed or critically failed, but the difficulty will increase by 1 step with each attempt regardless.
)

## Crafting
note (
# Craft 
In the feat body, change:
* “You must spend 4 days at work, at which point you attempt a Crafting check.” 

to

* “Find the full price of the item. You must spend a number of days equal to the full price of the item divided by that amount of gold gained by earning income in table 4-2 per day or 4 days whichever is lower. At this point, you attempt a Crafting check.”
)
head(
-
)
#Feats
## Skill feats

item (
# Multitasker
## Feat 7
-
;Downtime,General,Skill
**Prerequisite** Master in Crafting
-
You can work on multiple projects at once, so long you can afford it. You may craft multiple common mundane items at one time, so long as the sum of the full price of those items is less than what you could craft on a success in 1 day.

If you are legendary in crafting, you can craft any items you otherwise meet the requirements for in this manner, under the same price restrictions.
)



## Class Feats
### any
item (
# :f: Fast Hands
## Feat 1
-
;Flourish,Any
**Trigger** When you would perform an interact action.
-
You may instead choose to perform it as a free action.
)

### Alchemist
note (
# Additional Feats
Add the Poison Weapon (6), Improved Poison Weapon (8), and Deadly Poison Weapon (12) to the alchemist feat list. For Alchemists, Deadly Poison Weapon is Common.
)




### Fighter
item (
# Reactive Shot
## Feat 4
-
;Fighter
Your foes trigger an attack of opportunity with your ranged weapons as normal as long as they are within your first range increment. Strikes made in this manner suffer a -4 circumstance penalty to hit.
)

## Archetypes
**Level reductions from general changes are already applied.**

### Spellcasters
7 feats have been combined into one editorially for brevity. "Tradition Expansion" is a representation of 1 of 7 feats you can take for your spellcasting archetype.

Replace the word **TRADITION** in the name and text with "Bloodline / Occult / Divine / Primal / Arcane / Mysterious / Patron's" for Sorcerers / Bard / Clerics / Druids / Wizards / Oracles / Witches respectively. Replace **CLASS** with the name of the class in a similar manner.
item (
# TRADITION Expansion
## Feat 10
-
;Archetype
**Prerequisites** Expert CLASS Spellcasting, TRADITION Breadth
-
You can cast more spells each day. Increase the spell slots you gain from CLASS archetype feats by 1 for each spell level other than your highest spell level
)

### Alchemist
note (
# Alchemist Dedication
* You gain the alchemist’s infused reagents class feature, gaining a number of reagents each day equal to your level + 1.
)
head(
-
)
# Magic
## Focus Spells
note (
# Refocus Activity
Change **"This restores 1 focus Point to your focus pool."** to **"This restores your focus point pool to maximum."**
)

note (
# Feats to increase refocus strength
Removed, due to the above.
)

note (
# Focus Pool
You have a focus point pool equal to the number of focus spells you are able to use, to a maximum of 3.
)


## General Spellcasting Changes
### Spell slots
New terms: **"Base Minimum"** and **"Base Maximum"**. The Base Minimum is the lowest number of spells a character has per spell level, and the Base Maximum is the highest. Under normal rules, a Wizard has 2 as their base minimum, and 3 at their base maximum -- Plus one depending on their school. The following changes use these terms to define across the board changes of that style.

note (
# Spellcasting Growth
All spellcasters gain additional base minimum and maximum spell slots per level. The totals are in the table below.
|Class|Base Minimum|Base Maximum|
|-----|-----|-----|
|Bard|2|5|
|Cleric|2|4|
|Druid|2|4|
|Oracle|2|5|
|Sorcerer|3|6|
|Witch|2|4|
|Wizard|2|4|
)

head(
-
)

# Spells
## Heightening Additions
item (
# True Strike
## Spell 1
-
;Fortune, Divination
**Traditions** arcane, occult

**Cast** :a: Verbal

**Duration** until the end of your turn
-
A glimpse into the future ensures your next blow strikes true. The next time you make an attack roll before the end of your turn, roll the attack twice and use the better result. The attack ignores circumstance penalties to the attack roll and any flat check required due to the target being concealed or hidden.
-
**Heightened (4th)** You instead roll the attack three times.
)

item (
# Haste
## Spell 3
-
;Transmutation
**Traditions** arcane, occult, Primal

**Cast** :aa: Verbal, Somatic

**Duration** 1 minute
-
Magic empowers the target to act faster. It gains the quickened condition and can use the extra action each round only for Strike and Stride actions.
-
**Heightened (5th)** You can target up to 3 creatures.

**Heightened (7th)** You can target up to 6 creatures.

**Heightened (9th)** You can target up to 10 creatures, and the extra action can be used for any action (or as part of an activity) with the Move or Attack trait.

**Heightened (10th)** You can target up to 10 creatures, and the extra action can be used for any action (or as part of an activity) with the Move, Concentrate or Attack trait. Targets also gain an additional extra action which can be used to Stride or Step.
)

head(
-
)
# Items

## Elixir of Life
The following change is intended to rebalance elixir of life to smooth out their power level and make them more usable amongst parties of all levels, particularly low levels.

|Level|Name|Healing|Bonus to Saves|Price|
|-----|-----|-----|-----|-----|
|1|I|1d6+2|1|3|
|3|II|2d6+4|1|10|
|5|III|3d6+6|1|30|
|7|IV|4d6+9|1|70|
|9|V|5d6+12|2|150|
|11|VI|6d6+15|2|300|
|13|VII|7d6+18|3|600|
|15|VIII|8d6+21|3|1300|
|17|IX|9d6+24|3|2500|
|19|X|10d6+27|4|3000|
head(
-
)

# Age of Ashes

Below are feats only available in the Age of Ashes campaign.
## Class Feats
item (
# Pack Loyalty
## Feat 2
-
;Rare,Any
**Prerequisites** You have hand raised a Warg from its youth and earned its trust.

-
Your close bond with your Warg companion has earned an unwavering trust from the creature. It will willingly follow you into battle and follow your commands to the best of its ability.  Though the Warg is an intelligent creature, it functions as a young animal companion with the following abilities.

**Warg**
Str +2, Dex +3, Con +2, Int –1, Wis +1, Cha +0
**Language**: Any one spoken by master
**Size**: Medium
**Melee** (1 Action) Jaws, Damage 1d8 piercing, grab
**HP**: 6
**Skill**: Survival
**Senses**: low-light vision, scent(imprecise, 30 feet)
**Speed**: 40 feet
**Special**: grab(jaws)
###Support ability
**Pack Attack** Your strikes deal an additional 1d4 piercing damage so long as your target is threatened by your Warg Companion. If your animal companion is mature, this damage increases to 2d4. If your animal companion is nimble or savage, this damage increases by 2 or 3 respectively.

### Advanced Maneuver

**Avenging Bite**  :r: 
*Trigger:* A creature within reach of the warg’s jaws attacks one of the warg’s allies. 
*Effect:* The warg makes a jaws Strike against the triggering creature.

### Ranger
When you Hunt Prey, your animal companion gains the action’s benefits and your hunter’s edge benefit if you have one.
)
item (
# Pack Alpha
## Feat 6
-
;Rare,Any
**Prerequisites** Pack Loyalty
-
Your Warg companion grows up, becoming a mature Animal Companion. During an encounter, even if you don’t use the Command an Animal action, your animal companion can still use 1 action on your turn that round to Stride or Strike.
)


item (
# Incredible Pack
## Feat 10
-
;Rare,Any
**Prerequisites** Pack Alpha
-
Your Warg companion continues to grow and develop. It becomes a nimble or savage animal companion (your choice), gaining additional capabilities determined by the type of companion (page 214).
)
item (
# Specialized Pack
## Feat 16
-
;Rare,Any
**Prerequisites** Incredible Pack
-
Your Warg companion continues to grow in power and ability, and it is now cunning enough to become specialized. Your animal companion gains one specialization of your choice. (See the Animal Companion section on page 214.)
)
