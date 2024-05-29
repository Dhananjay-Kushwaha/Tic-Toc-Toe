# Tic-Tac-Toe Game

A simple console-based Tic-Tac-Toe game implemented in C++. This project showcases basic game development, logic implementation, and use of standard C++ libraries. Ideal for beginners to understand the fundamentals of game development in C++.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Running the Game](#running-the-game)
- [How to Play](#how-to-play)
- [Code Explanation](#code-explanation)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Tic-Tac-Toe Game is a two-player game where each player takes turns marking a space on a 3x3 grid with either 'A' or 'B'. The first player to get three of their marks in a row (vertically, horizontally, or diagonally) wins the game.

## Features

- Two-player mode
- Simple text-based user interface
- Input validation to prevent overwriting moves
- Win detection for both players

## Getting Started

### Prerequisites

To run this project, you need:
- A C++ compiler (e.g., GCC, Clang)
- Windows operating system (for `windows.h` library)

### Running the Game

1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/Dhananjay-Kushwaha/tic-tac-toe.git
   ```
2. Navigate to the project directory:
   ```sh
   cd tic-tac-toe
   ```
3. Compile the game using your C++ compiler:
   ```sh
   g++ -o tic_tac_toe main.cpp
   ```
4. Run the compiled program:
   ```sh
   ./tic_tac_toe
   ```

## How to Play

1. The game starts with a 3x3 grid numbered from 1 to 9.
2. Player A is prompted to enter a number corresponding to the grid position they want to mark.
3. Player B takes their turn in the same manner.
4. The game continues until one player has three of their marks in a row or all positions are filled.
5. If a player tries to mark an already occupied position, they are prompted to try again.

## Code Explanation

The core logic of the game is implemented in a `do-while` loop which runs until a win condition is met or the grid is full. The grid is represented by a 2D array of strings. Each player's move is validated to ensure the chosen position is not already occupied.

Key functions include:
- Displaying the game board
- Validating player input
- Checking for win conditions

## Future Enhancements

- Implementing a single-player mode with AI
- Adding a graphical user interface
- Enhancing input validation and error handling
- Refactoring the code for better readability and maintainability

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additions.

## Contact

If you have any questions or feedback, feel free to reach out:

- GitHub: [yourusername](https://github.com/Dhananjay-Kushwaha)
- LinkedIn: [yourLinkedIn](https://www.linkedin.com/in/dhananjaykushwaha)

```

