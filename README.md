# Number-Tile-Game
Number tiles are squares with a number from 1 to 9 at each side. A “board” for the game is a sequence of number tiles satisfying this property:

	The right side of each tile (except the last) = the left side of the next tile on the board

The initial board consists of a single, randomly-generated tile.  This tile is not taken from either player’s hand

There are 2 players in the game, both of whom are the computer. Each player starts with a hand of 5 tiles.  A move is made by a player removing one tile from the hand and placing it on the board, if possible.   A tile may be placed on the board in any of 3 ways:

1.	Between two adjacent tiles
2.	As the new first tile 
3.	As the new last tile

If none of the tiles in the hand can be placed on the board, then one random tile is added to the player's hand and it becomes the other player’s move

A number tile in the players hand can be rotated 90 degrees but once placed on the board its position is fixed  

A round is when player1 makes a move and then player2 makes a move (to make the game fair)  

The game ends when all tiles are removed from one or both player's hand(s).  If both hands are empty at the end of a round the game ends in a tie.  Otherwise the player with the empty hand is the winner.  

Program will consist of 5 classes:
1.	The NumberTile class – models a number tile
2.	The Hand class – models a player’s hand of number tiles
3.	The Board class – models the board where tiles are inserted from the hands
4.	The TileGame class – conducts the game
5.	The TestGameTester class – driver class with main method 
