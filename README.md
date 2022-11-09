# Tennis-Predictions
AML Final Project Cornell Tech

## Processed Data Explanation:
After pre-processing, we obtained a dataset with 93781 rows and 16 columns. 
The meaning and datatype of each column is explained below:
- Date (*DateTime*): Date on which the game was played. - to drop for training -
- Tourney (*String*): Name of the tournament. - to drop for training -
- Location (*String*): Country in which the game was played. - to drop for training -
- BestOf (*Numeric*): Best of sets played.
- Player1 (*String*): Full name of the first player who played. - to drop for training - 
- Player1Age (*Numeric*): Age of the first player
- Player1Nationality(*String*): Country in which player1 was born
- Player1PlaysHome (*Boolean*): True if Player1Nationality and the Location of the tourney match, False otherwise.
- Player2 (*String*): Full name of the second player who played. - to drop for training - 
- Player2Age (*Numeric*): Age of player2
- Player2Nationality(*String*): Country in which player2 was born
- Player2PlaysHome (*Boolean*): True if Player2Nationality and the Location of the tourney match, False otherwise.
- Player1SetsWon (*Numeric*): Number of sets won by player1.
- Player1SetsLost (*Numeric*): Number of sets lost by player1.
- Player1GamessWon (*Numeric*): Number of games won by player1.
- Player1GamesLost (*Numeric*): Number of games lost by player1.
- Player1Won (*Boolean*): __TARGET__ 1 If player1 won, 0 if player1 lost.
