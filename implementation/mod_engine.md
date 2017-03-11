# Mod Engine

## Queue System

API should have the ability to define a queue for a ship. 

E.g. Move to this solar system, mine this resource, start fabricating shells, etc.

Send queue ONCE to the backend and it deals with executing it.

## Priority

What if an enemy is in proximity? The queue should be suspended and a higher
priority action to be run.

## Ideas

- We can use the mod system to build a rim-world like priority queue.
