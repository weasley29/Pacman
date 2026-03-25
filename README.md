# Pac-Man in Python 🎮

A fully functional, classic Pac-Man clone built from scratch using Python and the [PyGame](https://www.pygame.org/) library. 

## Features ✨

- **Classic Gameplay:** Navigate the maze, eat dots to gain points, and avoid the ghosts!
- **Four Unique Ghosts:** Just like the arcade original, each ghost has its own distinct movement logic:
  - 🔴 **Blinky (Red):** Directly pursues Pac-Man.
  - 🔵 **Inky (Blue):** Uses unpredictable paths to box Pac-Man in.
  - 🌸 **Pinky (Pink):** Attempts to ambush Pac-Man by aiming in front of his current path.
  - 🟠 **Clyde (Orange):** Pursues Pac-Man but occasionally wanders off if he gets too close.
- **Power Pellets:** Eat the large glowing dots to turn the tables! The ghosts become "spooked" (turning blue), allowing Pac-Man to eat them for bonus points.
- **Live Tracking & Score:** Keep track of your high score and remaining lives on the bottom menu.
- **Custom Graphics:** Uses custom asset sprites for Pac-Man and the Ghosts across their different states (alive, spooked, and dead).

## Requirements 📦

To run this game, you will need Python 3 and PyGame installed on your system.

1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
2. Install PyGame via pip:

```bash
pip install pygame
```

## How to Play 🕹️

1. Clone or download this repository to your local machine:
   ```bash
   git clone https://github.com/weasley29/Pacman.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Pacman
   ```
3. Run the game:
   ```bash
   python pacman.py
   ```

* **Controls:** Use the **Arrow Keys** (Up, Down, Left, Right) to guide Pac-Man through the maze.
* **Objective:** Clear the board of all dots to win!
* **Restart:** If you lose or win, press the **Spacebar** to restart the game.

## Project Structure 📁

- `pacman.py`: The main game file. Contains the game loop, rendering logic, ghost pathfinding algorithms, and collision detection.
- `board.py`: Contains the array-based map of the game maze (the walls, dots, power pellets, and ghost spawn gates).
- `assets/`: Contains the sprite images used for Pac-Man and the ghosts.
