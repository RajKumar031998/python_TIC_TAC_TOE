# python_TIC_TAC_TOE
**A simple game made by using basic functions **

This is a summary of a** tic-tac-toe ** game written in Python and run in a Jupyter notebook. The game allows two players to choose their markers (X or O) and take turns placing them on a 3x3 board. The game ends when one player has three of their markers in a row, column, or diagonal, or when the board is full and there is no winner. The game uses the following functions:

**display_board:** This function takes a list of 10 strings representing the board (index 0 is ignored) and prints the board with some formatting.
**player_input:** This function asks player 1 to choose their marker and returns a tuple of (player 1 marker, player 2 marker).
**place_marker: **This function takes the board list, a marker, and a position (1-9) and assigns the marker to the board at that position.
**win_check:** This function takes the board list and a marker and returns True if that marker has won the game, or False otherwise.
**choose_first:** This function uses the random module to randomly decide which player goes first and returns a string indicating that.
**space_check:** This function takes the board list and a position (1-9) and returns True if the position is empty, or False otherwise.
**full_board_check:** This function takes the board list and returns True if the board is full, or False otherwise.
**player_choice:** This function takes the board list and asks the player to choose their next position (1-9) and returns it as an integer. It also checks if the position is valid and empty using space_check.
**replay:** This function asks the player if they want to play again and returns True or False.

The game uses a while loop to run until the players decide to quit. It also prints some messages to guide the players and congratulate the winner or announce a tie.
