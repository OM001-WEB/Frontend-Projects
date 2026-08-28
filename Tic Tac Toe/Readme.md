# Tic-Tac-Toe Game

A two-player Tic-Tac-Toe game built with JavaScript. Players take turns placing **O** and **X** on the board. The game detects a win or draw, displays the result, and lets players start a new game.

## Features

- Two-player turn-based gameplay
- Alternating **O** and **X** turns
- Automatic winner detection
- Draw detection when all boxes are filled
- Winning and draw messages
- Reset game button
- New game button
- Disabled boxes after a game ends

## Concepts Used

- Variables and Boolean values
- Arrays and nested arrays
- Functions and arrow functions
- Conditional statements
- Loops: `forEach` and `for...of`
- DOM selection and manipulation
- Event listeners
- Button state management with `disabled`
- CSS class manipulation with `classList`
- Game logic using winning patterns

## How It Works

1. Player **O** starts the game.
2. Players take turns clicking an empty box.
3. Each selected box is disabled after a move.
4. After every move, the game checks all possible winning patterns.
5. If three matching symbols appear in a winning pattern, the winner is announced.
6. If all nine boxes are filled without a winner, the game declares a draw.
7. Players can use **Reset Game** or **New Game** to play again.

## Technologies Used

- HTML
- CSS
- JavaScript

## Run Locally

1. Download or clone this repository.
2. Open the `index.html` file in a web browser.
3. Click any empty box to start playing.

## Future Improvements

- Add single-player mode with a computer opponent
- Add score tracking for both players
- Save scores using `localStorage`
- Add sound effects and animations
- Highlight the winning three boxes
- Add responsive design for smaller screens
- Add a dark mode toggle

## Author

Created as a JavaScript practice project to improve understanding of DOM manipulation, event handling, arrays, loops, conditional logic, and basic game development.
