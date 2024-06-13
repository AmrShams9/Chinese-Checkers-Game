Chinese Checkers AI Game
This Java-based Chinese Checkers game features a graphical user interface (GUI) and allows you to compete against an AI opponent using the Alpha-Beta Pruning algorithm. The goal is to move all your marbles to the opposite side of the star-shaped game board. The first player to do so wins.

Game Rules
The game is intended for two players.
The game board is a star with six points, each containing a different colored set of 10 marbles.
Player 1 controls the Green, Blue, and Purple sets, while Player 2 controls the Red, Orange, and Yellow sets.
A player wins by moving all their marbles to the opposite side of the star, taking the place of the opponent's marbles.
How to Play
Players take turns moving their pieces across the board.
During a turn, a player can move a piece to any adjacent empty hole.
A player can also hop over an adjacent piece into an empty hole. This piece can be their own or the opponent's. Multiple jumps are allowed in one turn, as long as there are empty holes to land in.
Game Features
Human vs. Computer Mode: Play against the AI opponent.
Alpha-Beta Pruning Algorithm: The AI uses this algorithm to efficiently search the game tree and make optimal decisions.
Game Controller: Manages game flow, switching turns between players, updating the game board, and declaring the winner.
Knowledge Representation: Uses data structures to represent the game state, including the board and player positions, allowing easy manipulation and tracking.
Utility Function: Evaluates the game state for each player, assigning positive values to favorable states and negative values to unfavorable ones.
Min-Max Implementation: Determines the AI's moves by exploring all possible moves and their outcomes to make optimal decisions.
Difficulty Levels: Offers different levels of difficulty (Easy, Medium, Hard) based on the depth of the Min-Max algorithm, with deeper levels providing more challenging AI.
Launching the Game
Clone the repository or download the project files.
Open the project in your preferred Java development environment (IDE).
Compile and run the project.
Select the desired difficulty level (Easy, Medium, Hard) before making the first move.
Take turns with the AI opponent, following the rules mentioned above.
Game Components
GameBoard: Represents the game board, providing methods to initialize, update, and display it. The board is a star-shaped grid with colored marbles.
Player: Represents a player, storing their colored sets of marbles. Each player has three sets of marbles.
Move: Represents a move made by a player, storing the source and destination positions. It helps in validating and applying moves.
GameController: Manages the game flow, player turns, user input, and the AI opponent's moves, updating the game state accordingly.
AIPlayer: Implements the AI opponent using the Alpha-Beta Pruning algorithm for decision-making, evaluating the game state, exploring the game tree, and selecting the best move based on the utility function and Min-Max algorithm.


