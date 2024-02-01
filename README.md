# CS213Chess

## General Chess Reminders/Clarification

- There is no need to implement an auto-draw/flag/stalement functionality
- The chess move "en passe" is performed by a pawn, taking another pawn that is directly horizontal from it after the enemy pawn has taken two steps forward
- The checkered areas represented by "##" symbolize the dark squares
- Clarification on Piece Names
  - b: black pieces
  - w: white pieces
  - p: pawns
  - B: bishops
  - N: knights
  - R: rooks
  - K: kings
  - Q: queens

---

## How to Play

Running the main Java program, Chess.java, through the terminal displays a depiction of a chess board. The program then prompts, through the terminal, for a valid chess move using chess notation from White. A sample move formatted through chess notation is as follows:

> ```White's move:```  e2 e4

The above chess move pushes the white pawn originally located on square e2 to square e4. From here, the program updates the board from the first player's move and prompts the other player, Black, for a move. Any player can resign from the game, which ends the game immediately, resulting in the other player's win.
