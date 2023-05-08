# Connect4
This is a Python script that implements a two-player game of Connect Four using Pygame and Numpy libraries.

First, the script creates a 6x7 board using the Numpy library and defines some constants, such as the colors used for the game pieces, the number of rows and columns, and the font used for the game's text.

Then, the script initializes Pygame and creates a graphical window to display the game board. The board is drawn using a nested loop that creates a rectangle for each square in the grid and then draws a circle for each game piece. The pieces are represented by integers 1 and 2 for player 1 and player 2, respectively.

The script uses event handling to detect mouse movements and mouse clicks. When the mouse is moved, the script draws a circle of the appropriate color at the current position of the mouse. When the mouse is clicked, the script determines the column of the clicked square and drops the player's piece into the lowest available position in that column.

The script then checks whether the game has been won by either player by calling the winning_move() function. If a player has won, the script displays a message on the screen and sets the game_over flag to True, which terminates the game loop.

Finally, the script displays the updated game board and waits for the next event to occur.
