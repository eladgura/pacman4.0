Pac-Man Game in Python
Overview
This project is a Python-based recreation of the classic Pac-Man arcade game. Built with pygame for graphical rendering and numpy for maze data handling, it includes sprite management, text rendering, and core gameplay mechanics to create a retro gaming experience.

Features
Character Sprites: Animations for Pac-Man, ghosts, fruits, and lives.
Maze Layout: Dynamically rendered maze backgrounds with customizable walls.
Score Tracking: Real-time score updates and game state messages.
User Interaction: Keyboard controls for moving Pac-Man, with responsive enemy AI.
Requirements
Make sure Python (version 3.8 or higher) is installed on your system. The following Python libraries are required:

pygame==2.6.0
numpy==2.1.0
To install the requirements, use the provided requirements.txt file:

bash
Copy code
pip install -r requirements.txt
Alternatively, create this file by running:

bash
Copy code
pip freeze > requirements.txt
Directory Structure
plaintext
Copy code
project-root/
├── sprites.py       # Handles sprite sheets and sprite management
├── text.py          # Renders text for scores, levels, and game states
├── vector.py        # 2D vector class for movement and positioning
├── run.py           # Main file to initialize and run the game
└── requirements.txt # Dependencies for running the game
Project Files
sprites.py
Manages sprite handling for game characters and other entities:

Spritesheet: Base class for loading and processing sprite sheets.
PacmanSprites: Manages Pac-Man animations.
GhostSprites: Handles ghost animations and state changes.
FruitSprites: Manages fruit sprites by game level.
LifeSprites: Controls lives display with Pac-Man icons.
MazeSprites: Manages the maze layout, wall positioning, and rotations.
text.py
Contains classes for displaying text on the screen:

Text: Controls individual text properties like position, color, size, and visibility.
TextGroup: Manages a collection of text objects for game messages, such as the score and level.
vector.py
Defines a 2D vector class for handling positional data:

Vector2: Supports basic vector operations, including addition, subtraction, multiplication, and magnitude calculations.
run.py
The main script that initializes the game and runs the main game loop. It includes:

Asset Loading: Ensures sprites and fonts are correctly loaded.
Event Handling: Processes keyboard inputs to control Pac-Man.
Game Loop: Updates sprites, renders frames, and manages game states.
Setup and Usage
Clone the Repository: Clone the project repository to your local machine.

bash
Copy code
git clone <repository-url>
cd <repository-directory>
Install Dependencies: Use the requirements.txt file to install the necessary libraries:

bash
Copy code
pip install -r requirements.txt
Prepare Game Assets: Ensure all necessary game assets (e.g., spritesheets, fonts) are in the correct directories.

Run the Game: Start the game by running run.py:

bash
Copy code
python run.py
Controls
Arrow Keys: Move Pac-Man.
ESC: Exit the game.
Contributing
To contribute, fork the repository and submit a pull request. Please ensure that your changes are well-documented and tested.

License
This project is open-source under the MIT License. See the LICENSE file for details.

