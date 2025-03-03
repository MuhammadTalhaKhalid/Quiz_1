q1# You are given a grid as shown in the figure below. You can determine the color and number of
each square from the grid. Write python program that inputs two numbers within the grid range.
Your program will determine if the two squares entered in this grid have the same color or not
and display the appropriate message, let’s call this ROUND1. You then again ask the user to
enter two numbers and determine if the two squares have the same color then display a victory
message but this time you will have to make sure that does not repeat the numbers entered in
2the first round. If he does, give him a warning and ask to enter values again (You can give a max
of 3 warnings, on the fourth warning you will end the program). Total rounds of this guessing
game will be 5. In each round you will make sure that the numbers entered do not match with
any of the previous victory numbers.
If the user wins at least 3 rounds of this guessing game, then it's a win.



q2:Write a program that displays the following menu: Welcome to Guessing games
1. Play Higher or Lower
2. Play paper - scissors - rock
3. Guess the numbers
4. Quit Enter your choice (1 - 4)
If the user enters 1, the program should generate two random numbers between 1 and 20 and
display the first number. It should then ask the user to enter either H or L for Higher or Lower.
The user wins if they entered H and the second number was higher than the first or when they
entered L and the second number was lower than the first.
If the user enters 2, the program should generate one random number between 1 and 3 with 1
corresponding to paper, 2 to scissors, and 3 to rock. The program should then ask the user to
enter P for paper, S for scissors, or R for rock. If the user guesses the correct corresponding
number, the program should then display who won the computer or the user. Scissors beat
paper, rock beats scissors, and paper beats rock.
Example: if the random number is 2 and the user enters the character S the program should
display, you won: Scissors beats paper. If a user enters any other character, the program should
display: you lose.
Finally, if the user enters 3, the program will generate three random numbers each between 0
and 9. The user should guess three numbers and the program should compare each of the
user's guess to the three generated random numbers and display an appropriate output based
on whether they got:
1. Any one matching
2. Two matching
3. Three matching, not in order
4. Three matching in exact order
5. No matches at all Input Validation:
Input Validation: Display an error message if the user enters a number outside the range of
through 4 when selecting an item from the menu. Do not accept characters other Than H or L
for Higher / Lower, other than P, S, and R for paper, scissors and rock , or a value outside the
range from 0 to 9 for guessing numbers. The user can play games in a repeated manner until the
user terminates the game by choice.



q3:Consider an integer array, the number of elements in which is determined by the user. The
elements are also taken as input from the user. Write a program to find those pairs of elements
that have the maximum and minimum difference among all element pairs.

use lists and tuples only
