# Snake-Ladder


This is a text-based implementation of the classic "Snake and Ladder" game written in C++. The game simulates the traditional board game where players roll dice and move their markers across the board, encountering ladders that allow them to climb higher and snakes that bring them down.

## Features

- **Two-Player Gameplay**: The game supports two players taking turns to roll the dice and move their markers.
- **Ladders and Snakes**: The board contains ladders that players can climb to advance and snakes that players must descend.
- **Automatic Marker Movement**: After each roll of the dice, the markers for both players are automatically moved to the correct position on the board based on the outcome of the dice roll.
- **Winning Condition**: The first player to reach or exceed square 100 wins the game.

## How to Play

1. Compile the code using a C++ compiler (e.g., Turbo C++).
2. Run the compiled executable.
3. The game will display the board and players' markers.
4. Roll the dice by pressing any key.
5. Players' markers will move based on the dice roll and any ladders or snakes encountered.
6. Continue taking turns until one player reaches or exceeds square 100.

## Rules and Notes

- The game starts with Player 1.
- If a player rolls a 6, they get an additional turn.
- The position of the markers is automatically updated based on the dice roll.
- Ladders allow players to climb higher on the board.
- Snakes cause players to move down on the board.
- The game displays the current player's marker in different colors (blue and red).
- The game ends when a player reaches or exceeds square 100. The winning player is announced.
- The game can be played on a console window.

## Code Overview

The code is structured using various classes and functions to manage the game's logic, player movements, and board layout. Some key classes include:

- `dice`: Represents the dice used in the game and can roll a random number between 1 and 6.
- `player1` and `player2`: Represent the two players and manage their positions on the board.
- `setplayer()`: A function to alternate between Player 1 and Player 2's turns.
- `graph()`: Draws the graphical representation of the board, ladders, and snakes.
- `sohaib()`: The main game loop that controls the flow of the game.

## Note

This code uses graphics from the `graphics.h` library for visual representation. Please ensure that your compiler and environment support this library for the graphics to work properly.

