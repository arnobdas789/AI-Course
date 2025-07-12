

# 🎮 Connect Four with AI (Python + Pygame)

## 🧰 Requirements
Install required libraries:

**pip install pygame numpy**

Included Libraries
- pygame — for rendering the game board and handling mouse events
- numpy — for representing and manipulating the game board
- math, random, sys — standard libraries used for calculations and control flow

🎮 How to Play
Main Menu
- Press 1 → Play first as Red
- Press 2 → Let AI play first as Yellow
- Press Q → Quit the game
In Game
- Hover your mouse over a column to highlight it
- Click to drop your chip in the selected column
- First to connect four chips in a row wins!
Win types:
- Horizontal
- Vertical
- Diagonal
Game Over Screen
- Displays Winner (Player or AI)
- Press Y → Restart the game
- Press N → Exit

🧠 AI Strategy
The AI opponent uses the Minimax algorithm with Alpha-Beta Pruning for fast and strategic decision-making.
Heuristic Evaluation Includes:
- Scoring patterns based on 2, 3, or 4 connected pieces
- Extra points for center column control
- Defensive logic to block the player’s potential win
The result is a competitive AI that balances offense and defense, adapting its strategy based on the board state.

🚀 Features
- Real-time UI with intuitive gameplay
- Restart and quit functionality
- Challenging AI that evolves with each move
- Efficient board computation using NumP
