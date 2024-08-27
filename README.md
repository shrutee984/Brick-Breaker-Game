# Brick Breaker Game

## Features:
 Brick Map Generation: The game dynamically generates a brick layout at the start of the game using a MapGenerator class.
Scoring System: Players earn 5 points for each brick they break, with the score displayed at the top.
Player Control: Move the paddle left or right using arrow keys to prevent the ball from falling.
Game Over and Win Conditions: If the ball falls past the paddle, the game ends with a "Game Over" message. If all the bricks are broken, the player wins.


## How to Play:
-Use the Right Arrow (→) and Left Arrow (←) keys to move the paddle.
-Break all the bricks by bouncing the ball off the paddle and towards the bricks.
-If you win or the game is over, press Enter to restart the game.


## Code Overview:
-GamePlay.java: Handles the game mechanics including ball movement, paddle control, brick collision detection, and rendering the game's graphics.
-Main.java: Sets up the JFrame window and starts the game.
-MapGenerator.java: Generates the bricks on the screen, stores their positions, and updates them when a brick is hit.

  ### Screenshot
