head (
# Houserules
A collection of rule adjustements and additional feat options.
-
)

# General Changes

* All class feats with a level requirement of 2 now have a level requirement of 1.
* All archetype feat level requirements reduced by 2, to a minimum of 1.
* Additional Spell levels gained from Basic, Expert, and Master spellcasting multiclass feats are available 2 levels sooner.
* All characters have an additional class feat at level 1.
head(
-
)

# Ancestries
## Elf
note (
# Ancient Elf
Can now select any level 2 (now 1) archetype at level one, not just multiclass archetypes. All other restrictions still apply.
)

# Classes
## Alchemist
note (
# Alchemist's Alchemical DC Adjustments
* Remove the Potent Poisoner Feat
* Remove the Powerful Alchemy Feat
)
note (
# Proficiencies
* Alchemical Weapon Expert now granted at level 5.
* Alchemical Expert now granted at level 7.
* Alchemical Weapon Master (new) granted at 13
* Alchemical Master now granted at 15
* Alchemical Weapon Legend (new) now granted at 17
* Alchemical Legend (new) now granted at 19
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
### Feats
note (
# Additional Feats
Add the Poison Weapon (6), Improved Poison Weapon (8), and Deadly Poison Weapon (12) to the alchemist feat list. For Alchemists, Deadly Poison Weapon is Common.
)
note (
# Subtle Delivery
Text now reads as:
Your Strikes can apply injury poisons even if they deal no damage due to a creature's resistance. If you critically succeed at an attack roll using a weapon you've poisoned, the target treats the save as one degree worse.
)
-
## Fighter
### Feats
item (
# Reactive Shot
## Feat 4
-
;Fighter
Your foes trigger an attack of opportunity with your ranged weapons as normal as long as they are within your first range increment. Strikes made in this manner suffer a -4 circumstance penalty to hit.
)
-
## Oracle
note (
# Cursebound Trait
##Wording Changed:
Spells with this trait increase the severity of your oracular curse **when cast while your focus pool is not full, or if you will it to increase.** Usually only revelation spells have this trait. You can’t cast a cursebound spell if you don’t have an oracular curse.
)
note (
# Focus Pool
You have a focus pool of 1 + the number of focus spells you know, to a maximum of 4. 
)

## Wizard
note (
# Spell Subtitution
In light of the spellcasting changes below giving Spell Substitution as written in the CRB to all prepared spellcasters, the text of the Spell Subtitution Thesis changes as follows:

- Once per day as a free action, you may swap a spell you have prepared in one of your spell slots for any spell you know in your spellbook. You must be holding your spellbook to do this. If you are a master in wizard spellcasting, you may do this twice per day, and if you are legendary you may do it three times per day.

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

## Athletics
note (
# Disarm
- Duration of the penalty increased to end of their next turn. They can end it early with an Interact action. 

The success entry for disarm now reads as:
You weaken your target's grasp on the item. Until the end of that creature's turn, attempts to Disarm the target of that item gain a +2 circumstance bonus, and the target takes a -2 circumstance penalty to attacks with the item or other checks requiring a firm grasp on the item.
)

## Crafting
note (
# Craft 
In the feat body, change:
* “You must spend 4 days at work, at which point you attempt a Crafting check.” 

to

* “Find the full price of the item. You must spend a number of days equal to the full price of the item divided by that amount of gold gained by earning income in table 4-2 per day or 4 days whichever is lower. At this point, you attempt a Crafting check.”
)

## Medicine
note (
# Continual Recovery and Treat Wounds
Treat wounds cooldown is now 10 minutes instead of 1 hour.

Continual Recovery feat removed.
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
-
## Class Feats
### any
note (
# "Any" Trait
A feat with the "Any" trait can be taken as a class feat or archetype feat on any class.
)

item (
# :f: Fast Hands
## Feat 1
-
;Flourish,Any
**Trigger** When you would perform an interact action.
-
You may instead choose to perform it as a free action.
)
-

### Wizard
item (
# :a: Still Spell
## Feat 4
-
;Concentrate,Metamagic,Wizard
-
You've learned how to cast many of your spells with complex spellwork weaved amidst the words of power required to cast them. If the next action you use is CAsting a Spell that has a somatic component and at least one other component, you can remove the Somatic component. This makes the spell castable when you cannot move your hands.
)
-




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
You have a focus pool equal to the number of focus spells you know, to a maximum of 3.
)
-
## General Spellcasting Changes
### Prepared Spellcasters gain Spell Substitution
All prepared spellcasters may spend 10 minutes to swap a spell out, as the Wizard's Spell Substitution Thesis from the CRB.

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
|Magus|1|3|
|Oracle|2|5|
|Sorcerer|3|6|
|Summoner|1|3|
|Witch|2|4|
|Wizard|2|4|
)

head(
-
)

# Spells
## Rewrites
item (
# Read Aura
## Spell 1
-
;Cantrip, Detection
**Range** 30 feet; **Targets** 1 object

**Traditions** arcane, occult, divine, primal

**Cast** 1 minute

-
You focus on the target object, opening your mind to perceive magical auras. When the casting is complete, you know whether that item is magical, and if it is, you learn the school of magic and you can immediately attempt to identify it instantly with a +1 status bonus to the check.
If the object is illusory, you detect this only if the effect's level is lower than the level of your read aura spell.
-
**Heightened (3rd)** You can target up to 10 objects.

**Heightened (6th)** You can target any number of objects.
)

## Heightening Additions
item (
# Dimension Door
## Spell 4
-
;Conjuration, Teleportation
**Traditions** arcane, occult

**Cast** :aa: Verbal, Somatic

-
Opening a door that bypasses normal space, you instantly transport yourself and any items you’re wearing and holding from your current space to a clear space within range you can see. If this would bring another creature with you—even if you’re carrying it in an extradimensional container—the spell is lost.
-
**Heightened (5th)** The range increases to 1 mile. You don’t need to be able to see your destination, as long as you have been there in the past and know its relative location and distance from you. You are temporarily immune for 1 hour.

**Heightened (7th)** As 5th level, but the range increases to 10 miles and the cast time increases to 3 actions with a material component. The teleportation leaves a magical residue behindfor 10 minutes which allows someone trained in arcana or occultism to attempt a hard Identify Magic check vs your spell DC to determine which direction you went and precisely how far. If they have also been to this location or near it, they immediately know where you went.

**Heightened (9th)** As 7th level, but the range increases to 100 miles and the temporary immunity increases to 8 hours. The residue remains for 1 hour.

**Heightened (10th)** As 9th level, but the range increasses to 1000 miles and the temporary immunity increases to 24 hours. The residue remains for 8 hours.
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



head(
-
)
# Items

## New Items

item (
# Bag of Shared Infusions
## Item 3
-
;Conjuration, Extradimensional, Magical
-
This bag was invented by frustrated alchemists and their magical companions, and is commonplace amongst adventuring parties worth their salt. This extra small bag of holding has a small pocket just inside its mouth containing a single pouch that can be clipped to a belt or other article of clothing and looks to be large enough to hold a single potion. When one of these pouches is removed from the small pocket inside the bag, another one is immediately created. These pouches are linked to the Bag of Shared Infusions they were pulled from. Up to 10 pouches can be linked at a time, and if an 11th pouch is attempted to be pulled from the Bag of Shared Infusions, the oldest pouch is instantly destroyed.

The pouches are empty. Someone with a linked pouch can interact to draw from the pouch by imagining the pouch containing a single alchemical item with the Infused trait from the pouch; this action gains the concentrate trait. If that item exists in the Bag of Shared Infusions, the item instantaneously appears in the shared extradimensional space of the pouch and can be drawn normally as part of the interact action. Before the item appears, the owner of the Bag of Shared Infusions can mentally interrupt the process as a free action, and in that case the interact action is cancelled and the action is otherwise still available.

(In effect, this explains away "I'm gonna give each of you 3 elixirs, and im gonna give this guy a couple poisons, and im gonna give you a couple posions too, and...")
)

-

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
