# Gear and Items
Your character has gear slots. You can equip one item per slot before a run. You cannot change gear during a run.

## Item Gems
Each pice of gear is a die, with 6 sides. Each gem the item has is mapped to one side of the die.

An item can have fewer than 6 gems, but not more than 6.

By default items will have fewer gems than faces. They can fill in the blank faces during a run with **Blessings** (see below)

## Item DNA
Slot: Where it goes
Base: The base item type. Dictates some of the default gems
Affixes: Prefixes and Suffixes that change the item
Name: a string
Image: a transparent PNG
Border: a transparent PNG or just a color
Background: an image or maybe an animated thing

## Item Blessings
During the run you can get a blessing of a specific mana. This will add the gem to one of the item's die faces. The blessing is removed at the end of the run.

## Item Affixes
Here are some sample ideas for item affixes:

### Basic Bonuses
 - +10 max hp
 - +1 Fire Resistance
 - +1 Ice Mastery (mastery gives you tearing for your Ice attacks)
 - Add a 🌀 gem

### Skill Modifiers

 - Your *Offensive Fire* skills deal +3 damage
 - The first *Ice Cooldown* skill you use each combat has its cooldown refreshed by 1

### Mana Based Modifiers
 - If you spend activate a 🌀 bonus on your turn, heal for 2 HP
 - Every third time you spend a 🔥, gain 1 reroll point
 - Whenever you roll a ☀️ deal 1 damage to a random enemy

### Slay the Spire
 - Every 3 turns, gain 5 Shield

# Examples

>**Helmet**  
>Slot: Head  
>Gems: 🌀, ☀️  

>**Queen's Helmet of Divinity**  
>Slot: Head  
>Gems: 🌀, ☀️, ☀️  
>+5 to Max HP  


>**Terror Dome**  
>Slot: Head  
>Gems: 🌀, ☀️, 🔥  
>+2 Fire Resistance  
>Your *Ice Offensive* skills gain +2 Proven  
>Every 5th turn, gain 12 Shield  
