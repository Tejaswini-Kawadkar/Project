# Project
## Whack a mole game

#### HTML Body:

The game interface includes a score label, a chance label, and a grid of holes represented by input elements with type "image."
Each hole has an onclick attribute that calls the myScore function with the corresponding hole's ID when clicked.
At the bottom, there's a "PLAY" button that triggers the start function.

#### Game Flow:

The player clicks the "PLAY" button to start the game.
Moles appear randomly in the holes, and the player must click on them to score points.
The score and remaining chances are displayed.
The game ends when the player runs out of chances, and an alert notifies them of the game over.
