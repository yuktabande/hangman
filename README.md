# Hangman Game in Python

## Overview

This repository contains a Python implementation of the classic Hangman game. The game randomly selects a word from a predefined list, and the player has to guess the word by suggesting letters within a limited number of attempts. The game provides feedback on whether the guessed letters are correct or not and displays the current state of the word being guessed.

## Repository Structure

- `hang.py`: The main script containing the game logic.
- `hangman_art.py`: A Python file containing ASCII art for the hangman stages.
- `hangman_words.py`: A Python file containing a list of words that the game can choose from.

## Features

- **Random Word Selection**: The game selects a word randomly from a list of words.
- **Limited Attempts**: The player has a limited number of attempts to guess the word.
- **Interactive Feedback**: The game provides feedback on whether the guessed letters are correct or not.
- **Visual Representation**: The game displays the current state of the word being guessed and the hangman's progress using ASCII art.

## Requirements

- Python 3.x

## How to Play

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yuktabande/hangman.git
   cd hangman
   ```

2. **Run the Game**:
   ```bash
   python hang.py
   ```

3. **Gameplay**:
   - The game will randomly select a word and display it as a series of underscores, representing each letter.
   - You will be prompted to guess a letter.
   - If the letter is in the word, it will be revealed in the correct position(s).
   - If the letter is not in the word, you will lose one attempt.
   - The game continues until you either guess the word correctly or run out of attempts.

## Code Structure

- `hang.py`: The main script containing the game logic.
- `hangman_art.py`: Contains ASCII art for the hangman stages.
- `hangman_words.py`: Contains a list of words that the game can choose from.

## Customization

- **Word List**: You can modify the `hangman_words.py` file to include your own list of words.
- **Number of Attempts**: You can change the number of allowed attempts by modifying the `max_attempts` variable in the `hang.py` script.

## Example

```python
Welcome to Hangman!
The word is: _ _ _ _ _ 
You have 6 attempts remaining.
Guess a letter: a
Good guess! The word is: _ a _ _ _ 
You have 6 attempts remaining.
Guess a letter: e
Sorry, the letter 'e' is not in the word.
The word is: _ a _ _ _ 
You have 5 attempts remaining.
Guess a letter: ...
```

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional features. Please ensure that your code follows the existing style and includes appropriate comments.

## Acknowledgments

- Inspired by the classic Hangman game.
- Thanks to the Python community for providing excellent resources and libraries.

## Contact

For any questions or suggestions, please open an issue on GitHub or contact the maintainer directly.

Enjoy playing Hangman! 🎮
