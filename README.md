# The "Guess -A - Number" Game
C#

![Guess a Number - Game Picture](https://github.com/tsvetelinaVeselinova/GuessANumber/assets/133970524/4ca5794f-5e37-411b-bb5a-53fa40f1450c)

**Guess A Nubmer** is a game where a user is supposed to guess the number that the computer has randomly chosen (between a range of numbers, depending on the level).
Each time the user enters a number (if it is not equal to the computer's one) the computer will tell them whether it is lower or higher than the expected number.
The user wins the game when their number is the same as computer's number.
***The number of attempts is 5**, and there is an option to start the game again if the number is guessed.*

**INPUT and OUTPUT**
Choose number between **x** and **y**q then press *Enter*.

The computer selects a random number, then returns information whether the number is **less than, greater than, or equal to the selected number

**MY SOLUTION**
*Description of how I solved the problem:*
I used: 
**Random Class and  Next() method to generate random number;**
**While loop to o iterate, until the player guesses the computer's random number, or until the attempts count is <= 5.**
**Nested if-else statement to check  the player's input**

**LINK TO THE SOURCE CODE:**
[Source Code](GuessANumber.cs)






