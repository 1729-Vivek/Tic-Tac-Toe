
# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game built using React.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Helper Functions](#helper-functions)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project implements a basic Tic-Tac-Toe game where two players can play against each other. The game board is a 3x3 grid. Players take turns to place their mark ('X' or 'O') on the board. The game checks for a winner after each move and declares the winner when a player has three of their marks in a row, column, or diagonal.

## Features

- Two-player game
- Display current player's turn
- Check for winner
- Reset game board

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/tic-tac-toe.git
    cd tic-tac-toe
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm start
    ```

## Usage

- Open the game in your browser (typically at `http://localhost:3000`).
- Click on a cell to place your mark.
- The game will automatically check for a winner and display the result.
- Click the "Reset" button to start a new game.

## Components

### `App.js`

The root component that renders the `Grid` component.

### `Grid.js`

Handles the game logic, including state management for the game board, current turn, and winner. It also provides the reset functionality.

### `Card.js`

Represents each cell in the game grid. It displays the player's mark and handles click events to place the mark.

### `Icon.js`

Renders the appropriate icon based on the player's mark ('X', 'O', or empty).

## Helper Functions

### `checkWinner.js`

Contains the `isWinner` function, which checks the game board for a winning combination.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
