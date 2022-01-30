# Random walk game at Empire State Building

We work with the concept of Random walk to simulate our game which looks at the odds of reaching Step 60 in multiple throws of a dice(100 in our case). 
The idea is to roll a dice and based on some rules, take the number of steps either forward or backward. At the end of the 100th Dice roll, we record the no. of steps we have covered. We then simulate this random walk game multiple number of times to finally check how many times we achieve Step 60 and the odds of it happening(the probability).
## The Rules of the game:
1. Before taking a step we roll the dice.
2. If Dice roll turns out to be 1 or 2 we take a step back.
3. If Dice roll turns out to be 3,4 or 5 we take a step up.
4. If Dice roll turns out to be 6, Bingo! Free hit chance comes up and you roll the dice again and take steps up equal to the next dice roll.
5. You start at ground level step 0.
6. As in reality the number of steps you are on can never be negative.
7. Oh and if you are clumsy, you have a fractional chance of falling down(0.001%), in which case you would start from zero again.

## Goal of the game
Simulate this random walk game multiple number of times to finally check the probability of reaching Step 60.
