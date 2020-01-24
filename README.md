# Game-Project
Building a Game Project: Black_Jack
## Rules
1. start with $1000, win if you reach $3000, game over if you reach $0. Have option to restart.
2. Player can stand or hit to a maximum of 5 cards.
3. Set a hard rule if player reaches 17 or above they win the round, draw if they get 16 and lose
if lower than 16 or above 21 (Bust).
4. Betting $10 and winning gives you $20, if you lose you lose your bet money, if you draw you
get your money back.
5. Need to keep track of wins, losses, draws and busts.
6. At the end of Every turn show the player's account balance, number of wins etc, so will need
a status window.
7. Ace is 1 or 11.
## Hints (This is just a suggestion)
Classes to Create:
1. #Deck, with methods:
a. Take a card from the deck
b. Reset deck
2. #Player, with methods:
a. Change account balance,
b. Update counts for wins, losses and busts
c. Print status window (account balance and number of wins etc)
d. Update Hand
e. Clear hand
f. Show hand
g. Bet amount
3. #Game Status:
a. Check game status (has the game ended? When player has no money or over
$3000)
b. Update Round Status (did player win etc)
## Methods to create for flow of game:
1. Check player input (yes or no etc)
2. Check Bet amount
3. Hit or Stand
4. Check for Bust
5. Check if Hand is ok (ie has it bust, reach 5 cards?)
6. Update wins and losses
7. A round (as there can be many rounds)
