### Rock Paper Scissors

This repository contains two versions of a simple Rock Paper Scissors game implemented in a single HTML file. Both versions allow a player to choose between Rock, Paper, and Scissors, with the computer's move being randomly generated. The outcome of the game (win, lose, or tie) is displayed in an alert box.

#### How to Play
1.  Open either of the HTML files (`RPS with functions.html` or `Rock-paper-scisssors.html`) in a web browser.
2.  Click one of the three buttons ("Rock", "Paper", or "Scissors") to make your move.
3.  An alert box will appear, showing your move, the computer's move, and the result of the game.

#### File Descriptions
* `Rock-paper-scisssors.html`: This is the initial version of the game. The JavaScript logic for choosing the computer's move and determining the winner is duplicated within the `onclick` attribute of each button.
* `RPS with functions.html`: This is a refactored version of the game. The JavaScript logic has been moved into separate functions (`playGame` and `pickComputerMove`), which are then called by the buttons. This makes the code more organized and easier to maintain.

#### Technologies Used
* **HTML**: For the page structure and buttons.
* **JavaScript**: For the game's logic, including generating a random computer move and determining the winner.
