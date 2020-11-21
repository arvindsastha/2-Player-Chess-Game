# 2-Player-Chess-Game

## Introduction ##
My very first coding project. Please do not mind coding style and efficiency. <br>Created a 2-player chess game using data structures in C.

` Data Structure used: **“Linked List”**`

## Modules ##
1] **Create:** This module is used to create horizontal links in the chess board. 

2] **Verticallink:** This module is used to create vertical links in the chess board.

3] **Crosslink1:** This module is for creating diagonal links in one direction. ( i.e, from top left to bottom right)

4] **Crosslink2:** This module is for creating diagonal link in another direction. ( i.e, from top right to bottom left)

5] **Find_node:** This module is used to find the current node of the given COIN NAME. It is found by traversing each row in a horizontal way with separate pointers. It returns the node to the calling function.

6] **Final_node:** This module is used to find the final node of the COIN based on the POSITION given by the user. It is found by traversing each row in a horizontal way with separate pointers with the help of the POSITION given by the user. It returns the node to the calling function.

7] **Valid_pos:** This module is used to check if the POSITION given by the user is valid or not. It will return 1 if the position is valid or else 0.

8] **Invalid:** This module prints the message “INVALID MOVE” in a new screen. It returns nothing.

9] **Check:** This module is used to check if the final-node’s coin is a king or not. If yes, it prints the message “CHECK” in a new screen and it returns 1. If no, it returns 0.

10] **Checkmate:** This module is used to find if the game is over. Each time when this function is called, every coin on the board is checked for the possibility of crossing ‘OPPONENT’S king’.  If yes, the function CHECK is called. If no, the game proceeds.

11] **Display:** This module is used to print the chess board. The first line and first column will have the POSITIONS. Rest of the rows & columns are printed accordingly (i.e, if it has a coin, then that coin name is printed. If no coin, then tab is printed).
