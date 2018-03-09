# Battleship
The game of battleship written in python.  

Created using Codecademy python lesson.   

Board is a 5x5 square of "O"s that become "X"s when the location has been guessed. A ship's location on the board is randomly determined. Player chooses location to search by entering a row and column number, using 0 indexing. If the guess falls outside of the field or has already been guessed, the player will be told to try again. Player is given 10 tries before the game ends. Game also ends when the player has found the ship.   

Currently pretty bare-bones and could definitely be improved. Possible to-dos:
* multiple ships hidden in the field (be careful not to overlap)
* larger field or various options for field sizes
* perhaps player can choose the field size as a difficulty level
* ships are larger than a single point on the field, actual battleship has various sizes of ships
* multiplayer game mode
* replay option, stored stats
* not in console, actual graphics, sounds
