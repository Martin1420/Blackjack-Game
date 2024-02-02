
# Blackjack Game

## Description

This Python application is a simple command-line version of the classic Blackjack card game. Players compete against a dealer in an attempt to get a hand value as close to 21 as possible without going over. The game supports basic Blackjack actions such as hit and stand, and automatically handles the logic for the dealer's moves, player wins, busts, and ties.

## Features

- **Deck Creation**: Automatically generates a standard deck of 52 cards.
- **Shuffling**: Randomly shuffles the deck before dealing.
- **Dealing**: Deals two cards to both the player and the dealer at the start of the game.
- **Hit**: Players can choose to "hit" to receive an additional card.
- **Stand**: Players can choose to "stand" to end their turn.
- **Ace Handling**: Aces can count as either 1 or 11, adjusting automatically based on the hand's total value.
- **End Game Scenarios**: Includes logic to handle busts, wins, and ties.
- **Replayability**: Allows players to play multiple rounds without restarting the application.

## Installation

No external libraries are required to run this game, as it only uses Python's built-in `random` module. Ensure you have Python 3.x installed on your system.

1. Clone or download this repository to your local machine.
2. Navigate to the directory containing the game files.
3. Run the script using Python:

    ```bash
    python blackjack.py
    ```

## How to Play

1. Run the script to start the game. The game will automatically deal two cards to both the player and the dealer, with one of the dealer's cards remaining hidden.
2. Decide whether to "hit" (get another card) or "stand" (keep your current hand). Type 'h' for hit or 's' for stand when prompted.
3. The dealer's turn will automatically proceed after the player stands. The dealer hits until their hand value is at least 17.
4. The game will then determine the outcome (win, lose, tie) based on the final hand values.
5. You will be prompted to play another hand. Type 'y' to continue playing or 'n' to exit.

## Game Rules

- The goal is to get as close to 21 as possible without going over.
- All face cards (Jack, Queen, King) are worth 10. Aces are worth 1 or 11.
- The dealer must hit until their hand is at least 17.
- If you go over 21, you bust and lose the round.
- If you have a higher hand value than the dealer without busting, you win.

## Contribution

Feel free to fork this project and contribute by adding new features or fixing bugs. Please ensure you follow best practices and keep the code clean and well-documented.

## License

This project is open-source and available under the MIT License.

