# tag-table
> the expanding scroll of tags and their properties

## TAG TABLE preface

below is a list of TAGs that are present in THAUMWORLD.
they are not the only ones that exist, but they are the default out of the box TAGs.

see the TAG page for more information on what a TAG is

If an existing TAG does not quite fit a situation,
new TAGS can be created using similar structure to existing TAGS.

> you can use the [ BALLANCE : X ] tag to shift the ballance of powerful tags up by 1. 
> this changes how tags can be ballanced during crafting, creation of new items, or weighed in ballancing systems.

---

## TAG EXAMPLE FORMATTING

[ TAGNAME : information to be tracked ]
> PROFICIENCY : here, here if there are two, ...
> [ META TAG if any ], [ META TAG 2 if any ], ...
> description of TAG in a general sense

> > CHARACTER : description here

> > ITEM : description here

> > TILE : description here

--- 

## THE TAG TABLES





### META TAGs 
> META TAGs go onto other TAGs and give them default properties. 
> these are often called to within PERKS and SPELLS

---
--- 
--- 

### [ DISPERSING ]
> PROFICIENCY : decided by TAG this is on
the TAG this is put on naturally disperses at the end of a TURN
fast paced effects that go away within a TIMED EVENT or 1 EXTENDED ACTION

CHARACTER :
> -1 ( TAG ) at end of TURN

ITEM :
> -1 ( TAG ) at end of TURN

TILE :
> -1 ( TAG ) at end of TURN

---

### [ DISEASE : CR of the DISEASE ]
> PROFICIENCY : PAIN unless overridden
the TAG this is put is a DISEASE that effects biological creatures.
the TAG this is on will state what the specific disease does, 
and its CR for curing a TAG

CHARACTER : 
> -1 ( TAG ) on passed RESULT ROLL : ( DISEASE CR ) during SLEEP

ITEM : 
> decided by TAG this is on

TILE : 
> decided by TAG this is on

--- 

### [ DAMAGE ]
> PROFICIENCY : PAIN unless overridden
this marks a DAMAGE TAG AND proc-s a lot of stuff through the ITEM that does the DAMAGE

CHARACTER : -

ITEM : 
> the item procs rules about this DAMAGE TAG when it is used to do DAMAGE
> like characters with weaknesses to it 

TILE : -

--- 

### [ TOOL ]
> PROFICIENCY : decided by TAG this is on
if something can be EQUIPT on a HAND SLOT as a TOOL

CHARACTER : 
> this could happen if a larger creature grabs you like an item, and uses you to preform an action.
> you take equal damage as the potency you helped. 
> attack damage that your body does to something also applies to you, effecting your health instead giving you stacks of break

ITEM : 
> the ITEM can be EQUIPT in a HAND and used like a TOOL for ACTIONS to be specified on the TAG this is on
> this ITEM gains the default TARGETER GLYPH set by the TAG this is on.

TILE : -

--- 
--- 
--- 

### normal TAGs
>these are TAGs you would find in the world on CHARACTERs, ITEMs, or TILEs.
>you may see these referenced in other TAGs, but never put onto TAGs themselves.

---

### [ OVERENCUMBERED ]
> PROFICIENCY : BRAWN
> this is set from overloaded carry capacity

CHARACTER : 
> movement speed and evasion is decreased by 1 for every TAG MAG

ITEM : 
> -

TILE : 
> -

---

### [ KNOCKED ]
> PROFICIENCY : BRAWN
[ DISPERSING ]
> this is usually set from your HEALTH dropping below 1 per the HEALTH rules page

CHARACTER : 
> all movement is limited to 1, and you are limited to 1 USE PARTIAL ACTION per turn when you have this TAG
> this TAG decreases by 1 TAG MAG for every point of HEALTH you recover / heal
> note this also disperses by 1 at the end of your TURN

ITEM : 
> -

TILE : 
> -

---

### [ SLEEPING ]
> PROFICIENCY : PAIN
> this is usually set when you use the EXTENDED ACTION : SLEEP

CHARACTER : 
> cannot move or do any actions. -1 TAG MAG per for each DAMAGE taken or when SLEEP is completed.

ITEM : 
> -

TILE : 
> -

---

### [ AWARENESS : TARGET who you are aware of ]
> PROFICIENCY : INSTINCT
> this is assumed and not tracked unless people are trying to use it. 
> it is usually set by the AWARENESS rules page

CHARACTER : 
> represents when a character knows the target’s location.
> for proc-ing stealth stuff, and the prerequisite to being able to TARGET something

ITEM : 
> -

TILE : 
> -

---
### [ GRAPPLED : TARGET who grappled you, CR equal to the TAG giver's LATEST GRAPPLE RESULT ROLL aginst you]
> PROFICIENCY : BRAWN
> this means you are being grappled by someone.

CHARACTER : 
> when TARGET size = yours, movement is limited to 0
> when TARGET size > yours, they control movement, limited to the size delta
> when TARGET size < yours, you control movement, limited to the size delta
> 
> -1 TAG on passed GRAPPLE RESULT ROLL : ( CR of latest grapple )
> all TAG MAGs are cleared from this effect if the TARGET does pass a GRAPPLE at least 1 time in per TURN

ITEM : 
> -

TILE : 
> -

---

