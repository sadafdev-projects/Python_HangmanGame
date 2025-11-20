# 🎮 Hangman Game

## 📘 Overview
This project focuses on creating a simple **text-based Hangman game** where the player guesses a hidden word one letter at a time. It showcases **Python fundamentals** such as loops, conditionals, string manipulation, and list handling.

## 🎯 Objective
To build a **fun and interactive console-based Hangman game** that allows the player to guess letters and complete the hidden word before running out of attempts.

## 🚀 Features
- Randomly selects a word from a predefined list of 5 words
- Allows the player up to **6 incorrect guesses**
- Displays progress with **underscores for unguessed letters**
- Provides feedback on **correct and incorrect guesses**
- Ends with a **win/lose message** based on performance

## 🧠 Tech Stack
- **Python**
- `random` module for word selection
- `while` loops and `if-else` statements
- Strings and lists for tracking guesses
- Console input/output

## ⚙️ How It Works
1. The program selects a **random word** from a predefined list.
2. The player guesses **one letter at a time**.
3. Correct guesses **reveal the letter** in the word; incorrect guesses **reduce remaining chances**.
4. The game continues until the player either **guesses the full word** or **runs out of attempts**.

## 💡 Example Gameplay
Welcome to Hangman! Guess the word: _ _ _ _ _

Enter a letter: a
Good guess!
_ a _ _ _

Enter a letter: e
Wrong guess! 5 attempts left.

Enter a letter: r
Good guess!

You won! The word was: earth
