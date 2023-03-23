Random Number Guessing Game

The Random Number Guessing Game is a Python program that generates a random number between 1 and 100 and prompts the user to guess the number. The program provides feedback to the user on whether their guess was too high or too low and keeps track of the number of guesses it took to find the correct answer.

Requirements

This program requires Python 3.x to be installed on your computer. You can download and install the latest version of Python from the official website: https://www.python.org/downloads/
How to Use
1.     Download or clone this repository to your local machine.
2.     
3.     Open a terminal or command prompt and navigate to the directory where you saved the program files.
4.     
5.     Run the program by typing python random_number_guessing_game.py in the terminal or command prompt.
6.     
7.     The program will generate a random number between 1 and 100, and prompt you to guess the number.
8.     
9.     Enter your guess and press Enter.
10.     
11.     The program will provide feedback on whether your guess was too high or too low, and prompt you to guess again.
12.     
13.     Keep guessing until you correctly guess the number.
14.     
15.     After you guess the correct number, the program will display the number of guesses it took you to find the answer.
16.     
Additional Features

1.     You can quit the game at any time by entering "q" instead of a number.
2.     
3.     The program includes a timer to display the time taken to play the game.

Explanation:

1.     We start by importing the necessary libraries, random and time.
2.     
3.     The generate_number() function uses random.randint() to generate a random number between 1 and 100.
4.     
5.     The play_game() function is where the actual game logic is implemented. It starts by generating a random number using generate_number(), and initializing the guesses counter to 0.
6.     
7.     The while loop runs indefinitely until the user correctly guesses the number or chooses to quit the game.
8.     
9.     Within the loop, the user is prompted to enter a guess using input(). If the user enters "q", the game is quit using break.
10.     
11.     The user's input is converted to an integer using int(), and we handle any ValueError exceptions using a try-except block.
12.     
13.     If the user's guess is incorrect, we provide feedback by printing a message that the guess was too high or too low.
14.     
15.     The guesses counter is incremented for each guess.
16.     
17.     If the user correctly guesses the number, we print a congratulatory message and break out of the loop.
18.     
19.   After the game is finished, we calculate the time taken to play the game by subtracting the start_time from the end_time.
