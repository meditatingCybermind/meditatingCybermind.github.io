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

# Classes
## Alchemist
note (
# Alchemist's Alchemical DC Adjustments
* Remove the Potent Poisoner Feat
* Remove the Powerful Alchemy Feat
)

### Class Features
note (
# Infused Reagents
The DC of your alchemical items crafted with infused reagents is equal to your alchemist class DC.
)

# Skills
## Crafting

note (
# Craft 
In the feat body, change:
* “You must spend 4 days at work, at which point you attempt a Crafting check.” 

to

* “Find the full price of the item. You must spend a number of days equal to the full price of the item divided by that amount of gold gained by earning income in table 4-2 per day or 4 days whichever is lower. At this point, you attempt a Crafting check.”
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

### Fighter
item (
# Reactive Shot
## Feat 4
-
;Fighter
Your foes trigger an attack of opportunity with your ranged weapons as normal as long as they are within your first range increment. Strikes made in this manner suffer a -4 circumstance penalty to hit.
)

### Archetypes
**Level reductions from general changes are already applied.**

#### Spellcasters
5 feats have been combined into one editorially for brevity. "Tradition Expansion" is a representation of 1 of 5 feats you can take for your spellcasting archetype.

Replace the name **TRADITION** with Bloodline/Occult/Divine/Primal/Arcane for Sorcerers/Bard/Clerics/Druids/Wizards respectively. Replace **CLASS** with the name of the class in a similar manner.
item (
# TRADITION Expansion
## Feat 10
-
;Archetype
**Prerequisites** Expert CLASS Spellcasting, TRADITION Breadth
-
You can cast more spells each day. Increase the spell slots you gain from CLASS archetype feats by 1 for each spell level other than your highest spell level
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
|Sorcerer|3|6|
|Wizard|2|4|
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


# Items

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
**Pack Attack** Your strikes deal an additional 1d4 piercing damage so long as it is threatened by your Warg Companion.

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