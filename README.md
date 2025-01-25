# Tic Tac Toe

This project is a Python implementation of the classic Tic Tac Toe game, utilizing the MiniMax algorithm for optimal decision-making. The program supports both single-player mode (against the computer) and two-player mode. It also includes an optimized version of the MiniMax algorithm with alpha-beta pruning.

## Features
- **Single-player Mode**: Play against a computer that uses the MiniMax algorithm to determine its moves.
- **Two-player Mode**: Play with a friend on the same system.
- **Dynamic Board Rendering**: Displays the current state of the board after each move.
- **Optimal Moves**: The computer always makes the best possible move using the MiniMax algorithm.

## Complexity
- **Original MiniMax**: O(b^d), where `b` is the branching factor and `d` is the depth of the game tree.
- **Optimized MiniMax with Alpha-Beta Pruning**: O(b^(d/2)), significantly reducing the computational complexity.

## How to Use
1. Clone this repository or download the script.
2. Run the Python script in a terminal or Jupyter Notebook.
3. Follow the prompts to choose single-player or two-player mode:
   - For single-player mode, select whether to play first or second.
   - For two-player mode, players take turns entering their moves.

## Game Rules
- The board is represented as a 3x3 grid:
  ```
  1 | 2 | 3
  ---------
  4 | 5 | 6
  ---------
  7 | 8 | 9
  ```
- Player `X` and Player `O` alternate turns.
- To make a move, enter the position (1-9) where you want to place your mark.
- The game ends when one player achieves three marks in a row (horizontally, vertically, or diagonally) or when the board is full (draw).

## File Contents
- **`ConstBoard(board)`**: Displays the current state of the board.
- **`User1Turn(board)`** and **`User2Turn(board)`**: Handle player inputs and update the board.
- **`minimax(board, player)`**: Implements the MiniMax algorithm.
- **`CompTurn(board)`**: Determines the computer's move using MiniMax.
- **`analyzeboard(board)`**: Evaluates the current board state to check for a winner.
- **`main()`**: Main function that initializes the game and handles the game loop.

## Example Gameplay
```text
Enter 1 for single player, 2 for multiplayer: 1
Computer : O Vs. You : X
Enter to play 1(st) or 2(nd): 1
Current State Of Board:

-  -  -
-  -  -
-  -  -

Enter X's position from [1...9]: 5
```

## Requirements
- Python 3.x

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.

