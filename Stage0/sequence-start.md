# Interaction Sequences

## Startup Sequence

The module **start-the-game** opens the game screen,
display the game menu, starts the new game,
takes the names of player 1 and player 2 and then initiates the first serve.
Then control goes to the module **Ball-move** which is responsible
to throw the ball towards Player 1 after the initial serve.

## Movement Initiation

After **Player-1-action** module takes the action which can be **hit the ball**,
**miss the ball** or **exit the game**,
the respective result takes playes which can give control to any one of the modules **Ball-move**,
**player-2-score** or **Exit-game**.
**Ball-move module** is responsible to hold every movement of the ball.
**Player-2-score** keeps the score of player 2.
**Exit-game module** is responsible to close the game screen.
After going the controls to **Player-2-action** and the result takes place can give control
to one of modules which are **Player-1-score**, **Ball-move** or **Exit game**.
**Player-1-score** keeps the score of player 1.

## One score

If the control goes to **player-1-action** and racket 1 miss the ball,
control goes to **player-2-score** module which is responsible to keep the score of player 2.
If the control goes to **player-2-action** and racket 2 miss the ball,
control goes to **player-1-score** module which is responsible to keep the score of player 1.
