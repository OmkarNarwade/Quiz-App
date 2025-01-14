# Quiz App

# Overview
 - This Quiz App is built using Flutter and provides an engaging way to test users' knowledge through multiple-choice questions. Users can navigate through questions, select answers, and see their results at the end of the quiz.

# Features
 - Multiple Choice Questions: Each question has four options, and only one correct answer.
 - Dynamic UI: Changes button color based on the selected answer and correctness.
 - Progress Tracker: Displays the current question number out of the total.
 - Final Score: Summary of correct answers after the quiz is completed.
 - Reset Option: Allows users to restart the quiz.

# Technologies Used
 - Flutter: Framework for building the app.
 - Dart: Programming language for app logic and UI.

# Screenshots
- Home Screen with Questions :- screenshots\Home Screen with Questions.PNG
- Answer Selection :- 1. screenshots\Answer Selection.png
                      2. screenshots\Answer Selection2.png
- Quiz Completion Summary :- screenshots\Quiz Completion Summary.png

# How to Run the Project
 - Follow these steps to set up and run the project locally:
 - Clone the Repository:
   - git clone https://github.com/OmkarNarwade/Quiz-App.git
 - Navigate to the Project Directory:
   - cd quiz_app2
 - Install Dependencies:
   - flutter pub get
 - Run the App:
   - flutter run

# Folder Structure
- The project is organized as follows:
  
- lib/
 - │
 - ├── main.dart                  # Entry point of the application
 - ├── models/                    # Contains model classes
 - │   └── single_question_format.dart # Question format definition
 - ├── widgets/                   # Reusable UI widgets
 - └── screens/                   # Screens for question and result display

