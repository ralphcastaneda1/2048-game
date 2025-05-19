# 2048-game
Java implementation of the 2048 game logic 


2048 game

**A Java implementation of the 2048 game logic and GUI**  

## Overview

You’ll implement the core 2048 mechanics in `game2048logic/Model.java`, and the provided rendering layer in `game2048rendering/` will handle display, input, and new‐tile generation.

### Tasks in `Model.java` (game2048logic)
1. **`emptySpaceExists()`** – detect any empty cell.  
2. **`maxTileExists(int target)`** – check for a tile ≥ `target`.  
3. **`atLeastOneMoveExists()`** – determine if any tilt would change the board.  
4. **Tilting logic** (`tilt`, `merge`, etc.) – slide and merge tiles per the game rules.  
5. **Score updates** – add merged tile values to the running score.


