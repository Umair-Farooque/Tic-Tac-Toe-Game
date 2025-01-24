# Tic-Tac-Toe with Mini-Max Algorithm
This repository contains two implementations of a Tic-Tac-Toe game where one uses the basic Mini-Max algorithm and the other improves upon it by optimizing the time complexity with Alpha-Beta pruning.

Features
Single-player mode (Player vs Computer).
Multiplayer mode (Player vs Player).
AI powered by the Mini-Max algorithm for optimal gameplay.
Improved AI with Alpha-Beta pruning for faster computation.
Files
Basic Mini-Max Implementation: The initial implementation of the Mini-Max algorithm to evaluate the game tree for the AI's moves.
Optimized Mini-Max with Alpha-Beta Pruning: An improved version of the Mini-Max algorithm that reduces the number of game states evaluated.
How It Works
Mini-Max Algorithm
The Mini-Max algorithm is a decision-making algorithm used in game theory. It evaluates the possible moves in the game to determine the optimal move for the computer.

Alpha-Beta Pruning
Alpha-Beta pruning is an optimization of the Mini-Max algorithm. It reduces the number of nodes evaluated in the search tree, significantly improving performance without sacrificing accuracy.

Usage
Clone the repository.
Run the file Tic Tac Toe.ipynb in a Jupyter Notebook environment.
Follow the prompts to select the game mode:
Single-player (Computer vs Player).
Multiplayer (Player vs Player).
![image](https://github.com/user-attachments/assets/71246a22-030a-423b-9fc0-95802d9ed1ab)

Example
Player inputs positions as numbers between 1–9.
The game displays the board after each move.
The AI calculates the optimal move using the chosen algorithm.
Contributing
Feel free to open issues or submit pull requests for bug fixes or feature enhancements.
