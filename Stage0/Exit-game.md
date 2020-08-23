# Exit-game

## Feature

This module is responsible to close the game.
The variable score-one stores the score of player 1.
The variable score-two stores the score of player 2.

## Acceptance Criteria

### Scenario: Player 1 or player 2 press E

  Given - Game screen is open

  When - Player 1 or player 2 press E

  Then - close the game

### Scenario: Player 1 wins

  Given - score-one > or = 15

  When - declare player 1 winner

  Then - close the game
  
### Scenario: Player 2 wins

  Given - score-two > or = 15

  When - declare player 2 winner

  Then - close the game
