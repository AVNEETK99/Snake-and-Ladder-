# Snake-and-Ladder

Snakes and Ladders is a classic board game that has been played for centuries. The game is typically played on a square board that is divided into a grid of 100 squares. The board contains a series of numbered squares that are connected by a set of snakes and ladders.

The game is played by rolling a die or dice and moving a game piece along the numbered squares on the board. When a player lands on a ladder, they move their game piece up the board to the higher numbered square. However, if a player lands on a snake, they must move their game piece down the board to the lower numbered square.

The objective of the game is to be the first player to reach the end of the board, which is typically the square numbered 100. The game can be played by two or more players, and the rules can be modified to suit different skill levels and ages.

Snakes and Ladders is a fun game that can be enjoyed by people of all ages. It is also a great way to teach children basic counting and number recognition skills, as well as strategy and sportsmanship.

## Instructions to run the game
* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python p.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The first three lines are standard imports for time, random and sys modules in Python.

* ```SLEEP_BETWEEN_ACTIONS``` is a constant variable that defines the duration of a delay of 1 second between two actions in the game.

* ```MAX_VAL``` is the maximum value of the board (100 in this case).

* ```DICE_FACE``` is the maximum number of faces on a dice in this game (6 in this case).

* ```snakes``` is a dictionary that maps the head of a snake to its tail.

* ```ladders``` is a dictionary that maps the bottom of a ladder to its top.

* ```player_turn_text``` is a list of different messages that can be displayed before a player's turn.

* ```snake_bite``` is a list of messages that can be displayed when a player lands on a snake.

* ```ladder_jump``` is a list of messages that can be displayed when a player lands on a ladder.

* ```welcome_msg()``` function displays the welcome message for the game and the rules.

* ```get_player_names()``` function prompts the user to enter the name of the players and returns their names.

* ```get_dice_value()``` function generates a random integer between 1 and DICE_FACE and returns it.

* ```got_snake_bite()``` function displays a message when a player lands on a snake.

* ```got_ladder_jump()``` function displays a message when a player lands on a ladder.

* ```snake_ladder()``` function simulates the movement of the player's position based on the dice value and the location of the snakes and ladders.

* ```check_win()``` function checks if the player has won and ends the game if true.

* ```start()``` function is the main function that initializes the game and the positions of the players. It contains a loop that alternates between the players until one of them wins.
