# Online Quiz Application 🎯

## About the Project

The Online Quiz Application is a simple web-based project developed using HTML, CSS, JavaScript and PHP. It allows students to attend multiple-choice quizzes, select answers and view their scores immediately after submitting the quiz.

This project was developed as part of an online coding challenge to practise basic web development skills.

## Features

- Simple and user-friendly homepage.
- 10 multiple-choice questions.
- Four options for each question.
- Answer selection using radio buttons.
- JavaScript validation to check unanswered questions.
- Automatic score calculation using PHP.
- Displays total marks and percentage.
- Performance message based on the score.
- Responsive design for different screen sizes.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Creating the webpage structure |
| CSS | Styling and responsive design |
| JavaScript | Form validation |
| PHP | Processing answers and calculating scores |
| WAMP Server | Running the project locally |

## Project Structure

```text
onlinequiz/
│
├── index.html
├── quiz.php
├── result.php
├── style.css
├── script.js
└── README.md
```

## How to Run the Project

1. Install and open WAMP Server.
2. Wait until the WAMP icon turns green.
3. Open the WAMP `www` directory.
4. Copy the `onlinequiz` project folder into the `www` directory.
5. Open a web browser.
6. Enter the following URL:

```text
http://localhost/onlinequiz/
```

7. Click the **Start Quiz** button.
8. Answer all the questions.
9. Click **Submit Quiz** to view your result.

If your project is inside another folder, update the URL accordingly.

## How It Works

1. The homepage displays the quiz title and instructions.
2. The quiz page displays 10 multiple-choice questions.
3. Students select one answer for each question.
4. JavaScript checks whether all questions are answered.
5. PHP receives the submitted answers and compares them with the correct answers.
6. The final score and percentage are displayed on the result page.

## Learning Outcomes

Through this project, I learned:

- How to create webpages using HTML.
- How to design websites using CSS.
- How to use JavaScript for form validation.
- How to process form data using PHP.
- How to calculate quiz scores dynamically.
- How to run a PHP project using WAMP Server.
- How to organise and upload project files to GitHub.

## Future Improvements

- Add student registration and login.
- Add more quiz questions and categories.
- Store student scores in a MySQL database.
- Add a timer for each quiz.
- Display correct answers after submission.
- Create an admin panel to manage questions.

## Project Status

**Completed – Basic Version**

This project currently supports multiple-choice questions, answer validation and automatic score calculation. Database storage and user login can be added in future versions.

## Author

**Developed as part of an Online Quiz Application Coding Challenge.**

## License

This project is available for learning and educational purposes.
