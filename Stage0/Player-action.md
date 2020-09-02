# Player-action

## Feature

This module defines different actions
taken by player 1 and player 2 in different scenarios
and the respective results which takes places.
The terms "player" and "racket" is used in the general sense
and can be anyone player 1 or player 2
with racket 1 or racket 2.
The racket associated with player 1 is racket 1.
The racket associated with player 2 is racket 2.
This holds all the movement of racket 1 and racket 2.
Also, this is a general module and will be instantiated for both players.

## Acceptance Criteria

### Scenario: Racket miss the ball

  Given - ball is coming towards player

  When - racket miss the ball

  Then - activate module Player-score
  
### Scenario: Racket hit the ball

  Given - ball is coming towards player

  When - racket hit the ball

  Then - activate module Ball-move
  
### Scenario: Player exit the game

  Given - ball is coming towards player

  When - player press E
  
  Then - activate module Exit-game
