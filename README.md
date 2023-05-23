# The "Guess -A - Number" Game
C#

![Guess a Number - Game Picture](https://github.com/tsvetelinaVeselinova/GuessANumber/assets/133970524/4ca5794f-5e37-411b-bb5a-53fa40f1450c)

**Guess A Nubmer** is a game where a user is supposed to guess the number that the computer has randomly chosen (between a range of numbers, depending on the level).
Each time the user enters a number (if it is not equal to the computer's one) the computer will tell them whether it is lower or higher than the expected number.
The user wins the game when their number is the same as computer's number.
***The number of attempts is 5**, and there is an option to start the game again if the number is guessed.*

**INPUT and OUTPUT**

Choose number between **x** and **y**, then press *Enter*.

The computer selects a random number, then returns information whether the number is **less than, greater than, or equal to the selected number.

**MY SOLUTION**

*Description of how I solved the problem:*

I used: 

**Random Class and  Next() method to generate random number;**

**While loop to iterate, until the player guesses the computer's random number, or until the attempts count is <= 5.**

**Nested if-else statement to check  the player's input**

**LINK TO THE SOURCE CODE:**

[Source Code](GuessANumber.cs)

**SCREENSHOTS**

![You guessed it](https://github.com/tsvetelinaVeselinova/GuessANumber/assets/133970524/8f6fd943-bef1-4413-9bd8-5e455cf9a121)

![Too Low - Too High](https://github.com/tsvetelinaVeselinova/GuessANumber/assets/133970524/48ffa7ce-9285-482f-a6cb-2167f530981e)

![Invalid input](https://github.com/tsvetelinaVeselinova/GuessANumber/assets/133970524/36973e55-4436-4317-b8cc-92fbc3948d46)

![You have no more tries](https://github.com/tsvetelinaVeselinova/GuessANumber/assets/133970524/659514fe-1327-429a-8cd6-1cc6005f8ad3)

**LIVE DEMO**

*You can play the game directly in your Web browser here:* 
(https://replit.com/@tsvetelinaVesel/GuessANumber#Main.cs)

![image](https://github.com/tsvetelinaVeselinova/GuessANumber/assets/133970524/31c0ea94-b3c0-4f7e-a25a-a8e997aff3c6)








