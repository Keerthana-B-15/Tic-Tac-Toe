# Tic Tac Toe Game in Python

This is a simple command-line implementation of the classic Tic Tac Toe game in Python.

## Overview

This program allows two players to take turns marking spaces on a 3x3 grid. The objective is to get three of their marks in a row (horizontally, vertically, or diagonally) before the opponent does.

## Getting Started

### Prerequisites

Make sure you have Python installed on your machine. You can download it from [here](https://www.python.org/downloads/).

### Running the Game

1. Clone the repository to your local machine:
2. Navigate to the project directory: 
3. Run the game:
4. Follow the on-screen instructions to play the game.

## Game Rules

- The game is played on a 3x3 grid.
- Players take turns marking spaces with their respective symbols ('X' for Player 1 and 'O' for Player 2).
- The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game.
- If all spaces on the grid are filled and no player has won, the game ends in a draw.

## Implementation Details

The game logic is implemented in Python, with functions for summing the marks, printing the game board, and checking for a win condition.

- `sum(a, b, c)`: Function to calculate the sum of three numbers.
- `printboard(xstate, zstate)`: Function to print the current state of the game board.
- `checkWin(xstate, zstate)`: Function to check if a player has won the game.
- The game loop continues until a player wins or the game ends in a draw.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/improvement (`git checkout -b feature/improvement`).
3. Make your changes and ensure the code is properly formatted.
4. Test your changes thoroughly.
5. Commit your changes (`git commit -am 'Add some feature'`).
6. Push to the branch (`git push origin feature/improvement`).
7. Create a new Pull Request.
