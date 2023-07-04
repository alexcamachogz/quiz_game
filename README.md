# Quiz Game

This repository contains a simple quiz game implemented in Python. The game allows users to answer a series of questions and provides them with a final score at the end.

## Prerequisites

Before running the code, make sure you have the following installed:
* Python 3.x

## Installation

To get started, follow the steps below:
1. Clone the repository:
```
  git cone https://github.com/your-username/quiz-game.git
```  
2. Change into the project directory:
```
  cd quiz-game
```

## Usage

To run the quiz game, execute the following command:
```
  python main.py
```

## Code Explanation

The code consists of several components:

1. `question_model.py`: This module defines the `Question` class, which represents a single question in the quiz. Each question has a question text and a correct answer.

2. `quiz_brain.py:` This module contains the `QuizBrain` class, responsible for managing the quiz. It keeps track of the question bank, the current question number, and the player's score. The `still_has_questions()` method checks if there are more questions to be asked, and the `next_question()` method displays the next question to the user.

3. `data.py`: This module provides the `question_data` list, which contains a collection of questions and their corresponding correct answers.

4. The main part of the code initializes an empty `question_bank` list and populates it by creating `Question` objects from the `question_data`. Then, it creates an instance of the `QuizBrain` class, passing the question bank to it.

5. The `while` loop continues until there are no more questions in the quiz. Within each iteration, the `next_question()` method is called to display the current question and prompt the user for an answer.

6. Finally, the user's final score is displayed along with a message indicating the completion of the quiz.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes.
5. Submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).


