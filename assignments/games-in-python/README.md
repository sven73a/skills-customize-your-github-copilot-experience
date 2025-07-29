

# 🎮 Assignment: Games in Python - Hangman

## 🎯 Objective

Build a classic Hangman game in Python. Practice string manipulation, loops, conditionals, and random selection by creating a word-guessing game where players try to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Build the Hangman Game

#### Description
Create a Python program that lets a player guess letters to uncover a randomly selected word. The player should have a limited number of incorrect guesses before the game ends.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Display the word as underscores (e.g., _ _ _ _ _)
- Accept single-letter guesses from the user
- Reveal correctly guessed letters in their positions
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts are exhausted
- Show a win message if the player succeeds, or a lose message with the correct word if not

Example:
```plaintext
Word: _ _ _ _ _
Guess a letter: a
Word: _ a _ _ a
Incorrect guesses left: 4
...etc...
```

### 🛠️ (Optional) Add Extra Features

#### Description
Enhance your Hangman game with additional features to make it more fun or challenging.

#### Requirements
Completed program could:

- Allow the player to play multiple rounds without restarting the program
- Show the letters already guessed
- Add categories for word selection
- Display simple ASCII art for the hangman
