
---

# Word Guessing Game

Welcome to the Word Guessing Game! This is a simple console-based game where you guess letters to find out the hidden word. The game uses a list of programming languages as the source of words to guess.

## Features

- **Random Word Selection**: A word is randomly selected from a predefined list of programming languages.
- **Letter Guessing**: You guess one letter at a time.
- **Attempts**: You have 6 attempts to guess the word.
- **Feedback**: The game provides feedback on correct and incorrect guesses.
- **Hints**: Provides a hint if you're running low on attempts.

## Requirements

- **Python**: This game requires Python 3.x to run.

## Getting Started

### Running the Game

1. **Clone or Download the Repository**

   If you haven't already, clone or download this repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/word-guessing-game.git
   cd word-guessing-game
   ```

2. **Run the Game**

   Ensure you have Python 3.x installed. Open a terminal or command prompt, navigate to the directory containing the game script, and run:

   ```bash
   python word_guessing_game.py
   ```

   If you're using a Jupyter notebook, you can copy and paste the code into a new cell and run it.

### How to Play

1. **Guess a Letter**

   - When prompted, type a single letter and press Enter.

2. **Receive Feedback**

   - If the letter is in the word, it will be revealed in the word with underscores replaced by the guessed letter.
   - If the letter is not in the word, you'll lose an attempt.

3. **Win or Lose**

   - You win if you guess all the letters of the word before running out of attempts.
   - You lose if you use up all your attempts before guessing the word.

4. **Hints**

   - When you have less than 3 attempts remaining, a hint will be provided indicating that the word is the name of a programming language.

## Example

```
Welcome to the Word Guessing Game!
You have 6 attempts to guess the word.
_ _ _ _ _ _

Guess a letter: p
Correct guess!
p _ _ _ _ _

Guess a letter: r
Wrong guess. You have 5 attempts remaining.

...
```

## Contributing

Feel free to fork the repository and contribute by submitting issues or pull requests. Your contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact peelachandrika@gmail.com

---

