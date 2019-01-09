# tennis_kata
Implementation in Python of a tennis scoreboard

Version of python used : 3.6.3
This small project will follow a Test Driven Development workflow.
The tests will be written using unittest.
Pylint will be used as a linter and as a way to verify basic coding rules recommended by the PEP8.


For those not fond of Roger, here are a short reminder of the rules of tennis as given in the kata's description :
The scoring system is rather simple:

1. Each player can have either of these points in one game 0 15 30 40

2. If you have 40 and you win the ball you win the game, however there are special rules.

3. If both have 40 the players are deuce. a. If the game is in deuce, the winner of a ball will have advantage and game ball. b. If the player with advantage wins the ball he wins the game c. If the player without advantage wins they are back at deuce.


To launch tests : python test.py
To run pylint : pylint tennis_kata
To try the tennis module game loop from a python command invite :
  > from tennis import game_loop
  > game_loop
