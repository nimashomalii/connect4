# connect4
Connect Four is a strategy board game in which players take turns dropping a piece into a selected column. The pieces stack from the bottom up in the columns. The goal of the game is to be the first to align four pieces of the same color in a row, either horizontally, vertically, or diagonally. The player who achieves this wins the game.
![image](https://github.com/user-attachments/assets/d38e0f6b-a253-4e27-99fc-2eec33dd1357)

I have implemented this game using the Python programming language. In my implementation, there is a class called Game, which contains an attribute to store the game state, keeping track of which player has placed a piece in each position and which positions are still empty. The class also includes several methods for adding pieces and displaying the game board.

![image](https://github.com/user-attachments/assets/36deb78b-0c3f-4da5-ad5d-e334b05759ee)

After defining the Game class, I designed a playable version of the game where one participant is a human player. The human player is required to enter a number between 0 and 6 to select a column for placing their piece. On the other side, the opponent is a computer player, which randomly generates a number between 0 and 6 to make its move. The game then progresses accordingly.
In the next version, instead of having the computer select a move randomly, I plan to implement an AI model that makes decisions based on the current state of the game.
To achieve this, I intend to develop a model that will be trained using a reinforcement learning algorithm, allowing it to improve over time and eventually play the game professionally




