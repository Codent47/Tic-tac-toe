# Tic-tac-toe
The classic game has been modified such that the first person to play always wins such that he plays optimally

Game Rules

• Our game follows standard rules of Tic-Tac-Toe at the start.

• The objective is to get three Xs or Os in a row/column/diagonal. You play on a
three by three game board.

• The first player is known as X (Cross) and the second is O (Nought).

• Players take alternate turns placing Xs and Os on the game board until either
one has three in a row/column/diagonal or all nine squares are filled.

• If all 9 squares are filled and there are no 3 consecutive Xs or Os, it leads to a
  DRAW else the winner is whoever gets the consecutive 3.
  Being a 0-sum game, the outcome will always be a draw if both players play optimally. So we have introduced a tiebreaker that will lead   to the first player's victory given he/she plays optimally.
  
Winner is decided using a tiebreaker. The rules are:

• Each player plays alternatively.

• At each turn, a player can choose a sub-matrix/sub-rectangle consisting of 
  CROSSES(X) only and turn it to NOUGHTS(O).
  
• The player who cannot make any move loses.

• The game starts at the board obtained from the draw game.
