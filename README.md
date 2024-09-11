Pac-Man Game in Python
Overview
This project is a Python-based implementation of the classic Pac-Man game using pygame for graphical rendering and numpy for handling maze data. It includes sprite management, text rendering, and game mechanics.

File Structure
sprites.py - Contains classes for handling sprite sheets and specific sprites for Pac-Man, ghosts, fruits, and lives.
text.py - Manages text rendering, including scores, levels, and game state messages.
vector.py - Provides a 2D vector class for handling positions and movement in the game.
Dependencies
pygame==2.6.0
numpy==2.1.0
Installation
Ensure you have Python installed on your system.

Install the required libraries using pip:

bash
Copy code
pip install pygame numpy
Download the project files and place them in your working directory.

Files
sprites.py
This file contains classes for handling different types of sprites in the game.

Spritesheet: Base class for loading and managing spritesheets.
PacmanSprites: Manages Pac-Man sprites and animations.
GhostSprites: Manages ghost sprites based on their state and direction.
FruitSprites: Handles sprites for fruits with different images based on the game level.
LifeSprites: Manages the sprites representing Pac-Man's lives.
MazeSprites: Handles the maze background and wall sprites, including rotation.
text.py
This file includes classes for rendering text in the game.

Text: Manages individual text objects, including their position, color, size, and visibility.
TextGroup: Manages a collection of text objects, updating and rendering them, and handling game-specific messages like scores and level information.
vector.py
Provides a simple 2D vector class for handling positions and movements in the game.

Vector2: Class for 2D vector operations, including addition, subtraction, multiplication, and magnitude calculations.
Usage
Load the Game Assets: Ensure that your game assets, including the spritesheet and font file, are located in the correct directories.

Initialize Pygame: Create a pygame window and initialize the game loop.

Create Sprite Instances: Instantiate classes from sprites.py to manage different game entities (Pac-Man, ghosts, fruits, etc.).

Update and Render: In the game loop, update the sprites and text objects and render them to the screen.

Handle Events: Process user inputs and game events to control Pac-Man and interact with the game environment."# pacman4.0" 