### [ FLINCH ]
> PROFICIENCY : PAIN
> this is set from multiple sources, usually from surprises or intense senses

CHARACTER : 
> every start of your turn or immidiatly if it is yor turn when you get this,
> trade -1 ACTION for every 2 TAG MAG, and trade -1 PARTIAL ACTION for every remaining 1 TAG MAG
> at higher MAGs this may take multiple TURNs to trade away

ITEM : 
> -

TILE : 
> -

---

### [ BROKEN ]
> PROFICIENCY : MECHANICS
> this is set from multiple sources, usually from surprises or intense senses

CHARACTER : 
> you cannot EQUIPT this item by normal means if the TAG MAG of BROKEN is greater or equal to the ITEM MAG
> on a passed CRAFT RESULT ROLL : (CR 10) any CHARACTER can remove 1 TAGMAG from any TARGET

ITEM : 
> you cannot EQUIPT this item by normal means if the TAG MAG of BROKEN is greater or equal to the ITEM MAG
> decreases functional MAG by 1 per TAG MAG of BROKEN -- including for DAMAGE, any custom TAGs, DAMAGE negation, or for reapairing the ITEM
> on a passed CRAFT RESULT ROLL : (CR 10 + ITEM MAG) any CHARACTER can remove 1 TAGMAG of BROKEN from any ITEM

TILE : 
> walking or climbing on this tile crumble it, and the tile can be destroyed with DAMAGE MAG 1 and above
> on a passed CRAFT RESULT ROLL : (CR 10) any CHARACTER can remove 1 TAG MAG from any TARGET

---

### [ FIRE! ]
> PROFICIENCY : HEARTH
[ DISPERSING ]
> this is when things are on FIRE!, and this is usually conditional or caused

CHARACTER : 
> -1 ( TAG ) on passed HEARTH RESULT ROLL : (10+TAGMAG)
> at the end of a CHARACTER’s TURN, they get -(TAGMAG) HEALTH DAMAGE
> does not disperse naturally if the TAG holder also has [ FLAMMABLE ]
> spreads to CHARACTERs, ITEMs, and TILEs with [ FLAMMABLE ] within one adjacent TILE per TURN

ITEM : 
> at the end of a ROUND, the TAG holding ITEM get +(TAGMAG) stacks of [ BROKEN ]
> the TILE this occupies calculates as if its [ FIRE! ] tag is equal to this ITEM -- if it has a lower amount of [ FIRE! ] TAGs

TILE : 
> at the end of a ROUND, the TAG holding TILE get +(TAGMAG) stacks of [ BROKEN ]
> the TEMPARATURE MAG counts as +1 per MAG TAG for this tile, relative to the WORLD TILE its in.
> does not disperse naturally if the TAG holder also has [ FLAMMABLE ]
> spreads to CHARACTERs, ITEMs, and TILEs with [ FLAMMABLE ] within one adjacent TILE per TURN

---


### [ FLAMMABLE ]
> PROFICIENCY : HEARTH
> this is when things can catch on FIRE! automatically

CHARACTER : 
> when there is an adjacent or touching [ FIRE! ], convert all TAG MAG of this TAG, to [ FIRE! ]

ITEM : 
> when there is an adjacent or touching [ FIRE! ], convert all TAG MAG of this TAG, to [ FIRE! ]

TILE : 
> when there is an adjacent or touching [ FIRE! ], convert all TAG MAG of this TAG, to [ FIRE! ]

---

### [ FROST! ]
> PROFICIENCY : HEARTH
[ DISPERSING ]
> this is when things are suuuuuper cold, and this is usually conditional

CHARACTER : 
> -1 ( TAG ) on passed HEARTH RESULT ROLL : (10+TAGMAG)
> at the end of a CHARACTER’s TURN, they get -(TAGMAG) HEALTH DAMAGE

ITEM : 
> for the ITEM's TILE's TEMPARATURE MAG counts as -1 per MAG TAG for this tile, relative to the WORLD TILE its in.
> can be contained to avoid this effect.

TILE : 
> the TEMPARATURE MAG counts as -1 per MAG TAG for this tile, relative to the WORLD TILE its in.

---

### [ HYPOTHERMIA ]
> PROFICIENCY : PAIN
> this is set by things that are colder than comfortable

CHARACTER : 
> - 1 HEALTH per TAG MAG every EXTENDED ACTION spent in uncomfortable temperatures
> -1 TAG for every EXTENDED ACTION spent in comfortable temperatures

ITEM : 
> this ITEM becomes frozen at 2 TAGMAG.
> only ITEMs with TEMPARATURE RANGES can get this.

TILE : 
> this TILE becomes frozen at 2 TAGMAG. 
> only TILEs with TEMPARATURE RANGES can get this.

---

### [ HEATSTROKE ]
> PROFICIENCY : PAIN
> this is set by things that are hotter than comfortable

CHARACTER : 
> - 1 HEALTH per TAG MAG every EXTENDED ACTION spent in uncomfortable temperatures
> -1 TAG for every EXTENDED ACTION spent in comfortable temperatures

ITEM : 
> this ITEM becomes burnt at 2 TAGMAG.
> only ITEMs with TEMPARATURE RANGES can get this.

TILE : 
> this TILE becomes burnt at 2 TAGMAG. 
> only TILEs with TEMPARATURE RANGES can get this.

---