# Tic-Tac-Toe Game with GUI and Minimax Algorithm

This repository contains a Python implementation of a Tic-Tac-Toe game with a graphical user interface (GUI). The game includes player vs. computer functionality, and the computer uses the Minimax algorithm to make optimal moves.

## How to Run the Project

### Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- Pygame library (install using `pip install pygame`)

### Steps to Run the Project:

**Clone the Repository:**

```bash
   git clone https://github.com/MinDutch03/TicTacToe.git
```

1. Navigate to the Project Directory:

```bash
cd Tic-tac-toe
```

2. Run the Game:

```bash
python main.py
```

This command will start the game, and the graphical user interface (GUI) window will open.

3. Playing the Game:

   - Click the "Start" button on the start screen to initiate the game.
   - During the game, click on an empty cell to make a move for the player.
   - The computer opponent (Bot) will automatically make its move using the Minimax algorithm.
   - After the game is over, click the "New Match" button to start a new match or the "Home" button to return to the start screen.
4. Exiting the Game:
   you can simply Close the Pygame window and it will be back to initial state of the game .

### Project Structure :

- __main.py:__ The main game application that runs the game loop and integrates the `GameBoard` class.
- __game_board.py:__ Contains the `GameBoard` class, managing the game logic, drawing the game board, and making moves.
- __minimax.py:__ Contains the `minimax` function, implementing the Minimax algorithm for determining the best move for the computer player.

### Acknowledgments:

This implementation combines the classic game of Tic-Tac-Toe with a user-friendly GUI and a competitive computer opponent using the Minimax algorithm.

## Screenshots of the Game

1. click start
   ![App Screenshot](https://github.com/MinDutch03/TicTacToe/blob/main/App%20screenshot.png)
2. then the game if you press empty cell the bot will add symbol O in other cell :
   ![App Screenshot1](https://github.com/MinDutch03/TicTacToe/blob/main/App%20screnshot1.png)
3. When the Game will finish the result will appear and 2 other buttons will also appear
   ![App Screenshot2](https://github.com/MinDutch03/TicTacToe/blob/main/App%20screenshot2.png)

## Author :

- [Duc Nguyen](https://github.com/MinDutch03)

## MIT License

Copyright (c) [2024] [Duc Nguyen]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.