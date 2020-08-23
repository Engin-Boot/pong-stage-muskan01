# Ball-move

## Feature

This module holds the information about the ball
that includes dimension, speed and movement.
Racket 1 is associated with player 1.
Racket 2 is associated with player 2.

## Acceptance Criteria

### Scenario: Initial serve

  Given - new game starts

  When - press B

  Then - ball goes towards left which activates player-1-action

### Scenario: racket 1 hit the ball

  Given - Ball going towards racket 1

  When - racket 1 hit the ball

  Then - ball goes towards right which activates player-2-action
  
### Scenario: racket 2 hit the ball

  Given - Ball going towards racket 2

  When - racket 2 hit the ball

  Then - ball goes towards left which activates player-1-action
