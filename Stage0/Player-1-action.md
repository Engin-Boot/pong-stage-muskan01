# Player-1-action

## Feature

This module defines different actions taken by player 1 in different scenarios
and the respective results which takes places.
The racket associated with player 1 is racket 1.

## Acceptance Criteria

### Scenario: Racket 1 miss the ball

  Given - ball is coming towards player 1

  When - racket 1 miss the ball

  Then - activate module Player-2-score
  
### Scenario: Racket 1 hit the ball

  Given - ball is coming towards player 1

  When - racket 1 hit the ball

  Then - activate module Player-2-action
  
### Scenario: Player 1 exit the game

  Given - ball is coming towards player 1

  When - player 1 press E
  
  Then - activate module Exit-game
