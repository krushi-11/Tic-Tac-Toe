# Tic-Tac-Toe

A classic Tic Tac Toe game implementation using Java Swing with a graphical user interface. The game features a 3x3 grid where two players can compete, keeping track of their scores and displaying game outcomes.

## Features

- Graphical User Interface using Java Swing
- Two-player gameplay (X and O)
- Score tracking for both players
- Game state management
- Reset game functionality
- Clean exit option
- Player turn indicator
- Win detection system

## Prerequisites

To run this game, you need:
- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)
- An IDE that supports Java (e.g., NetBeans, Eclipse, IntelliJ IDEA)

## Project Structure

The project consists of two main classes:
- `MainFrame.java` - Contains the GUI implementation and game control logic
- `Storage.java` - Handles the game state and matrix operations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/tictactoe.git
```

2. Open the project in your preferred Java IDE

3. Build and run the `MainFrame.java` file

## How to Play

1. The game starts with Player X's turn
2. Players take turns clicking empty squares to place their mark (X or O)
3. The game ends when:
   - A player wins by getting three marks in a row (horizontally, vertically, or diagonally)
   - The board is full with no winner (draw)
4. The score is updated automatically for each win
5. Use the "Reset Game" button to start a new game
6. Use the "Exit" button to close the application

## Game Controls

- Click any empty square to place your mark
- "Reset Game" button: Resets the entire game including scores
- "Exit" button: Closes the application after confirmation

## Features Explained

### Score Tracking
- The game keeps track of wins for both X and O players
- Scores are displayed on the right side of the game board
- Scores can be reset using the Reset Game button

### Turn Indicator
- The current player's turn (X or O) is displayed on the right panel
- Updates automatically after each valid move

### Win Detection
- Automatically detects winning combinations:
  - Horizontal rows
  - Vertical columns
  - Diagonal lines
- Shows a popup message announcing the winner
- Automatically updates the score for the winning player

### Draw Detection
- Automatically detects when the game ends in a draw
- Shows a "No Winner Game Over" message
- Allows starting a new game

## Author

Krushikesh Thotange

## Future Enhancements

Possible improvements that could be added:
- AI opponent implementation
- Customizable player names
- Sound effects
- Game history tracking
- Different board sizes
- Network multiplayer support
- Custom themes/skins
