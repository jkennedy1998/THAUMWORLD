# tiles-n-occupied
> the world as a grid of voxels

TILES represent a voxel of the world for the sake of
calculating movement, area, and distances
within TIMED EVENTS.

TILES are about 2.5 feet wide.

REGION TILE is a narrative encounter space like a cul-de-sac, a battle map, or a large room in a dungeon.
> it sits between TILE and WORLD TILE scale

A CHARACTER is always on atleast 1 TILE in some sense.
> even if they don't occupy it

A CHARACTER OCCUPIES the amount of tiles dictated by the MAGNITUDE section for SIZE.
> they can choose which tiles they occupy, but the shapes have to be connected.

CHARACTERs cant move to TILEs that are OCCUPUIED
