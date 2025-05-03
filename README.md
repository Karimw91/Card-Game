# Card-Game
text-based card game in C++ focusing on game logic, rules enforcement, and data structure manipulation.text-based card game in C++ focusing on game logic, rules enforcement, and data structure manipulation.

Game Rules:
The game is played on a 4x4 grid with 16 face-down cards.
Each card hides a number from 1 to 8, with every number appearing exactly twice.
Players take turns flipping two cards per turn.

1- If the two cards match:
  
  The player earns points.

  The cards stay face-up.

  The player gets another turn.

2 - If the two cards do not match:

  The cards are flipped back face-down.

  The turn passes to the other player.

3 - Special rules:

  Matching two 7s grants bonus points.

  Matching two 8s results in a penalty (loss of points).

The game continues until all cards are face-up.
The player with the highest total score at the end wins.
