# Voting Games
*Games where players can vote on what will happen next.*

##Idea
The basis of this idea is so called "Vote chess". It's something that has been done for 
as long as I can remember. 
I would like to expand that idea to any games we can imagine this concept of voting would
work for.

## MVP
###Players
1. Anybody must be able to create an account.
2. A logged in player can select any game displayed in the lobby.
3. If the game is played in teams, they must chose only one. From that point on they can only vote for what their team
  will do next.
4. When a player selects a game, they must be able to vote on the next move.

###Games
1. All available games are displayed in the lobby
  1. At the beginning just Tic-Tac-Toe and maybe Connect Four
2. Games will be collecting input for a set amount of time, and after that execute 
  the most voted for command
  1. Players can see in the lobby how long each turn takes for that specific game
3. Games must have an end condition. Upon ending, they have to notify the user about
  the outcome.

##Ideas for expansion of product
1. Player statistics are recorded in a database. Based on those statistics ELO is calculated.
  They now get grouped with players of similar ELO.
2. Players can comment on their moves and explain why they voted for their choice.
3. Chess available in the lobby.
4. Private game rooms (Let's say max of 5 people per team or something similar)
