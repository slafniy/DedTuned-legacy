# DedTuned balance mod for Larian's Baldur's Gate 3 (WIP)
The final goals of this mod:
- Make Honor mode slightly harder
- Eliminate as many abuses as possible
- Make too weak abilities stronger
- Make too strong abilities weaker
- Balance out need of resting for different classes
- Remove concentration as much as possible, leave it only for really strong spells
- Add downside of using Illithid Powers because devs forgot to do it :)

## Changelist
### Experience reward
Required XP per level increased (around +27% total) because of two reasons:
- Do not let player to over-level enemies too much
- Bring more sense to XP rewards in Act III (in stock game player reaches level 12 at the beginning of Act III and progress stops)  

Expected levels:
 - 5 at the Act I before Rosymorn Monastery 
 - 6 at the end of Act I
 - 8 at the end of Act II 
 - 12 at the end of Act III

### Common spells
#### Guidance
- No concentration
- Lasts 3 turns instead of 10

Note: it's frustrating to break concentration to buff this out of combat just to pickpocket something, and it's not so strong for concentration.

#### True Strike
- No concentration
- Cooldown once per combat

Note: this is almost unusable cantrip out of the box. 

#### Divine Favour (Paladin, War Domain Cleric)
- No concentration
- Lasts 2 turns instead of 3

### Feats
#### Tavern Brawler
- Does not add attack roll bonus  

Note: it`s pretty strong damage boost for one feat, an attack roll bonus makes it imbalanced.

#### Great Weapon Master
- Attack roll penalty reduced to -3 (was -5) for levels 4-7
- Damage bonus reduced to 6 (was 10) for levels 4-7

Note: this is both too strong damage bonus for low levels if you managed to overcome attack roll penalty and too weak if you don't.
This change slightly balances it.

#### Sharpshooter
- Attack roll penalty reduced to -3 (was -5) for levels 4-7
- Damage bonus reduced to 6 (was 10) for levels 4-7

Note: same changes due to same reasons as for Great Weapon Master.

#### War Caster
- You also can pick INT, WIS or CHA +1 bonus  

Note: this is must have feat for any caster on low levels, but it's painful to pick this only for utility without any other bonus (no, reaction focus does not make it any better). 
Also, there are too few feats with stat bonus for casters comparing to non-casters.

### Classes
#### Fighter Champion
- Improved Critical passive gives -2 critical threshold instead of -1

Note: this subclass is too weak comparing to Battle Master, so I bring him this buff.

#### Barbarian Berserker
- Enraged Throw now gives stack of Frenzied Strain as Frenzied Strike always does.

Note: throwing build for Berserker is insanely strong, this change alongside of Tavern Brawler nerf should calm down it a little.

#### Cleric War Domain
- War Priest Action Points reset on Short Rest instead of Long Rest  
Note: additional attack as bonus action isn't THAT strong.

### Pickpocketing
- You cannot pickpocket Volo and Jergal anymore

Note: pickpocketing without any risk doesn't make sense.

### Honor mode boost
- HP boost increased from 30% to 160% (x2 HP from stock Honor)
- Raphael HP set to 1666
- Honor attack roll bonus for enemies increased from 2 to 3

Note: HP boost should give a chance for enemies to use their abilities and not being slain on first turn.
Attack bonus should make enemies slightly more dangerous.

### Initiative
- Initiative die changed from d4 to d8
Stock d4 removes any randomness in turn order and makes DEX stronger than it should be, but dnd5e d20 kills initiative bonuses at all.
d8 provides some level of randomness but with respect of initiative bonuses, so you can expect your Barbarian and Gloom Stalker are first in most situations.

### Resting
- Partial Rest does not restore any resources and only gives 25% HP  
Note: this is an attempt to eliminate partial resting infinite resource regen abuse
- Short Rest restores 2 level I slots and 1 level II slot  
Note: this is a little buff for classes with spell slots intended to make them closer to non-casters in terms of long resting needs.
- Long Rest requires 250 supplies instead of 80  
Note: default cost does not make any sense because you cannot run out of supplies even if you are resting after every little combat. 

### Multiclassing
- Multiclassing is forbidden  
Note: first, it's impossible to balance out Multiclassing with my experience, knowledge and tools. 
Second, I personally don't like it as a concept because it looks like abusing combination of too strong low-level features which are essential for pure class and could not be nerfed too much.
Proper multiclassing should include some lore limitations, karma mechanics of something else, which is not the case in BG3.

### Tiredness - new mechanics
An attempt to create a new mechanics, which forces party to rest more often. Not a direct adaptation of dnd5e Exhaustion.  
In a combat characters will get Tiredness stacks, which on some point lead to various consequences:
- Level 1 (30+ stacks): slight fatigue. A penalty to attack rolls, saving throws, ability checks, skill checks and spell DC
- Level 2 (40+ stacks): WIP
- Level 3 (50+ stacks): Uncontrollable sleep. Every turn character must perform CON saving throw or will fall asleep
- Level 4 (60+ stacks): Death.

Long Rest (with supplies) removes all Tiredness stacks, Short Rest removes 20. 