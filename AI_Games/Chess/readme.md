# ♟️ Chess - Player vs Computer (Minimax AI)

A visually rich and strategic chess game built with Python and Pygame. Challenge yourself against a computer opponent driven by a depth-limited Minimax algorithm with Alpha-Beta Pruning.

---

## 🧰 Requirements

Install the required libraries before running the game:


**pip install pygame chess**

## Included Standard Libraries:
- math — evaluation calculations
- sys — for exiting the program
- pygame — UI rendering and event handling
- chess — board logic and rule enforcement

## 🚀 Features
- 🖼️ Intuitive 8x8 chessboard with Unicode-based pieces
- 🤖 AI opponent using Minimax with Alpha-Beta Pruning
- 🧠 Basic heuristic evaluation for scoring positions
- ✨ Pawn promotion support
- 🔄 Result display with restart mechanism

## ▶️ How to Run
- Clone the repository or download the .py file
- Open terminal or command prompt
- Navigate to the project directory
- Run the script:
**python chess_ai.py**



## 🎮 How to Play
Controls
- Click a piece to select it
- Legal move hints appear on the board
- Click again to move to a highlighted square
- Play as White, AI plays as Black
AI Thinking
- The AI uses a depth-2 Minimax search with alpha-beta pruning
- Evaluates positions based on material count and simple tactics
Game Endings
- Checkmate
- Stalemate
- Insufficient material
- 75-move rule
- Fivefold repetition

## 🧠 AI Strategy
The computer evaluates moves using:
- Piece value heuristics:
- Pawn: 1
- Knight/Bishop: 3
- Rook: 5
- Queen: 9
- King: ∞ (non-evaluated)
- Material balance scoring
- Defensive and offensive move pruning

Enjoy classic chess with a solid AI challenge and beautiful visuals. Great base for experimenting with deeper search or improved heuristics!
