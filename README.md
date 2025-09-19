# SCT_003_Task03
# Tic Tac Toe Game

The **Tic Tac Toe Game** is a simple, interactive web-based version of the classic two-player game, built using **HTML, CSS, and JavaScript**. Players take turns marking X or O in a 3x3 grid, and the first to get three in a row (horizontally, vertically, or diagonally) wins the game. If all cells are filled without a winner, the game ends in a draw.

## Features
- Interactive 3x3 grid with click-to-play functionality.
- Tracks current player and displays whose turn it is.
- Detects win conditions and announces the winner.
- Detects draws when the grid is full without a winner.
- Restart button to reset the game at any time.
- Clean, responsive, and visually appealing interface.

## How It Works
- The board is represented as an array of 9 cells.
- Players alternate turns by clicking on empty cells.
- After each move, the game checks for a win or draw using predefined win patterns.
- The game updates the status message dynamically to show the current player's turn or the game outcome.
- The "Restart Game" button clears the board and resets all variables.

## Usage
1. Open the `index.html` file in a web browser.
2. Click on a cell to make a move.
3. The game will display the current player, detect wins or draws, and update the status message.
4. Click **Restart Game** to play again.

## Tech Stack
- HTML
- CSS
- JavaScript
