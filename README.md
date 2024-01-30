# Blackjack Game

## Overview

This is a simple text-based Blackjack game implemented in Python. The game includes a deck of cards, a player's hand, a dealer's hand, and basic gameplay functionality.

## Classes

### Card

- Represents a playing card with a suit and rank.
- The `__str__` method is implemented to provide a human-readable representation of the card.

### Deck

- Represents a deck of cards.
- Initializes with a standard set of 52 cards (4 suits x 13 ranks).
- Provides methods to shuffle the deck and deal cards.

### Hand

- Represents a player's or dealer's hand.
- Keeps track of the cards in the hand and calculates the total value.
- Provides methods to add cards, calculate hand value, check for blackjack, and display the hand.

### Game

- Orchestrates the Blackjack game.
- Manages the flow of the game, including dealing cards, player and dealer turns, and determining the winner.

## How to Play

1. Run the script, and it will prompt you to enter the number of games you want to play.
2. For each game, you'll see the initial hands of the player and the dealer.
3. You can choose to "Hit" (receive another card) or "Stand" (keep the current hand).
4. The game continues until the player chooses to stand or busts.
5. The dealer then plays its turn according to a simple rule: hits until the total value is 17 or higher.
6. The winner is determined based on the final hand values.

## Features

- Basic gameplay with options to hit or stand.
- Automatic handling of Ace values to minimize busts.
- Recognition of Blackjack (an Ace and a 10-value card) for both the player and the dealer.
- Informative display of hands and game results.

## To Run

1. Ensure you have Python installed on your machine.
2. Save the script to a file (e.g., `blackjack.py`).
3. Open a terminal and navigate to the directory containing the script.
4. Run the script by executing the command: `python blackjack.py`.

## Notes

- This implementation is text-based and runs in the console/terminal.
- The game logic is kept simple for educational purposes and can be extended for more advanced features.

Enjoy playing Blackjack! 🃏
