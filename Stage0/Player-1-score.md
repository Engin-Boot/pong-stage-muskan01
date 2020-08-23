# Player-1-score

## Feature

This module is responsible to update and save the score of player 1.
The variable which stores score of player 1 is score-one.

## Acceptance Criteria

### Scenario: Score update by plus 1

  Given - ball is coming towards racket 2

  When - racket 2 miss the ball

  Then - score-one = score-one + 1

### Scenario: Player 1 is winner

  Given - score-one = score-one + 1

  When - score-one > or = 15

  Then - Display Player 1 winner
  
### Scenario: Player 1 is not winner

  Given - score-one = score-one + 1

  When - score-one < 15

  Then - activate the module Player-2-action
  
### Scenario: After declaring Player 1 winner

  Given - score-one > or = 15

  When - Display Player 1 winner

  Then - activate the module Exit-game
