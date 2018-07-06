# Rock, Paper, Scissors

A simple rock, paper, scissors game that you can play against a computer or
against another player.

There are 4 computer players in the game:

* Player, who always plays rock
* RandomPlayer, who plays a random move each round
* ReflectPlayer, who plays the move the opponent played on the previous round
* CyclePlayer, who cycles through rock, paper, scissors moves at each round

Each match consists of 7 rounds. The player who wins the greatest amount of
rounds is the final winner of the match.

## Rules

Rock break scissors, scissors cut paper, paper envelops rock.

## Prerequisites

You need Python 3 installed on your computer. If you don't have it, you can
download it [here](https://www.python.org/downloads/).

## How to play

Open up your terminal or your command line, and clone this repository:
`git clone https://github.com/aberdean/rock-paper-scissors.git`
Then, navigate into the folder:
`cd rock-paper-scissors`
From there, type
`python rock_paper_scissors.py`
to start the game.

The game by default plays a match between a RandomPlayer and a HumanPlayer.
If you would like to change players, please modify line 249 in the
rock_paper_scissors.py file substituting RandomPlayer and/or HumanPlayer with
one of the following:

* Player
* RandomPlayer
* ReflectPlayer
* CyclePlayer
* HumanPlayer

The game can play matches between a computer and a human player, between two
human players, or between two computer players.

Have fun!
