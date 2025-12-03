📘 Quiz System (Java Console Application)

A simple quiz creator and quiz taker using Java and Object-Oriented Programming.
════════════════════════════════════════════════════════════════════════════════════════════════════════════
📌 Overview

This project is a console-based Quiz Management System written in Java.
It allows the user to:

Create questions

Edit questions

Delete questions

View all created questions

Start the quiz

Clear all questions

All quiz data is stored temporarily using an ArrayList<Question>.
════════════════════════════════════════════════════════════════════════════════════════════════════════════
🛠 Features
✔ Create Questions

Users can add a question, four choices (a–d), and the correct answer.

✔ Edit Questions

Modify an existing question, its choices, and its correct answer.

✔ Delete Questions

Remove a question by selecting its number from a list.

✔ View Created Quiz

Displays all questions and their possible choices.

✔ Start Quiz

The user answers each question.
The system will show which question numbers were answered wrongly.

✔ Clear Quiz

Deletes all stored questions at once.
════════════════════════════════════════════════════════════════════════════════════════════════════════════
🧱 How the System Works
1. Question Class

Each quiz item is represented by:

The question text

An array of 4 choices

The correct answer (a/b/c/d)

2. Storing Data

All questions are stored inside:

List<Question> questions = new ArrayList<>();


This allows dynamic adding and removing.

3. Main Menu

The application uses a continuous loop:

while (true) { ... }


This keeps showing the menu until the user chooses Exit.

4. Input Validation

The program uses methods such as:

safeIntInput() → ensures the user enters a number

safeCharInput() → ensures input is only a/b/c/d

safeLine() → safely reads text input

These avoid errors and crashes.
════════════════════════════════════════════════════════════════════════════════════════════════════════════
🚀 How to Run

Install Java (JDK 17 or later recommended).

Copy the code into a file named QuizSystem.java.

Open a terminal in the file's directory.

Compile:

javac QuizSystem.java


Run:

java QuizSystem
════════════════════════════════════════════════════════════════════════════════════════════════════════════
🔍 System Flow (Step-by-Step)
Home Menu
1. Create
2. Delete
3. Edit
4. View Created Quiz
5. Start Quiz
6. Clear
0. Exit


User chooses an option and the system performs the corresponding action.
════════════════════════════════════════════════════════════════════════════════════════════════════════════
📁 Code Structure
QuizSystem.java
│
├── class Question
│   └── Holds question, choices, and correct answer
│
├── createQuestion()
├── deleteQuestion()
├── editQuestion()
├── viewQuiz()
├── startQuiz()
├── clearQuestions()
├── listQuestions()
│
├── safeIntInput()
├── safeCharInput()
├── safeLine()
│
└── clearScreen()
════════════════════════════════════════════════════════════════════════════════════════════════════════════
🧪 Example Interaction
Home
1. Create
2. Delete
3. Edit
4. View Created Quiz
5. Start Quiz
6. Clear
0. Exit
Choose option: 1

(Create)
Input question: What is 2 + 2?
input answer a: 3
input answer b: 4
input answer c: 5
input answer d: 6
Correct answer (a/b/c/d): b
Add another question (1) or go back home (0): 0
════════════════════════════════════════════════════════════════════════════════════════════════════════════
📜 Purpose of the Project

This program demonstrates:

Use of Object-Oriented Programming

Handling arrays, ArrayLists, and loops

Implementing input validation

Constructing a console menu system

Applying clean code structure

It is a simple but complete example of a CRUD-based Java application.
════════════════════════════════════════════════════════════════════════════════════════════════════════════
👥 Developers

Add your names here.
