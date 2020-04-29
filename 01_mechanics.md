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

* **Health** - The amount of physical damage one can withstand. Describes both the maximum health and the current health. All characters have this.
* **Mobility** - The amount of distance one can cover. Describes the number of tiles a character can move in an action. Most characters have this (or a special rule instead).
* **Armor** - The innate amount of damage reduction. Few characters have this.

There are then some special attributes, which are rare for characters to have (though all members of a given species of alien often has one of these), which primarily have built-in special rules, and are sometimes checked:

* **Psi** - For those with psionics, the ability to project that power. This special attribute is the closest to the core attributes in that it is often checked.
* **Defense** - The innate protection one has available. A defensive modifier (a malus against other character's checks). Sometimes checked for withstanding extreme damage.
* **Dodge** - The ability to react quickly to danger. Primarily used in reaction to attacks to reduce the damage of incoming fire. Sometimes checked for reactions.
* **Crit** - The ability to hit just the right spot. Primarily used in combat as a chance to increase damage. Sometimes checked for luck or superskill.

There are many ways to modify these attributes contextually. Equipment often modifies these attributes for most combat situations, for example a laser sight increases the Crit attribute when firing *that weapon*. Hiding behind cover technically grants the character defense. The point here is that most characters will have 0 Dodge and 0 Crit outside of combat situations - even if they have the armor on - because those bonuses are granted by equipment that only applies to combat.

### Aim

Used for any check that requires coordination and physical skill.

Primarily used for making attacks during combat.

### Will

### Tech

### Health

### Mobility

### Armor

### Psi

### Defense

### Dodge

### Crit

## Combat

Combat is based off of the XCOM video games. It takes place on a grid of squares which are roughly 5 feet to a side.

### Turn Order

The turn order is a simple back and forth between the GM and the players. All of the players and any characters under their control will take all of their actions in any order. Then the GM will move all of their characters in whatever order (though they should make an effort to group them into factions if there is more than one group in involved).

Most characters get two actions per turn. Some actions will cause a character's turn to end, even if it is their first turn. Some actions are full turn actions and require both actions to perform.

Some actions are free actions and can be taken at any time. And some actions are movement actions which can be taken during movement.

#### Actions

There are some basic actions that all characters - in general - can be expected to be able to perform.

##### Attack (Basic Action)

Using an equipped weapon the player may make an attack.

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
      - Critical Hit: Add the damage range value (e.g. a maximum possible roll) to the damage.
    - Subtract the target's armor from the damage (minimum damage value is 1).
    - Apply the damage to the targets health, some abilities may trigger.
