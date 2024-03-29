# terminology

- main attack: physical unit attack by number in lower left corner, not by strike, hunt, etc
- permanently: until win/lose/draw of the current battle
- at start of turn: at start of player's turn, even if the unit's cooldown greater than zero (i.e., not activated yet)
- opposing enemy unit = enemy unit directly (vertically) across
- opposing adjacent enemy units = enemy units to the left and right of opposing enemy unit


# skill notes

## absorb N

- does _not_ heal for absorbed amount
- nullifies up to N damage from skills each turn
  - counter
  - mortar
  - poison
  - strike
- does not nullify damage from skills
  - hunt
  - swipe


## bravery

- can be used to complete daily quests which require valor skill
  - each activation of bravery counts towards valor for quest


## entrap

- when "on attacked", it is not activated if enemy assault is destroyed by main attack
- adds additional counter skill to unit (additive power: counter 5 + entrap 5 + entrap 5 = counter 15)


## hunt N

- activates if attack greater than zero
- leftmost enemy assault is damaged by N, and amount can be reduced by enemy's protect/barrier
- hunt cannot be evaded


## mimic

- only targets enemy units with mimicable skills
- is not affected by enemy's evade skill


## sabotage N

- reduces power of enemy unit's skills by N
  - fortify
  - heal
  - rally
  - strike
- some skills are not affected
  - allegiance
  - berserk
  - corrosive
  - evade
  - hunt
  - leech
  - mark
  - scavenge


## summon

- activates once when cooldown reaches zero for the first time
- new unit is summoned even if existing unit is jammed


## sunder N

- weakens enemy unit's main attack by X
- sundered units cannot gain attack from:
  - allegiance
  - rally
- sundered units can gain attack from:
  - berserk
- can be used to complete daily quests which require weaken skill
  - each activation of sunder counts towards weaken for quest


## swipe

- activates if attack greater than zero, even if protect/barrier on opposing enemy unit causes damage to be zero
- for opposing adjacent enemy units, armor does not reduce damage, but protect/barrier does
- for opposing adjacent enemy units, enfeebled units do take increased damage
