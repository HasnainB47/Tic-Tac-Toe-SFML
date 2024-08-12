# Tic-Tac-Toe Game

This project is a graphical implementation of the classic Tic-Tac-Toe game using the SFML library in C++. The game is designed for two players and includes features such as game state tracking, scorekeeping, and an easy-to-use graphical interface.

## Features

- **Two-Player Mode**: Play against a friend on the same computer.
- **Graphical Interface**: Uses SFML to render a simple and clean UI for the game.
- **Game Statistics**: Tracks the number of games played, wins, losses, and draws for each player.
- **Reset Functionality**: Easily reset the board to start a new game.
- **Console Window Hidden**: The console window is hidden during gameplay for a better user experience.

## Getting Started

### Prerequisites

- **SFML Library**: You need to have the SFML library installed on your system. You can download it from the official [SFML website](https://www.sfml-dev.org/download.php).

### Build the Project
  - Open the project in your preferred C++ IDE (e.g., Visual Studio, CLion).
  - Ensure that the SFML library is correctly linked.
  - Build and run the project.
    
### Usage
  - **Run the Game:** After building the project, launch the game executable.
  - **Enter Player Names:** The game will prompt you to enter the names of Player 1 and Player 2.
  - **Play: **Click on the board to place your piece (X or O). The game will automatically switch turns between the two players.
  - **Reset:** Click the reset button to start a new game.
    
### Game Statistics
  - Game statistics are saved in a file named `game_stats.txt`. This file will be created in the same directory as the executable and will keep track of the total games played, wins, losses, and draws.

### Files and Resources
  - **Resources Folder:** Contains all the necessary images (background, board, pieces) and the font used in the game.
  - **Source Code:** The core game logic and rendering are handled in the main.cpp file.

### License
  - This project is licensed under the MIT License - see the LICENSE file for details.
