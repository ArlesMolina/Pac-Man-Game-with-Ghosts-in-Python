Pac-Man Game with Ghosts in Python
Overview
This project is a simple recreation of the classic Pac-Man game using Python and the Turtle graphics module.
The main character (Pac-Man) can move around a maze and avoid ghosts while collecting points.
The ghosts move automatically within the maze, and Pac-Man can be controlled using keyboard inputs. The game ends when Pac-Man is caught by a ghost.

Features
  Pac-Man Movement: Use the arrow keys to control Pac-Man’s movement through the maze.
  Ghost Movement: Ghosts move automatically in random directions. If Pac-Man collides with a ghost, the game ends.
  Scoring: Points are earned by eating pellets (small dots) spread throughout the maze.
  Dynamic Maze: The maze is defined by a tile-based structure that restricts Pac-Man’s and the ghosts' movement.
  How the Game Works
  Pac-Man: The player can control Pac-Man using the arrow keys (Up, Down, Left, Right).
  Ghosts: Four ghosts move around the maze. They randomly change direction upon hitting walls or corners. If any ghost touches Pac-Man, the game ends.
  Scoring System: Pac-Man scores points by eating pellets. The game tracks the score and displays it on the screen.
  Maze Layout: The game board is created using a grid of tiles, where 0 represents a wall and 1 represents a space where Pac-Man can move and collect pellets.
  
Project Structure
  The game uses the Turtle library to draw and animate the game elements. Here's a breakdown of the core functions:

    square(x, y): Draws a square at the specified (x, y) coordinates in the maze.
    offset(point): Converts a point (Pac-Man or ghost's position) into an index in the tile array.
    valid(point): Checks if a point is a valid position for Pac-Man or a ghost to move to (i.e., not a wall).
    world(): Draws the maze using the tile layout and places the pellets.
    move(): Handles the movement of Pac-Man and ghosts, updates the score, and checks for collisions between Pac-Man and the ghosts.
    change(x, y): Updates the direction in which Pac-Man is moving.

How to Run the Game
Ensure you have Python installed.
Install the required freegames module:

pip install freegames

Save the code as a .py file (e.g., pacman_game.py).

Run the game using the command:

python pacman_game.py

Controls
  Arrow keys: Control Pac-Man’s movement.
  Technologies Used
  Python: The game logic is written entirely in Python.
  Turtle: The graphics for the game are drawn using the Turtle module, which allows for simple 2D rendering.

  
Future Improvements
  Some potential improvements for future versions of the game include:
  
    Adding levels with different maze designs.
    Increasing the difficulty by adding more ghosts or making them faster.
    Implementing power-ups, such as allowing Pac-Man to temporarily eat the ghosts.
Author
Arles Guevara Molina
Project created on: September 14, 2023
