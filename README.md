# Quizzler

## Introduction
Quizzler is a Python-based quiz application that showcases the integration of external APIs, object-oriented programming principles, and graphical user interfaces (GUI). This project aims to provide a comprehensive understanding of the code and its functionality for both technical and non-technical readers.

## Objectives
1. **Educational Engagement:** Create an interactive quiz application to engage users in a fun and educational manner.
2. **API Integration:** Demonstrate the integration of external APIs for data retrieval and enrichment of the quiz content.
3. **Object-Oriented Programming:** Showcase the use of object-oriented programming principles for code organization and modularity.
4. **User Interface Design:** Develop an intuitive graphical user interface (GUI) to enhance user experience and accessibility.
5. **High Score Tracking:** Implement a high score system to motivate users and provide a sense of achievement.
6. **Real-World Application:** Offer a practical example of how Python can be used to build an interactive and informative software application.

## Target Audience
Quizzler is designed for individuals of various age groups and educational backgrounds who seek an enjoyable and informative quiz experience. It is particularly well-suited for those interested in testing their knowledge and learning new facts in a user-friendly and interactive way.

## Libraries Used
The project utilizes several key libraries and modules:
- **requests:** For sending HTTP requests to the Open Trivia Database API and retrieving quiz questions.
- **tkinter:** For creating the graphical user interface (GUI) of the quiz application.
- **html:** For decoding HTML-encoded characters in the retrieved quiz questions.
- **json:** For parsing and handling JSON data, essential for processing the API response.

## Class Definitions
1. **Question Class (question_model module):** Responsible for storing individual quiz questions, including attributes for the question text and correct answer.
2. **QuizBrain Class (quiz_brain module):** Manages the core logic of the quiz, including tracking the user's score and the current question, and providing methods for checking answers.
3. **QuizInterface Class (ui module):** Defines the graphical user interface (GUI) for the quiz application, handling the display of questions and user interactions.

## Code Structure
The code for the quiz application is organized into several modules:
- **Main Program:** Orchestrates various modules to create the quiz application, initializes classes, and manages user interaction.
- **API Integration (requests module):** Fetches quiz questions from the Open Trivia Database API.
- **Question Model (question_model module):** Defines the `Question` class for storing question data.
- **Quiz Brain (quiz_brain module):** Implements the `QuizBrain` class to manage quiz logic.
- **User Interface (ui module):** Creates the GUI using tkinter library.
- **High Score Management:** Maintains and updates user's high scores.
- **Data Handling:** Deals with data retrieval, storage, and manipulation.

## Quiz Flow
1. **Initialization:** Initializes classes, retrieves high score, and sets up the user interface.
2. **Question Retrieval:** Fetches quiz questions from the API and converts them into objects.
3. **Question Presentation:** Displays the first question and initializes the user's score.
4. **User Interaction:** Allows the user to answer questions and provides visual feedback.
5. **Scoring:** Updates and displays the user's score.
6. **Next Question:** Proceeds to the next question if available.
7. **End of Quiz:** Displays end message and disables further interactions.
8. **High Score Update:** Updates and saves high score if surpassed.
9. **User Restart or Exit:** Allows the user to start a new quiz session or exit the application.
