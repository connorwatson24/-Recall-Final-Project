# -Recall-Final-Project

Game: Recall

Rules/Overview:
Board will start with all LED’s on green
Game will start when the user presses both buttons during the green phase
Board will blink white 3 times, play the starting melody, then start the attempt 
Board will generate a random sequence of red or blue flashes
Red and blue correspond to left and right button inputs
The sequence will start with 1 red or blue flash, an the user will use the left or right buttons to input the correct response 
The number of flashes in a sequence will increase by one for every correct pattern input
If a player inputs the latest sequence correctly, play a quick, two note chime 
After each new sequence plays, the board will turn off all LEDs and wait for the player’s input
During each player attempt, the board will respond to left or right inputs with short red or blue flashes, indicating the board has registered each input
The board will continue this sequence until the user inputs the sequence incorrectly 
When a player inputs the sequence incorrectly, stop responding the board inputs, have the board flash yellow 3 times, play sad melody, and return board to green
The board will stop the game if the user waits too long between or before inputs (10 second timer after the end of the sequence and after each correct input)
If so, play the yellow flash, play the sad melody, end the game, and return board to green 
The board will play a 3 note happy melody for every 5 points the user accumulates
