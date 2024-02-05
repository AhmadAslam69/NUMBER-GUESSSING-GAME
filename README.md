Number Guessing Game
This C++ program implements a simple number guessing game where the user has to guess a randomly generated number between 1 and 100. The game provides feedback to the user after each guess, indicating whether the guess was too low, too high, or correct.

Features
Random Number Generation: The program generates a random number between 1 and 100 using the rand() function and srand() with the current time as a seed.

User Input and Feedback: The user is prompted to input their guess. The program then provides feedback on whether the guess was too low, too high, or correct.

Game Loop: The game continues until the user correctly guesses the random number.

Visual Elements: The console interface is enhanced with colored text using the system("color C0") command and decorative borders made with setw() and setfill().

Gameplay
The program will generate a random number between 1 and 100.
The user is prompted to input their guess.
The program provides feedback on whether the guess was too low, too high, or correct.
The game continues until the user correctly guesses the random number.
Upon correct guessing, the program congratulates the user and reveals the randomly generated number.
Note
The use of system("color C0") is for visual enhancement and may not be supported on all systems.
Acknowledgments
This program is a simple demonstration of a number guessing game, and contributions or improvements are welcome. Feel free to customize or expand the code to add additional features or improve user interaction.
