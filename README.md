# Simple Blackjack Game

This is a simple implementation of a Blackjack game in Python. The project consists of two main files: `main.py` and `art.py`. The game allows a single player to play Blackjack against an automated dealer.

## Files

### 1. `main.py`

This file contains the main logic and user interface for the Blackjack game. It orchestrates the gameplay, manages player input, and interacts with the `art.py` file for displaying ASCII art.

To run the game, execute main.py

### 2 . art.py
This file provides ASCII art representations for various game elements, such as cards and the game logo. The main.py file imports and utilizes these art functions to enhance the visual experience of the game.

Game Rules
This simple Blackjack game follows the basic rules of Blackjack:

The goal is to beat the dealer by having a hand value closer to 21 without going over.
Numbered cards are worth their face value, face cards (Jack, Queen, King) are each worth 10, and the Ace can be worth 1 or 11.
The player is initially dealt two cards and can choose to "hit" to receive additional cards or "stand" to keep their current hand.
The dealer follows a set of rules for drawing cards.
The game ends when either the player or the dealer goes over 21 or both players stand, and the winner is determined.
