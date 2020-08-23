## Introduction

This is an attempt to explain the rules in a simpler way than in version 4.6.

## GAME-PLAY

### Overview

White begins the game.
On her turn, each player performs one or two actions.  The first action is mandatory, while the second action, when available, is optional. The second action is constrained by the first one, and can be unavailable.

Each action implies the manipulation of either a cube or a stack. A stack is made of two cubes.

Each action must be one of the following:

1. Parachute a cube from the reserve;
2. Move a stack by one or two cells;
3. Move a cube by one cell, as one of the following operations:
    31. Translate a cube from ground to ground;
    32. Unstack a cube;
    33. Stack a cube;
    34. Transfer a cube from top to top (the top of an existing stack becomes the top of a new stack).

The constraints on the second action are described in the next table, with reference to above action number.

| First mandatory action                              | Second optional action                      |
| --------------------------------------------------- | ------------------------------------------- |
| Parachute a cube from the reserve (1)               | Parachute another cube from the reserve (1) |
| Move a stack (2)                                    | Move the top of the moved stack (32 or 34)  |
| Move a cube that builds a new stack (33 or 34)      | Move the new stack (2)                      |
| Move a cube without building a new stack (31 or 32) | No available action                         |

A move is possibly accompanied by the capture of an opposing unit (cube or stack) located on the arrival cell of the played unit (cube or stack).
The diagrams on page 5 visually summarize the text below explaining the actions.

