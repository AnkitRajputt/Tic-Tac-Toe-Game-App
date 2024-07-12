# Tic-Tac-Toe-Game-App

The Tic Tac Toe Game App is a simple, classic game designed for Android devices. The app provides an engaging user interface where two players, X and O, can take turns tapping on a 3x3 grid to place their respective marks. The game includes the following features:

1) User Interface:

    The main screen contains a 3x3 grid of ImageViews, each representing a cell in the Tic Tac Toe board.
    A TextView displays the current player's turn, indicating whether it's X's or O's turn to play.
 
 2) Gameplay Logic:

    Players take turns tapping on the cells. An ImageView updates with the corresponding player's symbol (X or O) upon a tap.
    The app checks for winning conditions after each move by evaluating predefined winning positions.
    If a player wins, a winning message is displayed, and the game is halted.
    If all cells are filled without a winner, the game declares a draw.

3) Game Reset:

    The game can be reset at any time, clearing the board and starting a new game.
    The reset function ensures all ImageViews are cleared and the game state is reinitialized.

4) Animations:

    Smooth animations enhance the user experience by animating the appearance of the X and O symbols.

5) Status Updates:

    Real-time status updates keep players informed of whose turn it is and who has won.

   
