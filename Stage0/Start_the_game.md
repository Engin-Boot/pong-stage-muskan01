# Start_the_game

## Feature

This module is responsible to start the game

## Acceptance Criteria

### Scenario: Begin the game

  Given - Game on the system

  When - Double click the game icon

  Then - Game screen will open

### Scenario: Selecting new game option from the game menu

  Given - Menu appears:
  Press S to start the new game
  Press esc to exit the game

  When - Player presses S

  Then - New game starts
  
  ### Scenario: Selecting exit game option from the game menu

  Given - Menu appears:
  Press S to start the new game
  Press esc to exit the game

  When - Player presses esc

  Then - game closes
  
  ### Scenario: Enter the names of player 1 and player 2

  Given - New game starts

  When - New window pop up appers asking the names of player 1 and 2

  Then - Enter the names
