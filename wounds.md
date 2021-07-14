# Wounds Instead of HP
All damage numbers you take are converted to "wounds". Wounds have different severity (light, major, critical, deadly, etc). The damage is compared to your **Toughness** score to determine wound severity. If damage is <= 25% of Toughness it could be Light, if it's double your Toughness it could be Critical. Stuff like that.

### Examples
Your Toughness is 10 and you take 2 damage. You gain a Light Wound

Your Toughness is 10 and you take 11 damage. You suffer a Major Wound.

Your Toughness is 10 and you take 500 damage. You suffer a Mortal Wound.

### Wounds Bar
Each wound in your wound bar takes up sapce based on its severity. When your bar is full you die.

```
Maximum: [=======================================]
Current: [L][L][ M ][ Crit ]
```

### Wounds as Design Space
Game text to show the space:

 - Deals +1 damage for every Wound on the target
 - Fully remove your most severe Wound
 - Deals +10 damage if target has a Critical Wound
 - Reduce all your wounds by 1 severity

### Wound Tags
Wounds could gain tags based on the source of damage. You are hit by Fireball for 325 damage against your 842 Toughness. You gain a Minor Wound with the "Fire" tag. Abilities could use tags like so:

>**Cooling Breeze**: Treat a random wound, prioritizing *Fire* wounds. *Fire* wounds are reduced by an extra severity.

They could also be inheritently mechanical. You get stabbed by *Tainted Blade* and gain a Major Wound with the tag *Poison*.

>**Poison**: 25% chance at the start of your turn to increase this wound by one severity.
