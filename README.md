# Hangman Game

This is a simple implementation of the classic **Hangman** game written in Python. The game allows players to guess a word by suggesting letters within a certain number of attempts.

- The game selects a word randomly.
- The player has a limited number of lives to guess the word.
- After each incorrect guess, the number of lives decreases.
- The game displays the word with blanks for the unguessed letters.

## Files
- **`hangman.py`**: Main file that contains the core logic of the Hangman game.
- **`hangman_guessing_words.py`**: File containing a list of possible words to be used in the game.
- **`hangman_lives.py`**: Manages the lives of the player, tracking how many guesses the player has left.

## How to Play
1. Clone this repository or download the files.
2. Run the `hangman.py` file.
3. The game will display blanks for the letters in the chosen word.
4. Guess the letters one by one. You can only guess once per round.
5. The game ends when you either guess the word correctly or run out of lives.

