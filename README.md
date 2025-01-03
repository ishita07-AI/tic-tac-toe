Tic Tac Toe Game
Description
This project implements a Tic Tac Toe game in Python with a console interface. It allows two players to play against each other in turns. The game checks for valid inputs, ensures moves are made in unoccupied spots, and evaluates the winner based on the rules of Tic Tac Toe.
________________________________________
Features
•	Interactive Board Display: The board updates dynamically after each move.
•	Input Validation: Ensures inputs are between 1-9 and the spot is not already occupied.
•	Result Calculation: Determines the winner based on predefined winning conditions.
•	Error Handling: Prompts the player to enter valid moves in case of invalid inputs.
•	Game End Scenarios:
o	Declares a winner if a player achieves 3 consecutive signs.
o	Declares a tie if all spots are filled without a winner.
________________________________________
How to Play
1.	Clone the repository:
git clone <repository-url>
2.	Navigate to the project directory:
cd tic-tac-toe
3.	Run the program:
python tic_tac_toe.py
4.	Follow the instructions displayed on the screen.
________________________________________
Game Instructions
•	The game uses a 3x3 grid:
 1 | 2 | 3
---|---|---
 4 | 5 | 6
---|---|---
 7 | 8 | 9
•	Players alternate turns, starting with Player 1.
•	Enter a number between 1-9 to place your sign ('X' or 'O') in the corresponding spot.
•	The game ends when a player forms a straight line horizontally, vertically, or diagonally, or when the board is full.
________________________________________
Example Console Flow
Welcome to sunny's tic tac toe game.!!
Enter player 1 name: Alice
Enter player 2 name: Bob

Thank you for joining Mr./Mrs. Alice and Mr./Mrs. Bob

This will be our tic tac toe board

 1 | 2 | 3
---|---|---
 4 | 5 | 6
---|---|---
 7 | 8 | 9

Alice's turn:
1

   X |   |  
  ---|---|---
     |   |  
  ---|---|---
     |   |  

Bob's turn:
5

   X |   |  
  ---|---|---
     | O |  
  ---|---|---
     |   |  

Congratulations Alice. You WON.!!
Thank you both for joining.
________________________________________
Requirements
•	Python 3.x
________________________________________
Future Enhancements
•	AI Mode: Add an AI opponent to play against.
•	Save State Feature: Allow saving and resuming games.
•	GUI Version: Develop a graphical interface for better usability.

