# Player-2-score

## Feature

This module is responsible to update and save the score of player 2.
The variable which stores score of player 2 is score-two.

## Acceptance Criteria

### Scenario: Score update by plus 1

  Given - ball is coming towards racket 1

  When - racket 1 miss the ball

  Then - score-two = score-two + 1

### Scenario: Player 2 is winner

  Given - score-two = score-two + 1

  When - score-two > or = 15

  Then - Display Player 2 winner
  
### Scenario: Player 2 is not winner

  Given - score-two = score-two + 1

  When - score-two < 15

  Then - activate the module Ball-move
  
### Scenario: After declaring Player 2 winner

  Given - score-two > or = 15

  When - Display Player 2 winner

  Then - activate the module Exit-game
