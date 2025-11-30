🎯 Hangman Game (Python)

A simple command-line Hangman game written in Python.
The program randomly selects a word from a predefined list, and the player must guess the word one letter at a time before running out of attempts.

📌 Features

Random word selection

Tracks guessed letters

Displays word progress with underscores

Validates user input

Six allowed incorrect attempts

Win/lose game ending messages

🧠 How It Works

The game chooses a random word from the list:
["python", "computer", "program", "science", "hangman"]

The player guesses letters one at a time.

Correct guesses reveal the letter in the word.
Incorrect guesses reduce the number of remaining attempts.

The game ends when:

The player guesses all letters (🎉 win), or

The player runs out of attempts (💀 loss)

▶ How to Run the Game

Make sure Python is installed
Version 3.6+ recommended.

Save the script as:
hangman.py

Open a terminal or command prompt and run:
