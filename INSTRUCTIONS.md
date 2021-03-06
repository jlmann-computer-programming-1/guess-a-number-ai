# Guess-A-Number Project

Create a version of Guess-A-Number where the player thinks of a number and the computer guesses. Here's how game play should work:

The first line of output should be

"Please think of a number from 1 to 100 and I will try to guess it."

Then have a statement such as input("Press Enter to continue...")

The computer should guess numbers using the optimal guessing strategy of always picking the middle number from the group. After each "guess", the computer will ask "Is the number [guess]?" The player should respond with "yes", "higher", or "lower". (It is fine if you accept "y", "h", and "l" for input as well.) The process should repeat in a while loop until the computer finally guesses the number that the player is thinking of.

### Code hints:

When the game starts, create two variables low = 1 and high = 100. The guess will be the average of these values. Use // to divide so that the result is rounded to a whole number. If higher is the response, then the computer should adjust its low variable to one more than the guess. If lower is the response the computer should adjust it's high variable to one less than the guess.

This is an individual assessment, but you may discuss code with classmates.


## Rubric:

Before game loop...

Begining output (1 point)
Enter to start (1 point)
Set low and high variables (1 point)

In game loop...

Computer displays a guess 
Guess is rounded average of low and high
Player is prompted to enter "yes", "lower", or "higher"
Computer correctly adjust range of guesses based on player input
The number of computer guesses is tracked.
If player input is invalid, the computer should say something like "I don't understand." and the player should be prompted for feedback again.
Game ends when guess is correct

After game loop...
Output prints a sentence such as "That was fun. I guessed your number in [n] tries."


### Code quality...

Indentation is neat. White space between blocks of code makes code readable.
Variable names are descriptive and follow Python naming conventions.
Organization of code makes game logic clear.
