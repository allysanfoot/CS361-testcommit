# CS361-partner project

## How to request data from microservice
The microservice file, microservice.py, will read and pull data from the list_of_monopoly_winners.txt in a function called rewrite_top_scores(). The 
function will be imported into the board.py file, which would allow for the user to call rewrite_top_scores from within board.py.
The function will store each line from the text file in a list, which will then be further parsed out and stored in two separate lists: one containing
the top 5 winners by cash and the other containing the top 5 winners by minimum amount of turns.

## How to receive data from microservice
The data from the microservice will be put out and overwrite the text file, high_score.txt. The function rewrite_top_scores() will be called from within board.py,
upon which it will update high_score.txt with the list of the new top 5 players by balance and the top 5 players by turns. High_score.txt is a file that can be 
found from within the same folder/directory as board.py.
