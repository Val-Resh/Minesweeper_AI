# Minesweeper AI Player

An 8x8 Minewsweeper board that you can play yourself or with the assistance of the AI that can make the moves for you.

## To Run:

* Ensure Python is installed: https://www.python.org/downloads/
* Run from command line: ```pip3 install -r requirements.txt``` to install necessary package.
* ```python runner.py``` to run the game.

## Approach:

The AI is built on a knowledge-based approach. The rules of the game are programmed into the AI.
Based on logical inferences the AI is able to perform decisions, otherwise it will act randomly if no logical option is available.
An example of a logical inference is: <p>

```
| A | B | C |
-------------
| D | E | F |
-------------
| 0 | G | H |
```
We can conclude that D, E, G are not mines because of the rules of the game. 
This is a simple example and the AI uses other inferences to play the game, including the one represented above.

