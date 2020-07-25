# Mechanics

This table top roleplaying game is a d100 system. Meaning when there is an action to resolve that has a chance of failing we randomly determine a number between 1 and a 100 and then compare that to our character's ability and the relevant modifiers. We generate this number by rolling two ten sided dice with different marks for the 10s and 1s positions.

To preform a check we first find the relevant character attribute and set that as our **base target value**. For example if we were trying to hack a MEC we would use our Tech attribute. Then, depending on the situation, we apply bonuses and maluses to it, modifiers that add or subtract from the base target value to create our **target value**. For example shooting at another character in cover will apply a cover malus that lowers the target value, making it more difficult. Finally we roll a number and if we are equal to or under the target value we succeed.

#### Damage Rolls

Besides using d10s and d100s for randomization there is only one other relevant role. And that is the damage roll, which generally uses a d12 and sometimes a d10. Depending on the weapon's damage range we divide resulting roll of the d12 and round up to the nearest whole number (unless it exactly divides, for example 3 divided by 3 is 1). See the table below.

|Damage Range|Dice|Divide By|
|---|---|---|
|2|d10/d12|5/6|
|3|d12|4|
|4|d12|3|
|5|d10|2|
|6|d12|2|

## Attributes

Characters - player and enemy alike - have attributes. These are the core stats which inform what a character can do.

Some attributes every character has, like **health**, others only some characters have, like **psi**. Attributes that aren't listed for a character can be assumed to be 0.

There are three core attributes that almost all characters have that are commonly used for most checks:

* **Aim** - The ability to coordinate one's actions. Primarily used for aiming weapons and complex physical actions.
* **Will** - The ability to exert one's will. Primarily used for social situations and protecting against psionics.
* **Tech** - The ability to use one's skills. Primarily used for hacking technology and performing specialized tasks.

The other attributes, which cannot be checked are:

* **Health** - The amount of physical damage one can withstand. Describes the maximum health (but in general can also reference the current health). All characters have this.
* **Mobility** - The amount of distance one can cover. Describes the number of tiles a character can move in an action. Most characters have this (or a special rule instead).
* **Armor** - The innate amount of damage reduction, is never an innate attribute.

There are then some special attributes, which are rare for characters to have (though all members of a given species of alien often has one of these), which primarily have built-in special rules, and are sometimes checked:

