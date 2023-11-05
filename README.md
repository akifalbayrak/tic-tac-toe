# React Tic-Tac-Toe Game

This repository contains a simple Tic-Tac-Toe game built using React. Players can take turns, customize their names, and compete to achieve a winning combination or a draw on a 3x3 game board. The game logs all moves and displays the winner or a draw at the end of the game. A "Restart" button is provided to start a new game.

## Features

- **Two Players:** Two players can play against each other, taking turns to make their moves.

- **Game Board:** The game board is displayed as a 3x3 grid. Players can click on empty squares to make their moves.

- **Game Log:** The game log keeps track of all the moves made by both players, providing a record of the game's progress.

- **Customizable Names:** Players can customize their names by clicking on their respective symbols (X and O). The changes are reflected in the game.

- **Game Over Screen:** When the game is won by a player or ends in a draw, a game over screen is displayed, announcing the winner or a draw.

- **Restart:** A "Restart" button is available to start a new game.

## Getting Started

To run the Tic-Tac-Toe game on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-tic-tac-toe.git
   ```

2. Navigate to the project directory:

   ```bash
   cd react-tic-tac-toe
   ```

3. Install the required dependencies using [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/):

   ```bash
   npm install
   # or
   yarn install
   ```

4. Start the development server:

   ```bash
   npm start
   # or
   yarn start
   ```

5. Open your web browser and go to [http://localhost:3000](http://localhost:3000) to play the game.

## How to Play

1. Enter the names of Player 1 (X) and Player 2 (O) by clicking on the input fields above their respective symbols.

2. Click on an empty square to make your move. Players take turns, and Player 1 starts as "X."

3. The game log on the right side of the screen will record all the moves made by the players.

4. The game will announce the winner or a draw when the game is over. You can click the "Restart" button to start a new game.

## Customizing Player Names

You can customize the names of Player 1 (X) and Player 2 (O) by clicking on the input fields above their symbols and entering new names. The changes will be reflected in the game.

## Development

This Tic-Tac-Toe game is built using React and state management with React Hooks. The game logic is implemented to check for a winning combination or a draw. Player names can be updated dynamically.

The project is structured with the following components:

- `Player`: Responsible for displaying player information and allowing name customization.
- `GameBoard`: Displays the game grid and handles square selection.
- `Log`: Logs all game moves.
- `GameOver`: Displays the game result and provides a "Restart" button.

- ![image](https://github.com/akifalbayrak/tic-tac-toe/assets/142679378/73ca134c-67c9-46ac-a10e-12a93df07501)
