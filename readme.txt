In order to run the game you need python installed along with the numpy module. Please refer to google if you do not know how to do it.

to start the game please type in your console, after you installed python,
"python mancala.py" (omit the quotation marks). 
You may also try double clicking the mancala.py file, although it may not necesarilly work. 

The game by default is set to a mode player vs MiniMax of max depth 5

In order to change the depth of MiniMax, modify the value that is being passed into AI in lines:
MiniMaxAI_1 = GameAI.AI(<yourvalue>)
MiniMaxAI_2 = GameAI.AI(<yourvalue>)

After finishing a game, to begin another one, you need to restart it (unless it is AI vs AI, then it will stop automatically after playing 100 games).
To see two AIs playing against each other, simply uncomment lines:
if(whoseTurn == 0)
	choice = MiniMax_1....  - uncomment to play MiniMax with pruning against MiniMax with pruning
	choice = MiniMax_no.... - uncomment to play Minimax without pruning against MiniMax with pruning
	choice = randint(0,6)   - uncomment to play random agains MiniMax with pruning
	buttonClick(small... 


The no pruning version does not support playing as player 2.

