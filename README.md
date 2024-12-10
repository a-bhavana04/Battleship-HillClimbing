# Battleship Game with Hill Climbing

## Overview
This project implements the classic **Battleship game** with a computer opponent that uses the **Hill Climbing Algorithm** to optimize its moves. The game features a graphical user interface (GUI) for enhanced player interaction and a well-structured backend engine for game logic.


---

## Features
- **Interactive Gameplay**: Play against the computer or another player using an intuitive GUI.
- **AI Implementation**: The computer opponent intelligently guesses ship locations using Hill Climbing.
- **Game Rules**:
  1. Ships are placed horizontally or vertically (no diagonal placements).
  2. Ships cannot overlap or move during the game.
  3. The game ends when all ships of a player are sunk.

---

## Algorithm: Hill Climbing
- **Objective**: Maximize hits and ultimately sink all ships.
- **Working**:
  1. The AI starts with a random guess until a hit is achieved.
  2. Explores horizontal and vertical tiles adjacent to the hit.
  3. Continues in the direction of subsequent hits until a ship is sunk.
  4. Repeats the process for the remaining ships.


## Installation and Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/a-bhavana04/Battleship-HillClimbing.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Battleship-HillClimbing
   ```
3. Ensure Python 3.8+ is installed.
4. Run the game:
   ```bash
   python gui.py
   ```
---
## Demo
![Board View](images/board_view)
![Demo](image/demo)

