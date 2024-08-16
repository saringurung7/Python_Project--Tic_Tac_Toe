**Milestone Project: Tic Tac Toe**

Brief overview of the steps involved in creating the game:

**Step 1: Display the Game Board**

Function: display_board(board)
Purpose: Refresh and showcase the game board with each move using IPython.display.clear_output() to ensure a clean and clear display.

**Step 2: Player Input**

Function: player_input()
Purpose: Invite Player 1 to select their marker ('X' or 'O') while automatically assigning the opposite marker to Player 2.

**Step 3: Place Marker**

Function: place_marker(board, marker, position)
Purpose: Position the chosen marker on the game board at the desired location.

**Step 4: Win Check**

Function: win_check(board, mark)
Purpose: Detect whether a player has won by aligning three markers horizontally, vertically, or diagonally.

**Step 5: Random Player Selection**

Function: choose_first()
Purpose: Randomly decide which player takes the first move using the random.randint() function.

**Step 6: Space Availability Check**

Function: space_check(board, position)
Purpose: Confirm that the selected position on the board is free and available for the next move.

**Step 7: Full Board Check**

Function: full_board_check(board)
Purpose: Evaluate whether the board is full, signaling a draw if neither player has won.

**Step 8: Player's Position Choice**

Function: player_choice(board)
Purpose: Prompt the player to select a valid and available position on the board.

**Step 9: Replay Option**

Function: replay()
Purpose: Offer the players the option to start a new game, resetting the game loop for another round of fun.

**Step 10: Main Game Logic**

Purpose: Drive the game using a while loop that handles board resets, marker assignments, and turn alternations between players. Continue until a winner is declared or a draw occurs, then invite the players to replay.
