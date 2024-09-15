This is a simple number guessing game implemented in C++. The game involves a Guesser, three Players, and an Umpire. The objective is for the Players to guess the same number as the Guesser. The Umpire manages the guesses and determines the winner.

Game Overview

The game operates with four key entities:

Guesser: This entity guesses a random number X.
Players: There are three players (P1, P2, and P3). Each player guesses a number.
Umpire: The Umpire collects the guesses from both the Guesser and the Players. The Umpire then determines if any of the Players guessed the same number as the Guesser.

Gameplay Flow:

The Guesser picks a number.
The Players each pick their guesses.
The Umpire checks if any Player's guess matches the Guesser's number.
The result is printed, showing if there is a winner or if the guesses were incorrect.
The game ends.

Classes

The game is built with three main classes:

Guesser: Responsible for picking the number X that the players will try to guess.
Player: Represents the individual players (P1, P2, and P3) who each make a guess.
Umpire: Collects the guesses from the Guesser and Players, compares them, and declares the result.
Features
Random number generation for the Guesser.
Input-based or random guesses for Players.
Umpire logic to compare guesses and declare a winner.
Simple command-line interface.

How to Play

The Guesser will generate a random number or prompt the user to input a number.
Each of the three Players will make a guess.
The Umpire collects all the guesses and compares them with the Guesser's number.
The game prints whether any Player(s) guessed correctly or if everyone was incorrect.
The game ends with an option to restart.
