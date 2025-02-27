# Quiz Game

This is a Python-based Quiz Game inspired by the "Kaun Banega Crorepati" (KBC) format. Players are presented with multiple-choice questions and must select the correct answer to progress.

## Features
- **Multiple-choice questions**: Each question comes with four possible answers.
- **Score tracking**: The game keeps track of the player's score based on correct answers.
- **Player data storage**: Player information and scores are stored for future reference.

## Code Details

### Key Components
- **CSV Data Storage**: Questions and player scores are stored in CSV files for persistence.
- **Python-based Logic**: The game logic is implemented using Python.
- **Command-line Interface**: Users interact with the game through the terminal.

### Code Structure
```
Quiz_Game/
│── main.py         # Main application file
│── KBC.py          # Game logic and functions
│── Quiz.py         # Question handling and validation
│── Quiz.csv        # CSV file containing quiz questions and answers
│── Players.csv     # CSV file storing player information and scores
│── README.md       # Project documentation
```

## Installation

### Requirements
- Python 3.x installed on your system.

### Setup Steps:
1. Clone or download this repository:
   ```bash
   git clone https://github.com/Vidish3442/Quiz_Game.git
   cd Quiz_Game
   ```
2. Run the game:
   ```bash
   python main.py
   ```

## Game Walkthrough

### 1. Starting the Game
- Run `main.py` to start the quiz.
- Follow on-screen instructions to proceed.

### 2. Answering Questions
- Each question presents four choices.
- Type the correct option number and press Enter.

### 3. Scoring System
- Each correct answer earns points.
- The game displays your score at the end.

### 4. Storing Player Scores
- Scores are saved in `Players.csv`.
- Previous high scores can be accessed and compared.

## Future Scope
- Implement a graphical user interface (GUI) for better user experience.
- Add more diverse question categories.
- Include lifelines or hints similar to the KBC format.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
