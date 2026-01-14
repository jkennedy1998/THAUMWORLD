# tiles-n-occupied
> the world as a grid of voxels

TILES represent a voxel of the world for the sake of
calculating movement, area, and distances
within TIMED EVENTS.

TILES are about 2.5 feet wide.

A CHARACTER is always on a TILE in some sense.
###### even if they don't have [ OCCUPY ]

A CHARACTER has the [ OCCUPY ] TAG if they take up physical space.
TILEs with CHARACTERs or ITEMs that have the OCCUPY TAG, gain the tag.

CHARACTERs who have [ OCCUPY ] cannot move to tiles with [ OCCUPY ]

###### OCCUPIED TAGs representhas something on it that occupies it : a person, a wall, a furniture item

###### mostly ghosts, liquid or gas forms, and creatures XS and smaller do not occupy