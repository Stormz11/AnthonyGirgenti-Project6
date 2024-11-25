# Read me
The user will be taking a quiz on abbreviations for code names. Knowing what the real name for HTML can be important, so taking this quiz will help with remembering the real names. This quiz is also appealing to the eye, as well as a small challenge to answer the right name within 15 seconds. Don't worry the user can take the quiz as many times as they please. There will be five questions in this quiz, using HTML, CSS, and JS.
## File Structrue
- index.html: Main file for structure of the app
- css/style.css: The sytling for the app
- js/questions.js: Contaions the list of questions and answers, this will interact with quizApp.js
- js/quizApp.js: Has the main functions for the quiz
## Functions
-A start button
-Warning of the rules
-Five questions to answer
-The players score at the end
-A retake button or quit button
## Explanation of code
### HTML
The index.html contaions the layout of the quiz, with a start button, instructions, area for questions, and the results.
### CSS
- Layout: Stucture of the app, questions, and options.
- Buttons: Start the quiz, continue, and choose questions, as well as restart.
- The timer style is also made in css
### JS
- Shows instructions before quiz start
- Handles the timer
- Handles next question
- Uses an array to hold the questions to be called on
#### Example Code
- Timer: ```startTimer()``` will handle the code for the timer.
- Questions selected: ```optionSelected()``` Handles which question is selected and if they are right or wrong.
- Show Questions: ```showQuestions()``` gets the questions from the array that is in questions.js
