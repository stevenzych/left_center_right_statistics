# Left Center Right Statistics
***Repo in early progress.***

## Game Overview

The game [Left Center Right](https://www.amazon.com/LCR%C2%AE-Left-Center-RightTM-Dice/dp/B003I64OT6) is fully a probabilistic one. Players are given three coins to start. They then take turns rolling three dice labeled with the eponymous L (left), C (center), and R (right), as well as faces bearing no letter. The letters rolled determine the direction and amount of coins a player must pass on their turn. A roll of "L, C, None" translates to "Give one coin to the player to the left, put one in the center pot, and do nothing with the third."

The game continues like this until only one player has any coins in their posession. They then get all the coins in the center pot. If you are playing with real money, this is part actually matters. If not, it just signals the game's end.

## Repo Overview

This repo looks at some of the stats of this game. I analyze things like dice-throw probabilities, average rounds-per-game-per-player, and the natural decay of this game (coins slowly enter the central pot throughout, but can never leave, creating a feedback loop that tends toward ending).

*Note: Not all of these sections are yet finished.*