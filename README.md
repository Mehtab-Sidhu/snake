# Classic Snake game
This project is a classic Snake game coded in Python using the Pygame library. 

### Initialization:

- Libraries: Imports pygame, time, and random for graphics, timing, and random number generation.
- Game Window: Sets the window size and caption ("GeeksforGeeks Snakes").
- Colors: Defines basic colors (black, white, red, green, blue) for the game elements.
- Snake: Initializes the snake's starting position and body (4 blocks).
- Fruit: Generates a random position for the fruit the snake eats.
- Direction: Tracks the snake's current direction (default: right).
- Score: Initializes the score to 0.

### Functions:

- show_score(choice, color, font, size): Displays the current score on the screen.
- game_over(): Ends the game, displays the final score, and quits the program.

### Main Loop:

- Handles key events (up, down, left, right) to change the snake's direction.
- Ensures the snake doesn't move in two directions simultaneously.
- Updates the snake's position based on the current direction.
- Manages the snake's body growth: adds a new block when the snake eats the fruit, removes the tail block otherwise.
- Generates a new fruit position if the snake eats the previous one.
- Fills the game window with black background.
- Draws the snake body (green rectangles) and the fruit (white rectangle).
- Checks for game over conditions: hitting the wall or its own body.
- Continuously displays the score.
- Updates the game display.
- Sets the frame rate (controls game speed).
