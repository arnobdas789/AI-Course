Connect Four with AI (Python + Pygame)
This is a Python implementation of the classic Connect Four game using Pygame for graphics and the Minimax algorithm (with alpha-beta pruning) for the AI opponent.

Features
Fun 2-player-style game: You vs AI
Clean interface built with Pygame
Smart AI using Minimax with heuristic scoring
Game-over detection (Win or Draw)
Choose who goes first (Player or AI)
Option to play again after each match
Requirements
Python 3.x
pygame
numpy
Install dependencies:

pip install pygame numpy

How to Play
Run the game:
python connect_four.py

On the menu:

Press 1 to go first (Red)
Press 2 to go second (Yellow)
Press Q to quit
Click on a column to drop your chip.

First to connect 4 in a row (vertically, horizontally, or diagonally) wins!

At the end, press Y to play again or N to quit.

AI Logic
The AI uses the Minimax algorithm with alpha-beta pruning for faster decisions and a scoring system based on:

Connected pieces
Center dominance
Blocking player wins

