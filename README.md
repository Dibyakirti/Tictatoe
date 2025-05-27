# Tictatoe
Tic-Tac-Toe: Human vs AI – A Strategic Showdown
Tic-Tac-Toe: Human vs AI is a modern and visually appealing implementation of the timeless paper-and-pencil game. Built with Python and the Pygame library, this game pits a human player against an intelligent computer opponent in a battle of wits on a 3x3 grid. Whether you’re a beginner learning game development or a casual player wanting a fun challenge, this project delivers both learning and entertainment value.

🧠 Game Overview
Tic-Tac-Toe is a two-player game where the goal is to be the first to place three of your marks in a horizontal, vertical, or diagonal row. In this version:

You can choose to play as either X or O.

The AI uses the minimax algorithm (to be implemented) to make optimal moves.

The game runs in a loop with a visually interactive interface and mouse-controlled inputs.

🖥️ Features & Functionality
✅ Interactive Menu
At launch, the game prompts the player to select a symbol: Play as X or Play as O.

Buttons are clearly displayed using a clean and modern font (OpenSans-Regular.ttf) and rendered via Pygame.

🎲 Dynamic Gameplay
The board is drawn as a 3x3 grid.

User moves are made by clicking on empty tiles.

AI moves are calculated using a decision-making algorithm (minimax, to be fully implemented).

The game alternates between player and computer turns seamlessly.

🧠 Artificial Intelligence (Minimax Algorithm)
The game includes a structure for implementing the minimax algorithm, a recursive function that simulates all possible future moves and outcomes to determine the best action.

Once fully implemented, the AI will always play optimally, making it impossible to beat if you don’t play perfectly.

🏁 Endgame Recognition
The game correctly detects when a player wins or if the game ends in a tie.

A message is displayed at the top of the screen declaring the outcome: "Game Over: X wins", "O wins", or "Tie".

🔁 Replay Option
After a game finishes, the player is given the option to start a new game with a single click on the “Play Again” button.

🛠️ Technologies Used
Python 3

Pygame – Used for rendering graphics, detecting user input, and managing the game loop.

Custom Fonts – Utilizes OpenSans-Regular.ttf for a polished look.

📂 Project Structure
runner.py: Main script that initializes the Pygame window, handles UI and input, and drives the gameplay loop.

tictactoe.py: Contains the game logic, including:

Game state representation

Move validation

Result calculation

Terminal state detection

AI decision-making (minimax logic to be implemented)

requirements.txt: Lists dependencies, currently only pygame.

OpenSans-Regular.ttf: Custom font used for all in-game text rendering.


📌 Final Notes
This game is a great foundation for:

Learning Pygame and event-based programming

Understanding and implementing game logic

Exploring artificial intelligence concepts such as the minimax algorithm

Once complete, this project will offer an unbeatable AI opponent, smooth visual interaction, and the charm of a classic game reimagined for the desktop.
