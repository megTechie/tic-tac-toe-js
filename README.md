# Tic Tac Toe Game

A simple and responsive **Tic Tac Toe** game built using **HTML, JavaScript, and Tailwind CSS**.
This project allows two players to play Tic Tac Toe in the browser with a clean user interface.

## Features

* Two-player Tic Tac Toe game
* Player turns between **O** and **X**
* Winner detection
* Reset game option
* New game option after winning
* Responsive design using Tailwind CSS
* Simple and beginner-friendly JavaScript logic

## Technologies Used

* HTML
* CSS
* Tailwind CSS
* JavaScript

## Project Structure

```bash
TicTacToe/
│
├── index.html
├── script.js
└── src/
    ├── input.css
    └── output.css
```

## How to Run the Project

1. Clone or download this project.

2. Open the project folder in VS Code.

3. Install Tailwind CSS if it is not already installed.

4. Run this command in the terminal:

```bash
npx tailwindcss -i TicTacToe/src/input.css -o TicTacToe/src/output.css --watch
```

5. Open `index.html` in your browser.

## How to Play

1. The game starts with player **O**.
2. Players take turns clicking on empty boxes.
3. Player **O** and player **X** mark the boxes one by one.
4. The first player to match three symbols in a row, column, or diagonal wins.
5. After winning, a message is displayed.
6. Click **New Game** or **Reset Game** to play again.

## Winning Patterns

The game checks the following winning patterns:

```js
[0, 1, 2]
[0, 3, 6]
[0, 4, 8]
[1, 4, 7]
[2, 5, 8]
[2, 4, 6]
[3, 4, 5]
[6, 7, 8]
```

## Main JavaScript Logic

* `turn0` is used to track the current player.
* Each box has a click event listener.
* After every move, the game checks for a winner.
* If a player wins, all boxes are disabled.
* Reset and New Game buttons restart the game.

## Screenshot

You can add your project screenshot here:

```md
![Tic Tac Toe Screenshot](screenshot.png)
```

## Future Improvements

* Add draw match detection
* Add score tracking
* Add sound effects
* Add single-player mode with computer
* Improve UI animations

## Author

**Megha**
