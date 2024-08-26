# Random-number-guess
Overview
This is a simple C++ console-based game where the user is asked to guess a random number between 1 and 100. The program generates a random number at the start and provides feedback to guide the user towards guessing the correct number.

How It Works
Random Number Generation:

The program uses the std::rand() function to generate a random number between 1 and 100.
The random number generator is seeded using std::time(nullptr) to ensure a different number is generated each time the program runs.
User Input:

The user is prompted to guess the number.
After each guess, the program provides feedback:
If the guess is too low, it informs the user and prompts for another guess.
If the guess is too high, it similarly prompts for another guess.
If the guess is correct, the program congratulates the user and reveals the number.
Game Loop:

The game continues in a loop until the user guesses the correct number.
