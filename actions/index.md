# actions
> how characters do things

ACTIONS represent anything that a CHARACTER can do.
Every ACTION fits into an ACTION TYPE.
ACTION TYPES define cost, rolls, and outcomes.

Some ACTIONS have RESULT ROLLS.
> things that are easy enough to do that you wont fail at them dont need rolls

Some ACTIONS have POTENCY ROLLS.
> things that have stable outcomes dont need rolls

FULL and PARTIAL ACTIONS can be done within TIMED EVENTS each TURN.
EXTENDED ACTIONS take around 2 hours.

FULL ACTIONS use normal equations for ROLLs.
PARTIAL ACTIONS only use negative changes to ROLLs.
ACTIONS coming from an CHARACTER using a PARTIAL ACTION cannot contribute any modifiers, and use only NAT ROLLS for derriving roll outcomes.
this applies to RESULT and POTENCY ROLLs.

---

## use
A CHARACTER does something minimal to a TARGET.
> pressing a button, lighting a fuse  

**cost:** PARTIAL  

**valid targets:**  
CHARACTER, BODY SLOT, ITEM, TILE

**result roll (challenge rating):**  
varies per TARGET  

**potency roll:**  
ITEM’s POTENCY ROLL  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
–  

---

## attack
A CHARACTER inflicts a TARGET with harm.
> stabbing, punching, fireballing, magically melting someone  

**cost:** FULL / PARTIAL  

**valid targets:**  
CHARACTER, BODY SLOT, ITEM, TILE

**result roll (challenge rating):**  
TARGET’s EVASION  

**potency roll:**  
TOOL’s POTENCY ROLL  

**peak:**  
–  

**blunder:**  
your TOOL is damaged by 1 MAG  

**notes:**  
–  

---

## help 
A CHARACTER assists another ACTION by contributing POTENCY.
> helping someone do any ACTION, getting weird with it  

**cost:** FULL / PARTIAL  

**valid targets:**  
CHARACTER (not yourself)

**result roll (challenge rating):**  
–  

**potency roll:**  
relevant PROF ROLL  

**peak:**  
one extra POTENCY ROLL can be made  

**blunder:**  
–  

**notes:**  
> you can help with either the RESULT or the POTENCY roll  

---

## defend
A CHARACTER increases the EVASION of a TARGET.
> shielding yourself, guarding an ally  

**cost:** FULL / PARTIAL  

**valid targets:**  
CHARACTER

**result roll (challenge rating):**  
–  

**potency roll:**  
relevant PROF ROLL  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
adds +POTENCY to EVASION for 1 TURN  

---

## grapple
A CHARACTER restrains or controls a TARGET physically.
> restraining, wrestling, holding someone back, pushing a guy a little  

**cost:** FULL / PARTIAL  

**valid targets:**  
CHARACTER

**result roll (challenge rating):**  
10 + TARGET’s STR BONUS + BRAWN MAG − size delta  

**potency roll:**  
–  

**peak:**  
add another stack of GRAPPLED to the TARGET  

**blunder:**  
the GRAPPLED STATUS is cleared from the TARGET  

**notes:**  
–  

---

## inspect 
A CHARACTER studies a TARGET using a PROFICIENCY.
> looking for clues, reading an enemy, studying a spell  

**cost:** FULL / PARTIAL  

**valid targets:**  
CHARACTER, BODY SLOT, ITEM, TILE, REGION TILE, WORLD TILE

**result roll (challenge rating):**  
varies for TARGETs trying to hide  

**potency roll:**  
relevant PROF ROLL  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
–  

---

## communicate 
A CHARACTER communicates information or intent.
> giving directions in battle, taunting, bartering  

**cost:** FULL / PARTIAL  

**valid targets:**  
CHARACTER, REGION TILE

**result roll (challenge rating):**  
–  

**potency roll:**  
relevant PROF ROLL  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
–  

---

## dodge
A CHARACTER focuses on avoiding danger.

> quick footwork, evasive movement  

**cost:** FULL / PARTIAL  

**valid targets:**  
CHARACTER (self)

**result roll (challenge rating):**  
–  

**potency roll:**  
relevant PROF ROLL  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
adds SPEED MAG ROLL to EVASION for 1 TURN  

---

## craft
A CHARACTER creates an ITEM from materials.
> making potions, weapons, armor, decor, small scale items  

**cost:** EXTENDED + ITEM(s)  

**valid targets:**  
ITEM (crafted item)

**result roll (challenge rating):**  
varies per recipe  

**potency roll:**  
relevant PROF ROLL  

**peak:**  
increase the MAG of the CRAFTED ITEM by 1  

**blunder:**  
an additional EXTENDED ACTION is consumed  

**notes:**  
–  

---

## sleep
An organic CHARACTER rests to recover.
> sleeping, hibernation, stasis states  

**cost:** EXTENDED + 1 optional VIGOR  

**valid targets:**  
CHARACTER (self)

**result roll (challenge rating):**  
– (varies when diseased)  

**potency roll:**  
VIGOR MAG ROLL + CON BONUS  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
gains 1 VIGOR  
procs HEAL if VIGOR is expended  

---

## repair
A mechanical CHARACTER restores function.
> repairing limbs, tuning, cleaning mechanical parts  

**cost:** EXTENDED + 1 optional VIGOR  

**valid targets:**  
CHARACTER (self), BODY SLOT

**result roll (challenge rating):**  
– (varies for broken parts)  

**potency roll:**  
VIGOR MAG ROLL + CON BONUS  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
gains 1 VIGOR  
procs HEAL if VIGOR is expended  

---

## move
A CHARACTER spends time changing position.
> traveling on tiles, world travel, sprinting in battle  

**cost:** none / FULL / EXTENDED  

**valid targets:**  
TILE (TIMED EVENT), REGION TILE or WORLD TILE (EXTENDED)

**result roll (challenge rating):**  
–  

**potency roll:**  
–  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
1 ACTION may be spent to reset movement speeds in battle  

---

## work
A CHARACTER performs general labor.
> service jobs,  large scale crafting, researching, updating spell slots  

**cost:** EXTENDED  

**valid targets:**  
ITEM, TILE, REGION TILE

**result roll (challenge rating):**  
varies per job  

**potency roll:**  
relevant PROF ROLL (if it matters)  

**peak:**  
increase payout by 50% for this ACTION  

**blunder:**  
decrease payout by 50% for this ACTION  

**notes:**  
–  

---

## guard
A CHARACTER secures and watches an AREA.
> standing watch, protecting, alerting allies  

**cost:** EXTENDED  

**valid targets:**  
TILE, REGION TILE, WORLD TILE

**result roll (challenge rating):**  
–  

**potency roll:**  
relevant PROF ROLL  

**peak:**  
–  

**blunder:**  
–  

**notes:**  
–  

---

## hold
A CHARACTER delays an ACTION until a CONDITION occurs.
> “my CHARACTER HOLDS a FULL ATTACK on the DRAGON’s MOUTH until it opens again.”  

**cost:** FULL / PARTIAL  

**valid targets:**  
inherits from the held ACTION

**result roll (challenge rating):**  
–  

**potency roll:**  
–  

**peak:**  
inherits from ACTION  

**blunder:**  
inherits from ACTION  

**notes:**  
> you can HOLD an ACTION up until you take any kind of DAMAGE  
> you can cancel a HOLD at any time  
---
