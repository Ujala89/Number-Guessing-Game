You are tasked with implementing a simple number guessing game in C++
involving a Guesser, three Players, and an Umpire. The game operates as follows:
Guesser: This entity will guess a number x->4
Players: Each of the three players will guess a number 3 players p1-2 p2->4 p3->2
Umpire: This entity will collect the guesses from the guesser and the players and 
determine which players, if any, have guessed the same number as the guesser

p1->2 p2->4 p3->2            x->4

   classes ->guesser
             umpire
             player


             main functions -> 1. Create a Umpire
                               2. get the number from Guesser
                               3. get the number from all the three Players
                               4. Print th result of the game
                               5. End the game
