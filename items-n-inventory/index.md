# items-n-inventory
> for picking things up

ITEMS exist as definitions so they can be TARGETs, be EQUIPT within BODY SLOTs, be picked up into an INVENTORY, and scale with MAGNITUDE.

ITEM MAG determines how powerful an ITEM is in a general sense.
> scales damage, potency, crafting output, and effects
> for ballancing items, MAG can be used as a budget and damage can be subtracted for more utility

ITEMS can have TAGs that modify their behavior.
> an armor tag, a tool tag, conductive : x, etc.

You can USE, ATTACK, and CRAFT with ITEMS.

You cannot USE or ATTACK with an ITEM that is not EQUIPPED.

INVENTORY is how your CHARACTER carries things around.
it factors in STRENGTH, and BRAWN. 
> the amount of volume of items is unlimited currrently

CARRY CAPACITY is how much weight a CHARACTER can carry on themselves.
this includes all items EQUIPT on your BODY SLOTs.
ITEMs have a WEIGHT always listed, that contributes to WEIGHT PENALTY through being equipt as ARMOR or by being in your INVENTORY and above your CARRY CAPACITY

---

## creating new items and ballancing rules
> this section will probably move later into a ballancing page.

When creating new ITEMS, consider the following:
use MAG of an ITEM to generalize a boduget for how many TAGs or MAGs you can add to an ITEM

## workflow of making new items

1: determine mag of item
2: give it tags
3: populate the tag rules on the item with account to the mag cost of the tags

see examples below for clearer rules, 
and default MAGs below those to understand the bounds of a MAG 1 ITEM

## example 1 :  a sword
MAG 3 item
it gains the sword tag, which costs 1 MAG point for future calculations but has specific rules for the item.
for its damage roll it uses MAG 2 (3 - 1 for sword tag) to determine damage.now its a 1d4
done!

## example 2 : some armor with a bonus
MAG 3 item
it gains the armor tag, which costs 1 MAG points for future calculations but has specific rules for the item.
it gains the pressure sense amplifier tag, which costs 1 MAG point for future calculations but has specific rules for the item.
for its damage reduction roll from the armor tag, it uses MAG 2 (3 - 1 for armor tag) to determine damage reduction.now its a 1d4
the pressure sense amplifier tag scales with tag amount, so the item mag has no impact in its ruling 
done!

## example 3 : a conductive wand
MAG 3 item
it gains the conductive tag, which costs 1 MAG points for future calculations but has specific rules for the item.
it gains the wand tag, which costs 1 MAG points for future calculations but has specific rules for the item.
the wand tag changes the target of the spellcast, and scales the implied result roll, it uses MAG 1 (3 -1 for conductive -1 for wand)
the conductive tag scales with the tag amount, so the item mag has no impact in its ruling

## example 4 : a rare and valuble alchemic meat from a MAG 5 beast
MAG 5 item
it gains the carne tag, which costs 1 MAG points for future calculations but has specific rules for the item. 
it gains 2 alchemy tags of any type, which cost 2 MAG points for future calculations but have specific rules for the item.
it gains 3 mag points into value, which costs the remaining 3 mag points but increases the item's worth.
no tags scale with the item mag, so all tags function with their own tag amount.
done!

## example 5 : a healing potion
MAG 4 item
it gains the potion tag, which costs 1 MAG points for future calculations but has specific rules for the item.
it gains 3 alchemy tags of any type, which cost 2 MAG points for future calculations but have specific rules for the item.
potion doesnt scale past 1 and only sets rules for the item. lets you drink it tho.
the alchemy tags scale with tag amount, so the item mag has no impact in its ruling 

## example 6 : mundane items
MAG 1 item
it cant afford a tag, so its just something you can pick up with no other modifiers. 
it uses MAG 1 for any implied rolls.
maybe its a pile of worthless dirt, maybe its a rock you can throw, maybe its a stick you can use to poke things.
done!

## example 7 : a lot of mundane items
MAG 3 item
it uses 2 MAG to account for the size something takes up, via the MAG chart, relative to the max free range of an item.
it uses 1 MAG for any implied rolls, but more importantly tracks immense volume and is a little easier to track for sale, crafting, or trade

## MAG 1 item bounds

ROLL : MAG 0 or 1 ( flat 1 or 1d2 )
> what people have to roll when using this item for POTENCY

DAMAGE : correlates with ROLL
> this is narrative mostly for effects, damage, and senses

HARDNESS : MAG 0 or 1 ( paper, cloth, snow, fruit, meat )
> very soft or hard things cost MAG

CONDUCTIVITY : MAG 0
> all conductive or non conductive materials cost MAG 
WEIGHT : -1 to 1 ( a feather to a medium too or light armor )

SIZE : -1 to 1 ( a grape to a chestplate )
> very very small or large things cost MAG

TEMPARATURE : default is the TEMPARATURE of the current WORLD TILE
> you could ballance hot food in cold places this way

DISTACE : the range of -1 to 1 ( a few inches to the adjacent TILE )
> things that reach farther than this cost MAG

SPEED : with a relative speed measured from MAG 0 to MAG 1 (+1 per round or +1 per action )
> things that add speed in meaningful ways or shoot projectiles cost MAG

TIME : with a time of 0
> timers and things that happen really quickly cost MAG
