

# Hangman Game 

Welcome to the **Hangman Game**! This is a simple command-line game where you have to guess the name of an animal letter by letter before you run out of attempts.

##  Game Description

The Hangman Game is a classic word-guessing game. In this version, you need to guess the names of various animals within a limited number of attempts. Each incorrect guess brings you closer to running out of chances, so choose wisely!

##  List of Animals

The hidden words in the game are selected from the following list of animals:

- Tiger
- Lion
- Giraffe
- Zebra
- Dolphin
- Shark
- Elephant
- Rhino
- Cat
- Cheetah
- Dog
- Sheep
- Goat
- Fish
- Dragon
- Dinosaur
- Horse
- Cow
- Wolf
- Bear
- Raccoon
- Turtle
- Leopard
- Gorilla
- Donkey
- Camel
- Octopus

##  How to Play

1. **Start the Game**: Run the script to start a new game.
2. **Guess the Letters**: You'll see underscores representing the letters of the hidden animal's name. Type a letter and press Enter to make a guess.
3. **Correct Guesses**: If the letter is in the animal's name, it will be revealed in the correct positions.
4. **Incorrect Guesses**: If the letter is not in the animal's name, you will lose one attempt. You have a limited number of attempts to guess the word correctly.
5. **Win or Lose**: The game ends when you either guess the word correctly or run out of attempts.

## Installation

To play the game, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/hangman-game.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd hangman-game
   ```

3. **Run the Game**:
   ```bash
   python hangman.py
   ```
**Example**
```
Welcome to Hangman! 
Guess the animal: _ _ _ _ _

Enter a letter: e
Correct! The word is now: _ _ _ e _

Enter a letter: a
Incorrect! You have 5 attempts remaining.

Enter a letter: t
Correct! The word is now: t _ _ e _

Enter a letter: r
Correct! The word is now: t _ _ e r

Enter a letter: g
Correct! The word is now: t i g e r

Congratulations! You've guessed the word: tiger

```
## Requirements

- Python 3.x
  
**Error Handling**
Invalid Input: The game will handle non-alphabetic characters by notifying the player and asking for a valid letter.
Repeated Guesses: If the player guesses the same letter more than once, the game will alert them that the letter has already been guessed.
Case Sensitivity: The game will treat uppercase and lowercase letters as the same, allowing the player to input either.

