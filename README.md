# tracker-practice

#### User stories:
1. The user should be able to go to app URL and immediately see a game board.
2. The users should be able to set their name.
3. The users should be able to play the game with at least one other player.
4. The user should see if they won or lost.

### Your MVP
1. An interactive board which renders on page load
2. A way for players to set their name
3. A way for players to mark an empty space on their turn
4. The game should end when there is a winner, or if the game is a tie
5. The game should report the end state

#### Your Stretch Goals
1. A button on `game over` to reset the game back to initial state<br>
2. A way to keep track of Player 1 vs. Player 2 wins<br>
- An option to play vs. a computer with AI
  - Level 1: Random empty space is good enough
  - Level 2: Computer chooses a space which immediately blocks a player win<br>
3. Add in the ability to store a game to play later.  This might use Firebase or local storage to do so.<br>
4. Add in the ability to play live with somebody remotely.  This will definitely need to use [Firebase](https://www.firebase.com/).
