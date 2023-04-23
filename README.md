# Tic-Tac-Toe

This project is a Tic-Tac-Toe game built with HTML, CSS, and JavaScript.

## Description

The game is played on a 6x7 grid, and the objective is to get four pieces in a row (horizontally, vertically, or diagonally). There are two players, and they take turns placing their pieces on the board. Player one is represented by the color red, and player two is represented by the color yellow. The game ends when one of the players gets four pieces in a row, or when the board is full (in which case the game is a draw).

## How to play

1. Open the `index.html` file in your web browser.
2. Click on any of the squares on the game board to place a piece.
3. Take turns with the other player until one of the win conditions is met or the board is full.
4. To play again, refresh the page.

## Technical details

The game board is created using a 6x7 grid of `div` elements. The squares are selected using the `querySelectorAll()` method, and the current player and result displays are selected using `querySelector()`. The winning combinations are defined in the `winningArrays` array.

The `checkBoard()` function is used to check if one of the win conditions is met. It loops through each of the winning combinations, and for each combination, it checks if all the squares in that combination have the class of the current player. If all the squares in a combination have the class of player one, player one wins. If all the squares have the class of player two, player two wins. If none of the win conditions are met and the board is full, the game is a draw.

## Future improvements

Some possible improvements to this game could include:

- Adding an option to play against the computer.
- Adding an option to choose the size of the board.
- Adding animations and sound effects to make the game more engaging.
- Adding a score board to keep track of wins and losses.
