# Treasure-Hunt-Navigating-a-Maze

The game starts with 45 seconds timer, 3 lives and score 0.

A player starts the game in drill position. Toggling the tool pressing 't' changes it to a hammer.
In the hammer state, a player can collect golds hidden inside the bricks by breaking the bricks but a bomb effect appears and nearby walls and bricks with gold are destroyed if it encouters an enemy and loses a life.
In the drill state, it can encounter an enemy without losing any life. It can also shoot bullets to kill enemies.

Controls:
Pressing up,down, left, right arrow keys moves the player
Pressing W,S,A,D keys shoots bullet in different directions

Score:
5 points are rewarded for collecting gold
10 points are rewarded for killing enemies
10 seconds time are rewarded for each score 30

Game logic:
The game is over when the timer is up or all 3 lives are lost or when there are no more gold left. 
The player wins the game if it can collect all 7 gold.
