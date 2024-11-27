
# Tic-Tac-Toe Game in C++

## Overview
A simple console-based Tic-Tac-Toe game for two players (Player 1 uses 'X' and Player 2 uses 'Y'). The game checks for a winner after each turn and announces the winner or a draw if no one wins after 5 rounds.

## Features
- 2-player game
- 3x3 grid for the board
- Automatic winner detection (horizontal, vertical, diagonal)
- Draw detection after 5 turns

## How to Run
1. Save the code as `tictactoe.cpp`.
2. Compile using:
   ```
   g++ tictactoe.cpp -o tictactoe
   ```
3. Run the game:
   ```
   ./tictactoe
   ```

## Functions
- **`checkwin()`**: Checks if there’s a winner after each move.
- **`mark(int player, int box)`**: Marks the player’s move on the board.
- **`display()`**: Displays the current state of the board.

## Example Output
```
Player 1, Enter the Box: 1
0   1   2
3   4   5
6   7   8

Player 2, Enter the Box: 4
X   1   2
3   Y   5
6   7   8

Player 1, Enter the Box: 2
X   1   X
3   Y   5
6   7   8

Player 1 wins!
```

## Improvements
- Add input validation for invalid moves.
- Implement AI for single-player mode.
- Add a replay feature.

