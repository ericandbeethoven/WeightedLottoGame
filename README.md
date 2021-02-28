# WeightedLottoGame
Hybrid Squares, Tournament Bracket Battle Weighted Lottery Game 

## Game Overview
Based on the NCAA Braketball Tournament Bracket selection and Football Squares contests, this contest assigns 64 college basketball teams to entrants via a weighted lottery. There are payoffs at four payoffs throughout the tournament. These are based on National Championship winner and farthest to advance seed classifications. The entrant therefore has a chance to win a payoff with a lower seeded team too.

## Inputs
bb_seeds.xlsx - place in same directory, contains Seed (eg 1-64), Team Name & Entrant Assignment (Empty at beginning). Team Seeds and Names can be found online.
lotto_balls.xlsx - place in same directory, contains a 64x64 grid of Entrants (vertical) and Seed (horizontal in ascending order, eg 1,2,...,64) with weights (int)

## Program Flow


## Outputs
lotto_winners.xlsx - placed in same directory, contains Seed (64 - 1), Team Name & Entrant Assignment

   Seed                Team      Entrant
0    64  North Dakota State  gcvik 2_139
1    63        Gardner-Webb     cc 8_144
2    62   Abilene Christian  PPVIP 3_152
3    61             Bradley  gcvik 1_173
4    60             Colgate     LD 4_154
5    59             Montana  gcvik 2_173
6    58   Northern Kentucky  gcvik 1_190
7    57       Georgia State  gcvik 3_150





## Dependencies
import numpy as np
import pandas as pd
