# BoggleServer
A simple server for boggle players that hosts 2 minute long games on a randomly generated board.
Set the desired host port in the makefile and connect using netcat. 

Add to your current game score using 'add_score'
List the top 3 players on the server with 'top_3'
Begin a new game with 'new_game'
Terminate your connection using 'quit' or simply exit netcat, the server will remove your connection automatically.
