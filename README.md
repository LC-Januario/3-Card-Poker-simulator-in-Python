# 3-Card-Poker-simulator-in-Python
A simulator that plays a simplified version of poker with 2 players and prints out both players' hands, what "score" they had and who won

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Setup and Installation](#setup-and-installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [Contact](#contact)

## Overview

This 3-card poker game allows two players to draw hands and determines the winner based on standard poker hand rankings. The game is designed to be simple and easy to understand, making it a great introduction to Python programming and card games.

## Features

- **Deck Generation:** Creates a standard 52-card deck.
- **Shuffling:** Shuffles the deck randomly.
- **Drawing Cards:** Draws 3 cards for each player.
- **Hand Classification:** Classifies hands into poker combinations such as straight flush, three of a kind, straight, flush, pair, and high card.
- **Winner Determination:** Compares player hands and determines the winner.

## Setup and Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/3-card-poker-game.git
cd 3-card-poker-game
```

## Usage

Here's how the simulation runs:

1. **Generate and Shuffle Deck:**
    ```python
    deck_of_cards = generate_deck()
    shuffled_deck = shuffle_deck(deck_of_cards)
    ```

2. **Draw Cards for Players:**
    ```python
    player_1_hand = draw_cards(shuffled_deck)
    player_2_hand = draw_cards(shuffled_deck)
    ```

3. **Classify Hands:**
    ```python
    player_1_score = classify_hand(player_1_hand)
    player_2_score = classify_hand(player_2_hand)
    ```

4. **Determine the Winner:**
    ```python
    winner = determine_winner(player_1_score, player_2_score)
    print("Player 1's hand:", player_1_hand , ', ', player_1_combination)
    print("Player 2's hand:", player_2_hand , ', ', player_2_combination)
    print("The winner is:", winner)
    ```

## Contributing

We welcome contributions to enhance the game! If you have ideas for new features or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Open a pull request to merge your changes into the main branch.

## License

This repository is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions contact me at [luizcl2000@gmail.com].

---
