🎯 Fermi Pico Bagel Game (Python Console Version)
Welcome to the classic number guessing game Fermi Pico Bagel, implemented in Python!
This simple and addictive game challenges your logical thinking as you try to guess a secret 3-digit number based on clues provided after each guess.
________________________________________
🎯 Objective
•	Guess the secret 3-digit number with no repeated digits.
•	After each guess, you'll receive clues:
  o	Fermi: Correct digit in the correct position.
  o	Pico: Correct digit but in the wrong position.
  o	Bagel: No digits match at all.
Keep guessing until you crack the code!
________________________________________
🧠 Game Rules
•	The secret number has no repeated digits.
•	Your guess must be exactly 3 digits long.
•	If your input length is wrong, you’ll be prompted again.
•	If your guess contains duplicate digits, you'll be notified of the duplicate.
•	After each valid guess:
  o	You get hints (Fermi, Pico, or Bagel) based on your guess.
•	Correct guess ends the game with a You Win!! message!
________________________________________
🎮 How to Play
1.	The game random selects a secret number (example: 123).
2.	You input your 3-digit guess.
3.	The game will:
    o	Check if your input is valid (length and no duplicates).
    o	Compare your guess with the secret number.
    o	Provide hints (Fermi, Pico, Bagel) based on matching digits.
4.	Repeat until you guess the correct number.
________________________________________
🛠️ Code Structure
•	Variables:
    o	original_number: The secret number to be guessed (currently hardcoded as '123').
    o	guess_number: The number input by the user each turn.
    o	output: List to store hints (Fermi, Pico).
•	Game Flow:
    o	An infinite loop (while True) keeps the game running.
    o	Input validation ensures only correct guesses proceed.
    o	Duplicates are checked and reported individually.
    o	Hints are generated:
      	Fermi for correct digit and position.
      	Pico for correct digit but wrong position.
      	Bagel if no digits match.
________________________________________
📚 What I Learned
While working on this project, I learned:
•	How to use input validation to ensure clean user inputs.
•	How to compare strings and indexes to generate smart hints.
•	Using sets and loops to detect duplicate digits in inputs.
•	Managing infinite loops efficiently with proper exit conditions.
•	Designing simple feedback mechanisms that enhance gameplay.
This project helped me understand input checking, string manipulation, and dynamic feedback generation in Python.
________________________________________
▶️ How to Run
1.	Make sure you have Python 3 installed.
2.	Copy or download the script (.py file).
3.	Open a terminal or command prompt.
4.	Navigate to the folder containing the script.
5.	Run the script using:
      python filename.py
6.	Start guessing and have fun!
________________________________________
🚀 Future Improvements
•	Allow configurable number lengths (4-digit, 5-digit challenges).
•	Add a limited number of attempts to increase difficulty.
•	Create a graphical interface version using Tkinter or Pygame.

________________________________________
❤️ Acknowledgements
Inspired by the classic logic puzzle game "Fermi, Pico, Bagels," popularized in math and computer science education.

