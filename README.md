# Stone_Paper_Scissor
A classic implementation of the Stone, Paper, Scissors game (also known as Rock, Paper, Scissors) built using C++. This project focuses on clean logic, input validation, and random choice generation.

🚀 Features
Interactive Gameplay: User vs Computer.

Input Validation: Ensures the user enters valid choices.

Score Tracking: Keeps track of wins, losses, and draws across multiple rounds.

Randomization: Uses srand and rand for unpredictable computer moves.

Modular Code: Clean functions for game logic, UI, and results.
🛠️ How to Run
To run this game on your local machine, follow these steps:

Clone the repository:

Bash

git clone https://github.com/YourUsername/StonePaperScissors.git
Navigate to the project directory:

Bash

cd StonePaperScissors
Compile the code: Using g++ (MinGW or Linux):

Bash

g++ main.cpp -o StonePaperScissors
Run the application:

Bash

./StonePaperScissors
🎮 How to Play
Choose how many rounds you want to play.

Enter your choice:

1 for Stone

2 for Paper

3 for Scissors

The computer will make its move.

The winner of the round is announced based on the rules:

Stone beats Scissors.

Paper beats Stone.

Scissors beat Paper.

At the end of all rounds, the final winner is displayed.

💻 Code Structure
The project follows a structured approach:

Enums: To represent choices (Stone, Paper, Scissors) and winners.

Functions: Modular functions for getting user input, generating computer choices, and calculating results.

Loops: To handle the multiple rounds of gameplay.
