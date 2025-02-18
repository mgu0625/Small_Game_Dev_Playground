# Tic-Tac-Toe (Python & Pygame)
### About this project
This repository contains three different implementations of Tic-Tac-Toe, each showcasing a different approach to coding the game. This project was developed as part of my game development learning journey, using Python and Pygame to explore UI and logic optimization.

All versions were developed and tested using PyCharm 2024.3.3.

This Project Followed the Tutorial by **Shaun Halverson**. [YouTube](https://www.youtube.com/watch?v=M3G1ZgOMFxo)

---------

## Game Versions

### 1. Terminal-Based Tic-Tac-Toe (tic_tac_toe.py)
- Runs in the command line (terminal).
- Implements a basic 3x3 game board using lists.
- Uses player vs. player input (human vs. human).
- No GUI, just text-based input.
- Simple turn-based logic with winner detection.

How to Run:
`python src/tic_tac_toe.py`

### 2. Pygame Easy Mode (tic_tac_toe_pygame.py)
- Graphical version using Pygame.
- Allows mouse-based input instead of typing moves.
- Visual board with X and O graphics.
- Player vs. basic AI (random choice CPU move).

How to Run:
`python src/tic_tac_toe_pygame.py`

### 3. Pygame Optimized Version (tic_tac_toe_optimized.py)
- Fully optimized GUI version of Tic-Tac-Toe.
- Implemented Minimax AI algorithm for CPU moves (suppowed to be difficult to beat).
- More fluid animations and event handling.
- Reset button for replaying without restarting the script.
    - This was a STRUGGLE and got help from [StackOverflow](https://stackoverflow.com/questions/66933155/how-do-you-restart-a-game-on-pygame-by-using-a-button)
- Improved scalability for future enhancements.
- Shows Message at end of game.

How to Run:
`python src/tic_tac_toe_optimized.py`

-----
## Installation Guide

### 1. Clone Repository.
   `git clone https://github.com/yourusername/Game_Dev_Playground.git`
   
   `cd Game_Dev_Playground/TicTacToe`

### 2. Set Up the Dependencies.
  `pip install -r requirements.txt`

### 3. Run the Game ♠️♥️
   `python src/FILENAME.py`
