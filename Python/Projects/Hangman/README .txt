Hangman Game (Python)

This is a small Python project where I built a classic Hangman game that runs in the terminal. The goal of this project is to practice Python basics like loops, conditionals, working with files, and simple game logic. The game picks a random word from a text file and the player has to guess it before running out of attempts.


Files Included:

HangmanGame.py – the main Python script that runs the game
words.txt – a list of 50+ words used by the game
screenshots – a few images showing the game running
README.md – this file


To run the game:

- Make sure Python 3 is installed
- Download or clone this project
- Open a terminal in the project folder
- Run the game using: python hangman.py


How the game works:

- The program randomly chooses a word from words.txt.
- You guess one letter at a time.
- The game shows:
	- Correct letters
	- Wrong guesses
	- Remaining attempts
- You win if you guess the full word.
- You lose if you run out of attempts.


Features of this game:

- Random word selection from a file
- Tracks guessed letters
- Input validation (only accepts single letters)
- Clear win/lose messages
- Easy to customize the word list