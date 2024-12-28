# Hangman Game

The **Hangman Game** is a terminal-based word guessing game developed in Python. The player must guess a hidden word, one letter at a time, before they run out of attempts. The game offers a fun and interactive way to test your word-guessing skills.

## Features
- **Word Guessing**: The player must guess the correct word based on available hints.
- **Limited Attempts**: The player has a limited number of incorrect guesses before losing the game.
- **Dynamic Difficulty**: Words are randomly selected from a list, providing different challenges for each game.
- **Interactive User Interface**: The game provides real-time updates on the player's progress, including guesses and remaining attempts.

## Controls
- **Guessing Letters**: Enter one letter at a time.
- **Exit Game**: Type 'exit' to quit the game at any time.

## Requirements
To run the game, ensure you have Python installed. The game doesn't require any additional libraries, but you need Python to execute the script.

## Steps to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/farhat-1203/Hangman-Game.git
    cd Hangman-Game
    ```

2. **Run the Game**:
    Run the Python script to start the game:
    ```bash
    python3 hangman.py
    ```

3. **Play the Game**:
    - Guess the hidden word by typing one letter at a time.
    - If you guess incorrectly too many times, you lose.
    - If you guess the word correctly, you win!

## Project Structure
```
hangman-game/
├── hangman.py              # Main game script
├── words.json              # File containing a list of words for the game
├── README.md               # Project documentation
├── LICENSE                 # License file (MIT License)
