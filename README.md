Interactive Quiz Game

A simple desktop quiz game written in Python using Pygame. It was developed as – Python Project at Lovely Professional University.

Author: Prashanth (B.Tech CSE, Section K2P25PU)

Features
Opens an 800 × 500 Pygame window titled "Interactive Quiz Game".
Asks 5 multiple-choice questions, one at a time, in a fixed order.
Each question has 4 answer options drawn as clickable blue buttons.
Shows "Correct Answer!" (green) or "Wrong Answer!" (red) after each selection.
Click anywhere to move to the next question.
Displays "QUIZ COMPLETED!" with the final score (for example, Your Score: 4/5) at the end.
Requirements
Python 3
Pygame 2.0 or newer
Installation
pip install pygame
How to Run

Open a terminal in the folder containing main.py and run:

python main.py

Run it as a normal Python script from the terminal. It is not designed to be run inside a Jupyter notebook.

How to Play
Read the question shown on the screen.
Click one of the four options.
Read the feedback, then click anywhere to continue.
After the fifth question, your final score is displayed.
Close the window to exit.
Project Structure
interactive-quiz-game/
├── main.py     # Complete source code (question list, draw_text() function, main game loop)
└── README.md   # Project description and instructions
How It Works
The questions are stored in a Python list of dictionaries. Each dictionary has a question, a list of four options and the correct answer.
The main while loop handles window and mouse events and redraws the screen.
When an option is clicked, its text is compared with the stored correct answer. The score increases if they match.
The final screen is shown when all questions have been answered.
Limitations
The question bank is small and stored in the source code.
Questions are always asked in the same order.
The score is not saved after the window is closed.
Possible Future Improvements
More questions and categories
Random question selection
Start screen with player name
Answer explanations, percentage score and replay option
Timer and leaderboard
