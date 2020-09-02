# Player-score

## Feature

This module is responsible to update and save the score of player 1 & 2.
The variable which stores score of player 1 is score-one.
The variable which stores score of player 2 is score-two.
The terms "player","racket" ans "score" is used in the general sense and
can be anyone player 1 or player 2 with
racket 1 or racket 2 and score-one and score-two.
Also, this is a general module and will be instantiated for both players.

## Acceptance Criteria

### Scenario: Score update by plus 1

  Given - ball is coming towards racket

  When - racket miss the ball

  Then - update the score of opposite player by 1

### Scenario: Player is winner

  Given - score = score + 1

  When - score > or = 15

  Then - Display Player winner
  
### Scenario: Player is not winner

  Given - score = score + 1

  When - score < 15

  Then - activate the module Ball-move
  
### Scenario: After declaring Player winner

  Given - score > or = 15

  When - Display Player winner

  Then - activate the module Exit-game
