# TicTacToe
This is a simple implementation of the Tic Tac Toe game in Python. The game can be played with two players in a one-vs-one mode. The game board is displayed, and players take turns entering their moves until one player wins or the game ends in a tie.

# How to Run the Game
  1. Download or copy the code into a Python file (e.g., tictactoe.py).

  2. Make sure you have Python installed on your system.

  3. Open a terminal or command prompt and navigate to the directory where the Python file is located.

  4. Run the following command to start the game:
        `python tictactoe.py`
        
# How to Play
  1. The game starts with an empty 3x3 grid.

  2. Player 1 is assigned the symbol 'X', and Player 2 is assigned the symbol 'O'.

  3. The board is represented by a list of strings, where each string corresponds to a cell on the grid.

      - The numbering of cells is as follows:<br>
          1 | 2 | 3<br>
          4 | 5 | 6<br>
          7 | 8 | 9<br>
       
   4. Players take turns entering the number of the cell they want to mark with their symbol.

   5. The game validates the input and updates the board accordingly.

   6. The game continues until one player wins or the game ends in a tie.

         - A player wins by having three of their symbols in a row, column, or diagonal.
    
   7. After the game ends, the winner is announced, or it is declared a tie.

   8. Players can choose to play again or exit the game.


  # Game Logic
  The game logic is implemented in the provided code. The key components of the implementation are as follows:

  - The game board is represented by a list called board, where each element represents a cell on the grid.<br>
  - The printBoard(board) function is used to display the current state of the game board.<br>
  - The playerInput(board) function handles player input and updates the board accordingly.<br>
  - The game checks for a win or tie condition after each move using the checkHor(board), checkRow(board), checkDiag(board), and checkTie(board) functions.<br>
  - The current player is tracked using the currentPlayer variable, which switches between 'X' and 'O' after each move.<br>
  - The game ends when there is a winner or a tie, and the result is displayed using the checkWin() function.<br>
  - Players can play again by running the game again.

# Contributions
Contributions to the Tic Tac Toe program are welcome. If you find any bugs, issues, or want to add new features, please submit a pull request or create an issue on the project's repository.

# Acknowledgments
The Tic Tac Toe program was developed with reference to various Python programming resources and examples available online. Special thanks to the Python community for their valuable contributions and support.

If you have any further questions or need assistance, please contact ishitachoudhuri3@gmail.com

Enjoy your game!
