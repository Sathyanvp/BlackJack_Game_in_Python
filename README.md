**<h1 align="center">Blackjack Game</h1>**

**<h2 align="center">Overview</h2>**
  <p align="center">This is a simple console-based Blackjack game implemented in Python. The game allows a user to play against the computer (dealer) in a classic game of Blackjack. The goal is to have a hand value as close to 21 as possible without exceeding it, and to beat the dealer's hand.</p>

**<h2>Features</h2>**
 ->The game starts with a balance of $2000 for the player.
  
 ->Players can place bets, draw cards, and choose to either "stand" or "hit."
  
 ->The dealer (computer) draws cards until reaching at least 17.
  
 ->The game determines the winner based on the hands' values and displays the result.

 ->The player's balance is updated based on the outcome of each game.
  
**<h2>Requirements</h2>**

  ->Python 3.x
  
  ->No external libraries required
  
**<h2>How to Play</h2>**

<h3>Start the Game:</h3>

 ->When prompted, type 'y' to start a new game of Blackjack or 'n' to exit.
  
 ->Place a Bet: Enter a bet amount (must be less than or equal to the current balance).
  
<h3>Game Play:</h3>

 ->Two cards will be dealt to both the player and the dealer.
  
 ->The player will see their cards and the dealer's first card.
  
 ->The player can choose to "stand" (end their turn) or "hit" (draw another card).
  
 ->The dealer will draw cards until reaching at least 17.
  
<h3>Game End:</h3>

 ->The game will display the result: whether the player wins, loses, or if it's a draw.
  
 ->The player's balance will be updated accordingly.
  
  ->If the balance reaches zero, the game ends.
  
<h2>Code Description</h2>

<h3>Functions</h3>

"user_cards(user_card, sum_user)"

  ->Deals initial cards to the player or adds a card if the player chooses to hit.
  
  ->Prints the player's cards.
  
"computer_cards(computer_card, sum_computer)"

  ->Deals initial cards to the dealer or adds a card if needed.
  
  ->Prints the dealer's cards (except the last card) and the total value.
  
"total(card)"

  ->Calculates and returns the total value of a given hand.
  
"find_winner(sum_computer, sum_user)"

 ->Determines and returns the result of the game based on the hand values of the player and dealer.
  
**<h2>Main Game Loop</h2>**

**<h3>Initialization:</h3>**

  ->Sets up initial values for sums, cards, and balance.
  
**<h3>Game Execution:</h3>**

  ->Prompts the user to play or exit.
  
  ->Handles betting and updates balance.
  
  ->Manages game flow, including dealing cards and checking for win/loss conditions.
  
  ->Updates the balance based on the outcome and checks for a zero balance condition.
  

**<h2>Notes</h2>**
  ->Ensure that Python 3 is installed to run this script.
  
  ->The code uses basic list operations and random number generation for card dealing.
  
  ->The game does not handle input validation extensively, so ensure that inputs are correct to avoid errors
