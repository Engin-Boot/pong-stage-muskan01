# Player-2-action

## Feature

This module defines different actions taken by player 2 in different scenarios
and the respective results which takes places.
The racket associated with player 2 is racket 2.
Also, this holds all the dimensions, speed and movement of racket 2

## Acceptance Criteria

### Scenario: Racket 2 miss the ball

  Given - ball is coming towards player 2

  When - racket 2 miss the ball

  Then - activate module Player-1-score
  
### Scenario: Racket 2 hit the ball

  Given - ball is coming towards player 2

  When - racket 2 hit the ball

  Then - activate module Ball-move
  
### Scenario: Player 2 exit the game

  Given - ball is coming towards player 2

  When - player 2 press E
  
  Then - activate module Exit-game
