# 2048 Game 🎮

This is a classic "2048" puzzle game created using pure HTML, CSS, and JavaScript. The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

## Live Preview

[2048](https://emberlast1.github.io/2048-game/)

## Technologies Used

* **HTML5**: To create the basic structure of the game board.
* **CSS3**: For styling the grid, tiles, and the overall game interface.
* **Vanilla JavaScript (ES6+)**:
    * **ES6 Modules & Classes**: The game logic is structured using classes (`Grid`, `Tile`, `Cell`), which makes the code clean, organized, and object-oriented.
    * **Event Handling**: To track key presses and user interaction.

## Getting Started

Since this project has no external dependencies or build steps, running it locally is very simple:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/emberlast1/2048-game.git](https://github.com/emberlast1/2048-game.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd 2048-game
    ```
3.  **Open the `index.html` file in your favorite web browser.**

That's it! You are ready to play.

## Gameplay & Features

* **Objective**: To create a tile with the number **2048**.
* **Controls**: Use the **Arrow Keys** (↑, ↓, ←, →) to move all tiles on the board.
* **Mechanics**: When two tiles with the same number touch while moving, they merge into one tile with double the value.
* **New Tiles**: After each move, a new tile (with a value of 2 or 4) appears in a random empty spot.
* **Scoring**: The score increases every time you merge tiles. The best score is saved.
* **Game Over**: The game ends when there are no empty spots on the grid and no more moves are possible.
* **New Game**: The "New Game" button allows you to restart the game at any time.
