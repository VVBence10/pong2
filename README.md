# Pong Game in Python

This repository contains an implementation of the classic game Pong using the Pygame library in Python.

## Requirements

To run this game, you'll need:

- Python 3.x
- Pygame library

## Getting Started

1. Install Python: Download and install Python from https://www.python.org/.
2. Install Pygame: Open a terminal or command prompt and run `pip install pygame` to install the Pygame library.
3. Clone this Repository: Clone or download this repository to your local machine.

## Game Description

### Game Setup

- The game window dimensions are set to 960x600 pixels.
- The main window displays the title "Pong."
- Colors are set to different shades of grey.
- Two rectangular paddles and a ball are created.

### Game Logic

- The game starts with the ball randomly moving towards either player's side.
- Players can control their paddles using the arrow keys (up and down) for the first player and 'W' and 'S' keys for the second player.
- The objective of each player is to prevent the ball from crossing their side while trying to hit it towards the opponent.
- If the ball crosses the left or right edge of the screen, the corresponding player's opponent scores a point.
- When the ball collides with a paddle, its direction changes based on the position of the collision, simulating a realistic bounce.
- The game features sound effects for ball bounces and scoring.

### Levels and Players

- Players can choose from three different difficulty levels by pressing the keys '1', '2', or '3' on their keyboard.
- The difficulty levels affect the speed of the opponent's paddle and the ball.
- Players can choose to play in either single-player (against an AI opponent) or two-player mode.

### Features

1. **Winning Conditions**: A player can win if they reach a score of 21 points while also having a lead of at least 2 points over their opponent. The game will automatically determine the winner based on these conditions.

2. **Game Over Screen with Restart**: When a player wins or the game ends, the screen transitions to a game over screen. The winning player's name is displayed, and players can press the 'R' key to restart the game.

### Game Flow

- The game starts with the title screen, where players can choose the difficulty level and the number of players.
- Players can control their paddles according to the chosen configuration.
- If a player wins according to the new winning conditions, the game transitions to a game over screen with the winner's name displayed.
- Players can press the 'R' key on the game over screen to restart the game and play again.

## Credits

This Pong game was developed by Bence Varga-Vigh from Hungary.