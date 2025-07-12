

# 🎮 Connect Four with AI (Python + Pygame)

This is a Python implementation of the classic **Connect Four** game using **Pygame** for the graphical interface and the **Minimax algorithm** (with alpha-beta pruning) for the AI opponent.

Challenge yourself against an intelligent computer player and enjoy a smooth, clean, and engaging 2D game interface.

---

## 📁 Project Description

A simple 2D board game where the **goal is to connect four pieces in a row** before the AI does. The game offers:

- 2-player style gameplay: **You vs AI**
- Turn-based control
- Smart AI with offensive and defensive strategy
- Restart or exit after each match
- Visual and interactive GUI using Pygame

---

## ▶️ How to Run the Game

1. Make sure Python 3.x is installed.
2. Open a terminal or command prompt.
3. Navigate to the project folder containing `connect_four.py`.
4. Run the game with the following command:

```bash
**## python connect_four.py**
**##🧰 Requirements**
-You need to install the following Python libraries:

- pip install pygame numpy
**Required Libraries**
pygame — for rendering the game board and handling events

numpy — for efficient matrix (board) representation

math, random, sys — standard Python modules (no need to install separately)

🎮 How to Play
In the Main Menu:
Press 1 → Play first (Red)

Press 2 → Let AI play first (Yellow)

Press Q → Quit the game

In the Game:
Move your mouse to hover over columns

Click to drop a chip in the selected column

First to connect four chips in a row wins

Game checks for horizontal, vertical, and diagonal wins

At Game Over:
Message will display winner (Player or AI)

Press Y → Restart the game

Press N → Exit the game

🧠 AI Algorithm
The AI uses the Minimax algorithm with Alpha-Beta Pruning to make strategic decisions.

Heuristic Evaluation Function Includes:
✅ Scoring based on number of connected pieces (2, 3, or 4 in a row)

✅ Extra weight for controlling the center column

✅ Blocking potential winning moves by the player

The AI is designed to be fast and competitive, adapting its moves based on both offense and defense.
