# Number Guessing Game 🎲

This is a simple **Number Guessing Game** implemented in Python. The program generates a random number, and the user tries to guess it based on the feedback provided by the program.

## How It Works
1. The user enters an upper limit (must be a positive integer).
2. The program generates a random number between 0 and the upper limit.
3. The user guesses the number until they get it right.
4. After each guess, the program provides hints:
   - **"You were above the number!"** if the guess is too high.
   - **"You were below the number!"** if the guess is too low.
5. The program displays the number of guesses taken to get the correct answer.

## Requirements
- Python 3.x

## How to Run
1. Clone this repository or download the script.
2. Open a terminal or command prompt.
3. Run the script using:
   ```bash
   python number_guessing_game.py
   -----
## Example
Type a number: 10
Make a guess: 5
You were above the number!
Make a guess: 2
You were below the number!
Make a guess: 3
You got it!
You got it in 3 guesses

-----
## Features
Validates user input to ensure it's a positive integer.
Provides real-time feedback on guesses.
Keeps track of the number of attempts

-----
## Contributing
Feel free to contribute by:

Reporting bugs
Suggesting new features
Improving the code
To contribute, fork the repository, make your changes, and create a pull request.
