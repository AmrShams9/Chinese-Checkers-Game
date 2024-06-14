Overview
Chinese Checkers AI Game:

A Java-based game featuring a graphical user interface (GUI).
Allows players to compete against an AI opponent.
Uses the Alpha-Beta Pruning algorithm to enhance AI decision-making.
The objective is to move all your marbles to the opposite side of the star-shaped board to win.
Game Rules
Players and Setup:

Intended for two players: Player 1 and Player 2.
The game board is star-shaped with six points, each containing a set of 10 marbles in different colors.
Player 1 controls Green, Blue, and Purple marbles.
Player 2 controls Red, Orange, and Yellow marbles.
Winning condition: Move all marbles to the opposite point of the star.
Gameplay:

Players take turns.
Moves:
Move to an adjacent empty hole.
Hop over an adjacent piece into an empty hole (can be your own or opponent's piece).
Multiple jumps are allowed if there are empty holes to land in.
Game Features
Human vs. Computer Mode:

Play against the AI opponent.
Alpha-Beta Pruning Algorithm:

The AI uses this algorithm to search the game tree efficiently and make optimal decisions by pruning unnecessary branches.
Game Controller:

Manages game flow:
Switching turns between players.
Updating the game board.
Declaring the winner.
Knowledge Representation:

Uses data structures to represent the game state (board and player positions) for easy manipulation and tracking.
Utility Function:

Evaluates the game state for each player.
Assigns positive values to favorable states and negative values to unfavorable ones.
Min-Max Implementation:

The AI explores all possible moves and their outcomes to decide the optimal move.
Difficulty Levels:

Offers different levels of difficulty:
Easy
Medium
Hard
Difficulty is determined by the depth of the Min-Max algorithm, with deeper levels providing more challenging AI.
Launching the Game
Clone the repository or download the project files.
Open the project in a Java IDE (e.g., IntelliJ IDEA, Eclipse).
Compile and run the project.
Select the desired difficulty level (Easy, Medium, Hard).
Start the game and take turns with the AI opponent.
Game Components
GameBoard:

Represents the game board.
Methods to initialize, update, and display the board.
Star-shaped grid with colored marbles.
Player:

Represents a player.
Stores the player's colored sets of marbles (each player has three sets).
Move:

Represents a move made by a player.
Stores source and destination positions.
Validates and applies moves.
GameController:

Manages game flow:
Player turns.
User input.
AI opponent's moves.
Updates game state accordingly.
AIPlayer:

Implements the AI opponent.
Uses the Alpha-Beta Pruning algorithm for decision-making.
Evaluates the game state, explores the game tree, and selects the best move based on the utility function and Min-Max algorithm.
Detailed Description of AI Algorithms
Alpha-Beta Pruning:

An optimization technique for the Min-Max algorithm.
Reduces the number of nodes evaluated in the game tree.
"Prunes" branches that cannot possibly influence the final decision.
Min-Max Algorithm:

Recursive algorithm to determine the optimal move.
Maximizes the utility for the AI and minimizes the utility for the opponent.
Explores all possible moves (nodes) to a specified depth, calculates their utility, and chooses the move with the highest utility.
Implementing and Running the Game
Steps to Implement:

Clone/Download: Obtain the game code from the repository.
Set Up IDE: Import the project into your preferred Java IDE.
Compile: Ensure all necessary libraries and files are included.
Run: Execute the main class to launch the game GUI.
Select Difficulty: Choose the AI difficulty level.
Play: Engage with the AI opponent, following the rules and strategies to win.
This comprehensive setup allows players to experience a competitive game of Chinese Checkers against a strategically challenging AI opponent
