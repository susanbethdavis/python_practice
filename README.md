Welcome to my collection of Python coding problems! This repository contains various interactive games that I've developed to sharpen my Python skills. Each project offers a unique challenge, perfect for practice and learning.

### Cows and Bulls:
A number-guessing game where the goal is to correctly guess a randomly generated 4-digit number. Here's how the game works:
- The computer randomly generates a 4-digit number in the range of 0000 to 9999.
- The player is prompted to guess the target number.
- For each digit the player guesses correctly (matching both digit and position), they receive a bull.
- For each correct digit in the wrong position, they receive a cow.
- A digit is counted as a cow only once, even if it appears multiple times in the target number.
- The game continues until the player guesses the correct number.
- The game tracks the number of guesses it takes for the player to guess the target number.

### Birthday Plots:
A program that assigns a random number of birthdays to each month, with the total number of birthdays for each month determined by a maximum value set by the user.
- The program initializes the number of birthdays for each month to zero.
- The user is prompted to enter the maximum number of birthdays that any single month can have.
- The program then assigns a random number of birthdays to each month, with values ranging from 0 to the user-defined maximum.
- The results are plotted using the `pyplot` module from Matplotlib, providing a visual representation of the distribution of birthdays across the months.

### Morse Code Translator:
An interactive program that translates a user-inputted sentence into Morse code.
- The user is prompted to enter a sentence containing only alphabetic characters, numbers, and spaces.
- The program checks for valid input and ensures that only valid characters are entered.
- Each letter, number, and space is then converted to its equivalent Morse code using a predefined dictionary.
- The Morse code for the entire sentence is printed out, with each Morse code character separated by a space.
- The user can choose to translate another sentence or exit the program.

