# glyphs-n-calls
> are to words, as spells are to sentences

GLYPHS are to SPELLS as words are to sentences.

A GLYPH’S power is represented by its MAG.
GLYPH MAG can rise and fall over time.

SPELLS have a CALL COST.
The CALL COST of a SPELL is the sum of the CALL COSTS of all GLYPHS used.

CHARACTERS gain GLYPHS through creation and growth.
GLYPHS are learned from research, teachers, or experimentation.

GLYPHS connect to the nearest valid input.
They are read sequentially from start to end.

> spells read like sentences, left to right

---

## glyph types

### activator
INPUT: TARGET  
OUTPUT: ACTION  

COST: 1 THAUM × GLYPH MAG  

> the base of a SPELL, performs an ACTION and has a POTENCY ROLL

---

### targeter
INPUT: none  
OUTPUT: TARGET  

COST: 1 THAUM × GLYPH MAG  

> defines RESULT ROLLS and vectors for ACTIVATORS

---

### re-targeter
INPUT: TARGET  
OUTPUT: TARGET  

COST: 1 THAUM × GLYPH MAG  

> alters the vector of a TARGETER, resolves before it

---

### sensor
INPUT: TARGET  
OUTPUT: LOGIC  

COST: usually 0  

> produces a CONDITION that is true or false

---

### logic-er
INPUT: LOGIC  
OUTPUT: LOGIC  

COST: usually 0  

> refines LOGIC using gates like AND, OR, NOT

---

### magmaticor
INPUT: GLYPH  
OUTPUT: GLYPH  

COST: varies  

> changes the MAG of other GLYPHS

---

### gate
INPUT: ACTION or LOGIC  
OUTPUT: ACTION  

COST: usually 0  

> holds an ACTIVATOR until a CONDITION is met