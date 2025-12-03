# Quiz_System 

```
╔══════════════════════════════════════════════════════╗
║               QUIZ SYSTEM — JAVA PROJECT             ║
╚══════════════════════════════════════════════════════╝
A simple console-based Quiz Management System written 
in Java. Users can create, edit, delete, view, start, 
and clear quiz questions. All data is stored using an 
ArrayList during runtime.
```

```
╔════════════════════════╗
║        FEATURES        ║
╚════════════════════════╝
• Create Questions
• Edit Questions
• Delete Questions
• View Created Quiz
• Start Quiz
• Clear All Questions
```

```
╔══════════════════════════════════════╗
║        HOW THE SYSTEM WORKS          ║
╚══════════════════════════════════════╝
1. QUESTION CLASS
   - Stores the question text
   - Stores 4 choices (a–d)
   - Stores the correct answer as a character

2. ARRAYLIST STORAGE
   List<Question> questions = new ArrayList<>();

3. MAIN MENU LOOP
   Uses while(true) to display the menu
   until the user chooses Exit.

4. INPUT VALIDATION
   - safeIntInput(): accepts numbers only
   - safeCharInput(): accepts a/b/c/d only
   - safeLine(): safe string input

5. START QUIZ FEATURE
   - Displays each question with choices
   - User inputs answer
   - Checks correctness
   - Lists wrong answers at the end
```

```
╔══════════════════════╗
║      HOW TO RUN      ║
╚══════════════════════╝
1. Install Java (JDK 17+ recommended)
2. Save file as: QuizSystem.java
3. Open terminal in the file directory
4. Compile:  javac QuizSystem.java
5. Run:      java QuizSystem
```

```
╔════════════════════════════╗
║      PROJECT STRUCTURE     ║
╚════════════════════════════╝
QuizSystem.java
│
├── Question class
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
```

```
╔════════════════════════════╗
║     SAMPLE PROGRAM FLOW    ║
╚════════════════════════════╝
Home
1. Create
2. Delete
3. Edit
4. View Created Quiz
5. Start Quiz
6. Clear
0. Exit
Choose option: 1
```

```
╔══════════════════════════════╗
║     PURPOSE OF THE PROJECT   ║
╚══════════════════════════════╝
• Demonstrates Object-Oriented Programming  
• Uses ArrayList for dynamic storage  
• Implements input validation  
• Shows CRUD operations in a console program  
• Beginner-friendly Java application 
```
