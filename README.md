# dice-game
C program to simulate a dice game

 A program to simulate a dice game. The game details are as follows: Dice game is played by 2 players. The players throw the dices in order. They collect points as game proceeds. Game ends when the first player’s dice sum is twice the second player’s dice sum in the consecutive throws. The scoring is based on the following rules:  Players get the points as the half of the sum of the dices normally. However, if the two dices difference is 4, player doesn’t get any points but gets the right to throw the dices again until the sum of the two dices are greater than 8. If the player throws 3-3 or 6-6, s/he gets the right to throw 3 times consecutively in which the same dice values will not be counted as points.  
 
When the program ends, it will display the scores of each player, number of times the dices are thrown and the winner. 
The following menu is displayed continuously, until user wants to quit. srand() function is used to generate random dice values.  
Sample Run: 
********************* Welcome to Dice Game ********************* 
Input  P to play the game, S to display the total score, Q to Quit:P 
 
Throw the dice for player 1: 1 2 
Throw the dice for player 2: 3 2 
Throw the dice for player 1: 1 1 
…. 
Player 1: 45 points 
Player 2: 39 points 
Total of 54 throws are performed. 
Winner is: Player 1 ….. 
Input  P to play the game, S to display the total score, Q to Quit:Q 
Bye! 
