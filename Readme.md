# Tic-Tac-Toe with Minimax Algorithm

## Overview

This repository contains a simple command-line implementation of the classic Tic-Tac-Toe game in Python. The game allows a human player to play against the computer, which uses the Minimax algorithm with alpha-beta pruning to determine the optimal move.

## Features

- **Player vs Computer**: The human player plays as 'X', and the computer plays as 'O'.
- **Minimax Algorithm**: The computer uses the Minimax algorithm with alpha-beta pruning to determine the best possible move.
- **Dynamic Board Display**: The current state of the game board is displayed after each move.
- **Winner Detection**: The game checks for a winner after each move and announces the result.

## How It Works

### Displaying the Board

The game board is displayed in a 3x3 grid format after each move, showing the current state of the game.

### Validating Moves

The game checks if a move is valid (i.e., within the bounds of the board and on an empty cell).

### Getting Player Move

The player is prompted to enter the row and column numbers for their move. Input validation ensures that the player enters valid coordinates.

### Checking for a Winner

After each move, the game checks if there is a winner or if the game has ended in a draw. It returns:
- `1` if the player 'X' wins,
- `-1` if the computer 'O' wins,
- `0` if the game is a draw,
- `None` if the game is still ongoing.

### Minimax Algorithm

The Minimax algorithm is used by the computer to determine the best possible move. It evaluates each possible move recursively to maximize the computer's chances of winning (or minimize the player's chances). Alpha-beta pruning is applied to optimize the search process.

### Finding the Best Move

The computer evaluates all possible moves using the Minimax algorithm and selects the move with the highest score.

### Playing the Game

The game alternates between the player and the computer, displaying the board after each move. The game continues until a winner is found or the game ends in a draw.

## Usage

1. Run the `play_game()` function to start the game.
2. Follow the prompts to enter your move (row and column numbers).
3. The game will display the board after each move and announce the result when the game ends.

![image](https://github.com/idrees200/TicTacToe/assets/113856749/201cd130-ed0b-494b-a61b-fae1a9ea86d7)