* **Psi** - For those with psionics, the ability to project that power. This special attribute is the closest to the core attributes in that it is often checked.
* **Defense** - The innate protection one has available. A defensive modifier (a malus against other character's checks). Sometimes checked for withstanding extreme damage.
* **Dodge** - The ability to react quickly to danger. Primarily used in reaction to attacks to reduce the damage of incoming fire. Sometimes checked for reactions.
* **Crit** - The ability to hit just the right spot. Primarily used in combat as a chance to increase damage. Sometimes checked for luck or superskill.

There are many ways to modify these attributes contextually. Equipment often modifies these attributes for most combat situations, for example a laser sight increases the Crit attribute when firing *that weapon*. Hiding behind cover technically grants the character defense. The point here is that most characters will have 0 Dodge and 0 Crit outside of combat situations - even if they have the armor on - because those bonuses are granted by equipment that only applies to combat.

### Aim

Used for any check that requires coordination and physical skill (uncommon out of combat).

In combat, is primarily used for making attacks.

Aim for attacks uses a proficiency system. Without the relevant proficiency for the weapon in use automatically makes all attacks (even crits) with that weapon grazes (and normal grazes are misses).

Out of combat this can be used for checks of slight of hand and driving.

### Will

Used for checks relating to social situations and leadership. This is based off of the idea that to be a good leader or to talk to others requires willpower to face that situation. This is the Charisma stat.

In combat, is primarily used to resist psionics. It is subtracted from the Psi score of all psionic users (though it must be above 50 to begin making the Psi user less likely to succeed) in contested psionics.

Willpower checks for social situations will often suffer modifiers depending on the relative species of the parties. Notably it requires significant more willpower to talk to those that are more alien and those with psionics (on top of the powers psionics give).

The formula for Will penalties in social situations is:

* -5 Will, for every 25% distance in species.
* -5 Will, for extreme alien features (generally aliens from extreme environments).
* -5 Will, for talking those with obviously strong psionics (unless the user is also psionic).

This accounts for the general social unrest between different alien species, and between humans and aliens. For example a gatekeeper triggers all of these penalties for a general total of -30.

### Tech

(AKA Hack) Used for checks relating to situations which require specialized knowledge and skills. This is based off of the idea that most technical knowledge and training improves skills across the board, a thematic element of the XCOM universe. But also the extreme suffusion of technology and the use of it for solving most problems means skill in technology is the first important check.

In combat, is primarily used for hacking enemies and other utility actions (like medical care or repair).

Tech for use of equipment uses a proficiency system. Without the relevant proficiency for the equipment in use the user suffers a -50 Tech penalty (if the resulting tech score is below 0, the equipment cannot be used at all) for all rolls with the equipment. Most other equipment abilities (those that don't require rolls) will simply be unusable.

Tech for checks out of combat will often require specialized abilities to be performed at all. Which is to say if a character has a 70 in Tech but no Researcher, Doctor, Engineer, Hacker, Investigator, or similar abilities, then the character won't be able to make much use of that score.

### Health

### Mobility

### Armor

### Psi

Used for performing psionic abilities. Both in and out of combat.

The general formula for psionic skill checks is the difficulty of the psionic skill—usually 0 but may range from +20 to -50—plus the user's Psi score. For contested checks one subtracts the target's Will score and adds 50 (for the average Will power) as contested abilities are often trained to be contested.

Most Psionic citizens—especially alien ones—are expected to wear (self removable) Psi collars in public (outside of their specific neighborhoods or homes) which apply a -105 modifier to all Psi abilities and prevents the use of external focuses. Psi is often enhanced with focuses (generally called Psi AMPs), but these tools (weapons) are generally illegal and are only slightly more offensive than heavy arms (machine guns, grenade launchers) in most social situations. Psi AMPs can also increase psionic damage.

Unmodified sectoids and humans at peak skill can be expected to have as much as 100 Psi, though often between 60-80 is more common. With a Psi AMP and significant enhancement (genetic, cybernetic, and psionic) as much as ~160 can be reached (Avatars were 200).

### Defense

Used for resisting incoming damage through physical protection and autonomic processes. Both in and out of combat.

The primary use of this attribute is that it is subtracted from Aim for all attacks against the character. This is body armor, shielding, cover, or natural armor preventing the attack from connecting and doing much damage (the attack "hits" whatever is providing the defense to no effect).

The secondary use of this skill is for resisting diseases, toxins, poisons, explosions, hard vacuum and other similar situations. Generally the check for these situations starts at +50 and difficulty is subtracted or added depending on the specific situation.

Mutons are the main species to have innate Defense. Though it is often granted contextually through the use of cover, and sometimes armor and equipment, or by abilities. Cybernetic and genetic modification can also provide it.

### Dodge

Used for dodging incoming fire and making super human reactions. Both in and out of combat.

The primary use of this attribute is that it allows dodging fire in combat to prevent citical hits and reduce normal hits to grazing hits.

The secondary use of this skill is for reacting quickly in certain out of combat situations. In general a distinction is made between "intuitive" and "thinking" reactions. Only intuitive reactions can be made. For example someone making a sudden movement (deciding whether they are going for their weapon or maybe pushing a button or maybe just jumping up would be too much thinking, sudden movement would be the only cue) would allow for an intuitive reaction to restrain the person on a successful dodge roll. These checks often start at +50 and then modifiers for the difficulty of the situation. In general dodging damage can only be done if it can be seen comming, and an attack by an intelligent entity uses the normal dodge rolls.

Vipers are the main species to have innate Dodge. Though it is sometimes granted contextually through the use of armor and equipment, or by abilities. Cybernetic and genetic modification can also provide it.

### Crit

Used for performing exceptionally skillful actions. Both in and out of combat. This can be seen as a form of "luck" but is closer to "superskill".

The primary use of this attribute is that it allows scoring critical hits in combat.

The secondary use of this skill is for performing especially skillful actions in certain out of combat situations. Generally these are Tech or Will rolls with systemized results from abilities, which will also often grant the contextual Crit bonus, and the results.

Very few species have innate Crit (Etherals, Codexs, and Avatars). It is generally gained contextually through situations, equipment, or abilities. No known cybernetic or genetic modification can provide it.

## Combat

Combat is based off of the XCOM video games. It takes place on a grid of squares which are roughly 5 feet to a side.

### Turn Order

The turn order is a simple back and forth between the GM and the players. All of the players and any characters under their control will take all of their actions in any order. Then the GM will move all of their characters in whatever order (though they should make an effort to group them into factions if there is more than one group in involved).

Most characters get two actions per turn (Core Actions). Some actions will cause a character's turn to end, even if it is their first turn (Final Action). Some actions are full turn actions and require both actions to perform (Full Action).

Some actions are free actions and can be taken at any time (Free Action). And some actions are movement actions which can be taken during movement (Move Action).

#### Actions

There are some basic actions that all characters - in general - can be expected to be able to perform.

##### Attack (Final Action)

Using an equipped weapon the player may make an attack.

##### Move (Core Action)

The player may move their mobility score.

##### Dash (Full Action)

The player may move twice their mobility score. During this time they will have +30 Dodge against reaction actions.

### Attacks

Performing an attack does the following steps:

- Choose a target you can see.
- Attack
    - Determine the target's defense.
        - Innate defense stat.
        - Apply one form of cover.
            - The enemy is not in cover or is flanked.
            - Half-Cover provides +20 defense against ranged attacks.
            - Full Cover provides +40 defense against ranged attacks.
        - Other conditions.
    - Calculate the target value.
        - Aim is the base target value.
        - Subtract the target's defense.
        - Add any bonuses.
            - Melee attacks get +20.
            - If the enemy is marked, and it's a ranged attack, get +15.
            - Other conditions.
    - Make the Aim check against the target value.
        - If it fails, the attack is over.
- Dodge/Crit - can be rolled simultaneously
    - If the defender has Dodge they check it.
    - If the attacker has Crit they check it.
        - +50 Crit if the enemy is flanked.
    - If neither Crit nor Dodge are successful, continue to damage.
    - If both Crit and Dodge are successful, some abilities may trigger, continue to damage.
    - If only Crit is successful then the attack is a critical hit, some abilities may trigger.
    - If only Dodge is successful then the attack is a grazing hit, some abilities may trigger.
- Damage
    - Take the weapons base damage.
    - Roll damage based on the damage range.
    - Modify based on hit type:
      - Grazing Hit: Divide total damage by 2 (round up).
      - Critical Hit: Add the damage range value (e.g. a maximum possible roll, without base damage) to the damage.
    - Subtract the target's armor from the damage (minimum damage value is 1).
    - Apply the damage to the targets health, some abilities may trigger.

### Movement

Movement is one point of mobility per square traversed horizontally and vertically. And three points of mobility per two squares traversed diagonally: this is spent 2 points of mobility for the first diagonal, 1 point for the second diagonal, and repeat.

Some move actions (kicking down doors) can be done during movement for the cost of mobility points. And some (breaking through windows) can be done for free.

Some terrain is rough (like that which requires parkour over) and requires double mobility points to enter each square.

Some common move actions that can be done during movement:

##### Equipping (Move Action; 4/Varies)

In general it costs 4 movement points to change a piece of equipment to something you have at the ready. Some heavy weapons require 6 or 8. (Some sidearms are free to equip, but you will need to equip your main weapon again).

##### Take (Move Action; 4)

In general to take a small loose item from the enviroment and either equip it or store it takes 4 movement points.

##### Carry (Move Action; 10)

To pick up a person or other heavy item requires 

(see the the weapon tables for the points necessary), picking people up (10 movement), or putting them down (2 movement; free action to drop).
