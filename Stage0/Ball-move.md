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

  Then - ball goes towards left which activates player-action

### Scenario: racket 1 hit the ball

  Given - Ball going towards racket 1

  When - racket 1 hit the ball

  Then - ball goes towards right which activates player-action
  
### Scenario: racket 2 hit the ball

  Given - Ball going towards racket 2

  When - racket 2 hit the ball

  Then - ball goes towards left which activates player-action
  
### Scenario: racket 1 miss the ball

  Given - Ball going towards racket 1

  When - racket 1 miss the ball
  And - ball goes beyond the racket 1
  And - ball disappears after 2 sec

  Then - ball appears from bottom goes towards left which activates player-action
  
### Scenario: racket 2 miss the ball

  Given - Ball going towards racket 2

  When - racket 2 miss the ball
  And - ball goes beyond the racket 2
  And - ball disappears after 2 sec

  Then - ball appears from bottom goes towards right which activates player-action
