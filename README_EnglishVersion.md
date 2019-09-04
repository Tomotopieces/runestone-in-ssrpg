# Stone Story RPG Rune Tutorial
**Rune is a item that adds special attributes to the equipment in Stone Story RPG.**

**This tutorial based on version `beta1.6~1.8`**


## Rune List
Rune`sign` | Special effect`Affixes` | Overcome | Location | Boss | Weakness
:-: | :-: | :-: | :-: | :-: | :-:
Stone`o` | Critical | Null | Valley | Xyloalgia | Null
Poison`∞` | Weak`Pp` | Vigor`❤` | Cave | Bolesh | Ice`❄`
Vigor`❤` | Lifesteal`Lh` | Aether`＊` | Forest | Angry Shroom | Poison`∞`
Aether`＊` | Unmake`Uu` | Fire`φ` | Crypt | Pallas | Vigor`❤`
Fire`φ` | Burn`Ff` | Ice`❄` | Mine | Bronze Guardian | Aether`＊`
Ice`❄` | Chill`Ii` | Poison`∞` | Icy | Hrímnir | Fire`φ`
Poison`∞` | Weak`Pp` | Vigor`❤` | Temple | Nagaraja | Ice`❄`

*Note1: can get stone wand in all locations.*

*Note2: Uppercase affixes means active effect (affect when attacking foes), lowercase affixes means passive effect (affect when attacked by foes).*

#### overcome relationship
![克制关系](https://github.com/Tomotopieces/runestone-in-ssrpg/blob/master/%E5%B1%9E%E6%80%A7%E5%85%8B%E5%88%B6%E5%85%B3%E7%B3%BB.png "克制关系")

#### General Affixes
affixes | Special Effect
:-: | :-:
Aa | add armor when encounter overcome foes
Dd | make more damage to overcome foes



## Double Affixes
Equipment with both general affixes and special affixes.
> Example1: dP Poison Hammer, make a little more damage to poison foes, and when you attacked foes (not only poison foes), down its damage for a while.

> Example2：A Aether Hammer, not double affixes equipment, add armor when encounter aether foes.

*Note1: Affixes A or affixes D can't appear in double affixes, in other words, no DL Big Sword.*

*Note2: The first letter of double affixes must be lower case.*


## Check Rune Affixes
**1.All `Rune` has `Double Affixes`, a general affixes and a special affixes**

> Example: poison rune has 4 affixes type: dP, dp, aP, ap.

Take poison rune as an example, x may be a or d, y may be p or P.

Left | Right | Result
:-: | :-: | :-:
∞ | oStaff | xyStaff

**2.a and A are mutually exclusive，d and D are mutually exclusive**

Rune with affixes a can't make equipment with affixes A, rune with affixes d can't make equipment with affixes D.

Only rune with affixes a can make equipment with affixes D, only rune with affixes d can make equipment with affixes A.

*Note: `Staff`, not wand.*

## Control the Affixes
Both two affixes can mutate by Moondial Stone, or by drpo.

*Note: Moondial Stone can appear all reasonable affixes.*

## Affixes Cover
When the affixes of the rune made by Fissure Stone is `different from the runes in pack`, new affixes will cover the old type.
> Example: affixes of poison rune in pack is ap, Break apart a poison Staff with affixes dP, affixes of poison rune in pack will became dP.

## Fake mutate of Affixes
When the equipment can't get/compatible current affixes of rune, affixes of the equipment will happen fake mutate, but the affixes of rune have no change.
General affixes will change the letter, special affixes will change to its upper/lower case.
> Example: Left ap∞rune, Right oSword, Get dP∞Sword, because Sword can't get affixes a and affixes p.

Affixes Compatible List(sS means special affixes)

Compatibility | Sword | Wand | Big Sword | Heavy Crossbow | Shield | Hammer | Staff
:-: | :-: | :-: | :-: | :-: | :-: | :-: | :-:
a | × | × | × | × | √ | √ | √
A | × | × | × | × | √ | √ | √
d | √ | √ | √ | √ | × | √ | √
D | √ | √ | √ | √ | × | √ | √
s | × | × | × | × | √ | √ | √
S | √ | √ | √ | √ | × | √ | √

*Note: Hammer and Staff can get all type affixes, this is the reason why we use Staff to test the affixes of rune.*

## Fuse Example
Left | Right | Result | Note
:-: | :-: | :-: | :-:
ap∞ | oHammer | ap∞Hammer | Rune on left, get double affixes
oHammer | dp∞ | A∞Hammer | Rune on right, get general affixes
dh❤ | oBig Sword | dL❤Big Sword | Fake mutate, Sword can't get affixes h
oWand | afφ | DφWand | Fake mutate, wand can't get affixes A

## Others
1. In fuse, left affixes will cover right affixes.
