# Beginning the game

## Feature

This module is responsible to start the game

## Acceptance Criteria

### Scenario: Begin the game

  Given - Game on the system

  When - Double click the game icon

  Then - Game screen will open

### Scenario: Selecting new game option from the game menu

  Given - Menu appears:
  Press S to start the new game,
  Press E to exit the game

  When - Player presses S

  Then - New game starts
  
### Scenario: Selecting exit game option from the game menu

  Given - Menu appears:
  Press S to start the new game,
  Press E to exit the game

  When - Player presses E

  Then - Activate the module Exit-game.md
  
### Scenario: Enter the names of player 1 and player 2

  Given - New game starts

  When - New window pop up appears asking the names of player 1 and 2

  Then - Enter the names

### Scenario: Initial serve

  Given - Menu appears:
  Press B to serve the ball,
  Press E to exit the game

  When - player press B

  Then - activate the module Player-1-action
