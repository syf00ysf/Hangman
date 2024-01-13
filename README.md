
 basic c++ 
# Hangman Game

This is a simple implementation of the classic Hangman game in C++. 

## How to Play

1. The game chooses a secret word at random.
2. The player is shown a series of dashes representing the secret word.
3. The player guesses a letter at a time.
4. If the guessed letter is in the word, the dashes are replaced with the guessed letter in the correct positions.
5. If the guessed letter is not in the word, the player loses a try.
6. The game continues until the player guesses the word correctly or runs out of tries.

## Running the Game

To compile the game, use a C++ compiler like g++. Run the following command in your terminal:

```bash
g++ main.cpp -o hangman
