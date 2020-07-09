# TicTacToe
A simple tictactoe game made using javascript using the framework jquery to speed things up a bit and bootstrap

The game is a 3 by 3 board that you need to make a row to win, you always starts the game, next your oponent will make it's move, your oponent is a machine, i designed it so that it has some priority on the moves, at the bottom of the list of prioritys is a random move, next it checks if the human player is close to make a row so it makes a move to prevent that, and the top priority is the winner move, it happens when the machine is missing one to complete a row, so the this is the move that will make it win the game.

My to do list consists of:

1- Make a better layout;
2- Remove Jquery and use just vanilla Javascript; /* i used jquery to make it faster since i'm already used to it */
3- Use a button to "flip a coin" to determine who starts playing;
4- Make a winner chart;
5- Use node.js to save the games on a database to use it as a reference of the best move to make;
