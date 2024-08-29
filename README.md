# Flappy Bird

A simple Flappy Bird game implemented using Pygame.

## Description

This project is a clone of the popular Flappy Bird game. The player controls a bird, attempting to fly between columns of green pipes without hitting them.

## Features

- Animated bird with gravity and jumping mechanics
- Moving pipes with gaps for the bird to fly through
- Score tracking
- Restart button to reset the game

## Installation

1. Ensure you have Python installed. You can download it from python.org.
2. Install Pygame using pip:
    ```bash
    pip install pygame
    ```

## How to Play

1. Run the game script:
    ```bash
    python flappy_bird.py
    ```
2. Click the mouse to make the bird jump.
3. Avoid the pipes and try to get the highest score possible.
4. Click the restart button to play again after a game over.

## Code Overview

### Main Game Loop

The main game loop handles the game state, including starting, running, and ending the game. It also updates the display and checks for events like mouse clicks.

### Bird Class

The `Bird` class represents the player-controlled bird. It handles the bird's animation, movement, and collision detection.

### Pipe Class

The `Pipe` class represents the pipes that the bird must avoid. It handles the movement and positioning of the pipes.

### Button Class

The `Button` class represents the restart button. It handles drawing the button and detecting mouse clicks.

### Functions

- `draw_text(text, font, text_col, x, y)`: Draws text on the screen.
- `reset_game()`: Resets the game state for a new game.

## Assets

- Background image: `flappy_bird/img/bg.png`
- Ground image: `flappy_bird/img/ground.png`
- Bird images: `flappy_bird/img/bird1.png`, `flappy_bird/img/bird2.png`, `flappy_bird/img/bird3.png`
- Pipe image: `flappy_bird/img/pipe.png`
- Restart button image: `flappy_bird/img/restart.png`

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- Inspired by the original Flappy Bird game by Dong Nguyen.
- Pygame library for game development.
