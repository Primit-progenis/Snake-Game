# Snake Game

A small Snake game written in Python with Pygame. The game draws a 20-by-20 grid in a 500-by-500 window.

## How it works

- The snake is a sequence of grid cubes. The arrow keys change its direction, and each body segment follows the turn made by the segment ahead of it.
- A green snack appears at a random unoccupied grid position. Eating it adds a segment and places another snack.
- The game prints the current body length as the score when the snake hits a wall or itself, then resets the snake.

The game loop updates movement, checks collisions and snack pickup, and redraws the grid, snake, and snack.

## Requirements and run

Requires Python 3 and Pygame. Install Pygame if needed, then run:

```sh
python -m pip install pygame
python snake.py
```

Use the **arrow keys** to steer. Close the game window to exit.
