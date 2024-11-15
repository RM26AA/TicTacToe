# Tic Tac Toe Game

## Overview
This project is a graphical Tic Tac Toe game implemented in Java using the Swing library. The game allows two players to take turns marking "X" or "O" on a 3x3 grid until one player wins or the game results in a draw. This project showcases Java programming and GUI design skills.

## Features
- **Interactive GUI**: The game board is displayed using Swing components, with buttons for each grid cell.
- **Two-Player Mode**: Allows two players to compete, alternating turns between Player X and Player O.
- **Win Detection**: Checks for winning conditions after each move and displays the winner.
- **Draw Handling**: Declares the game as a draw if all cells are filled without a winner.

## Technologies Used
- **Java**: Uses object-oriented programming for managing game logic and tracking player turns.
- **Swing Framework**: Provides a graphical user interface, including the game board, labels, and buttons.
- **Event Handling**: Captures user interactions to update the game state in real time.

## Files
- **App.java**: The entry point, initializing the game by creating an instance of the `TicTacToe` class.
- **TicTacToe.java**: Contains the main game logic, GUI setup, event handling, and win/draw conditions.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-name.git
2. Compile the Java files:
   ```bash
   javac App.java TicTacToe.java
3. Run the application:
   ```bash
   java App

## How to Play:
- The game starts with Player X. Players take turns selecting a cell in the 3x3 grid.
- The first player to align three of their marks (X or O) horizontally, vertically, or diagonally wins.
- If all cells are filled without a winner, the game ends in a draw.

## License:
This project is open-source and available under the MIT License.

## Author:
Romeo Maunick - A developer enthusiastic about creating interactive games and enhancing programming skills through classic games.

















