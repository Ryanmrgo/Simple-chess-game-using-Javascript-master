Chess Game


This project is a simple web-based Chess game built using HTML, CSS, and JavaScript. The goal of this project is to provide a basic implementation of a chessboard and chess mechanics, including piece movement and game rules. However, this is not the final version, and there are known issues and bugs that still need to be addressed.

Features

1. A fully interactive chessboard displayed in the browser.

2. Basic piece movement for all chess pieces (pawns, rooks, knights, bishops, queens, kings).

3. Highlighting valid moves for each piece when selected.

4. Basic turn switching between white and black players.

5. Simple game setup following standard chess rules (initial piece positioning).

Known Issues

While the game is functional to some extent, the following problems and bugs are present in this version:

1. Check and Checkmate Logic
The game does not properly detect when a king is in "check" or "checkmate." Players can move their kings into check positions, which is not allowed in chess.
Checkmate conditions are not correctly enforced, so the game may continue indefinitely even when one player is in checkmate.
2. Pawn Promotion
When a pawn reaches the opposite end of the board, it should be promoted to a queen (or another piece chosen by the player). However, pawn promotion has not been implemented yet.
3. Castling
Castling (both kingside and queenside) is not yet supported, even when the conditions for castling are met.
4. En Passant
The en passant rule, which allows pawns to capture other pawns that move two spaces on their first move, is not implemented.
5. Piece Movement Bugs
Some edge cases allow invalid moves, such as pieces being able to move through other pieces when they shouldn't (especially rooks, bishops, and queens).
Occasionally, pieces can "disappear" if moved too quickly or dragged off the board.
6. Turn Logic
Although turn switching between players is functional, there are occasional bugs where players can take multiple moves in a row, breaking the game flow.
7. Game Reset
A game reset button is included, but it does not always fully reset the game state, sometimes causing pieces to remain on the board or starting positions to be incorrect.

Future Improvements

Implement proper check, checkmate, and stalemate detection.
Add pawn promotion with a choice of pieces.
Include castling and en passant rules.
Improve movement validation to prevent illegal moves.
Fix game reset issues and allow players to restart the game smoothly.
Add better visual and sound feedback for player actions.
Implement a move history log to track game progress.

Contributing

Since this is not the final version, contributions and bug fixes are welcome. Feel free to submit a pull request or report issues via GitHub.
