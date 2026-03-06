Guess the number

Overview---------------------------------------------------------------------------------------------------------

The project is a simple game where the player attempts to guess a randomly generated number between 1 and 50. The game includes username validation, input error handling, scores and win rates.
The notebook also includes a flowchart created before writing the final code
The goal is to guess the random number within 10 attempts and after each guess it provides feedback indicating whether the guess what too high or too low along with an accuracy percentage and an option to play again if user wants to.

Requirements------------------------------------------------------------------------------------------------------

Jupyter notebook
Python 3.8 or higher
no external libraries (only python's build in random module)


How to Run the Notebook--------------------------------------------------------------------------------------------

Open Anaconda Navigator
Launch Jupyter Notebook
Navigate to the folder containing the .ipynb file
Click the notebook to open it
Run the code cell using Shift + enter

How the game works------------------------------------------------------------------------------------------------------

1. Username Creation
   user is asked to enter a name with only alphabetical characters allowed. The user has 3 attempts, if all fail the game ends


2. Main Game Loop
   Once a valid username is entered, A welcome message is displayed and the score is set to 0, and play_game is set to "y"


3. Playing a Round
   Each round increases the total number of games played and adds 1 point if the user guesses correctly as well as updating the win rate.
A random number between 1 and 50 is generated and the user has 10 attempts, each guess is validated to make sure it is a number and between 1 and 50.
Feedback is given for each guess if its too high and low with accuracy percentage, if attempts reach 0 the round ends

4. End of Game
The user is asked whether they want to play again (y/n) and any invalid inputs trigger a error message and re-prompt
When the user chooses not to continue the game ends with total games played, final score and win rate.

GitHub repo----------------------------------------------------------------------------------------------------------------
https://github.com/adck872/guessing_number_game

