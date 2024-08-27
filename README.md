# Brick Breaker Game

A simple Brick Breaker game built in Java using `Swing` and `JFrame`. The objective is to break all the bricks using a bouncing ball while controlling a paddle.

## Features

- **Brick Map Generation**: Dynamically generates a brick layout at the start of the game using a `MapGenerator` class.
- **Scoring System**: Earn 5 points for each brick broken. The score is displayed at the top of the game screen.
- **Player Control**: Move the paddle left or right using the arrow keys to prevent the ball from falling.
- **Game Over and Win Conditions**: If the ball falls past the paddle, the game ends with a "Game Over" message. If all the bricks are broken, the player wins.

## How to Play

1. Use the **Right Arrow (→)** and **Left Arrow (←)** keys to move the paddle.
2. Break all the bricks by bouncing the ball off the paddle towards the bricks.
3. If you win or the game is over, press **Enter** to restart the game.

## Code Overview

- **GamePlay.java**: Handles the game mechanics including ball movement, paddle control, brick collision detection, and rendering the game’s graphics.
- **Main.java**: Sets up the `JFrame` window and starts the game.
- **MapGenerator.java**: Generates the bricks on the screen, stores their positions, and updates them when a brick is hit.

## Screenshot

_(Add screenshots here to show how the game looks in action.)_

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/brick-breaker.git
    ```
2. Open the project in your favorite Java IDE (e.g., Eclipse, IntelliJ IDEA).
3. Compile and run the `Main.java` file to start the game.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
