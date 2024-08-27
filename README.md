# Interactive Quiz App

This is a simple interactive quiz app built using HTML, CSS, and JavaScript. It allows users to test their knowledge with multiple-choice questions from different categories.

## Features

### HTML

-   **Semantic HTML5 tags:**  `header`, `div`, `h2`, `label`, `input[type="radio"]`, `button`
-   **Clear structure:**  The HTML is structured with divs for the header, question container, options container, and result display.
-   **Form elements:**  A form is used to get the user's name before starting the quiz.

### CSS

-   **External Stylesheet (style.css):**  Provides clean separation of content and styling.
-   **Centering techniques:**  Flexbox is used for centering content both vertically and horizontally.
-   **Responsive design:**  Media queries are used to ensure the quiz looks good on different screen sizes.
-   **Styling for different states:**  Hover effects are added to buttons for better user interaction.

### JavaScript (script.js)

-   **DOM Manipulation:**  The script uses JavaScript to manipulate the DOM, dynamically changing the content of the page.
-   **Event Handling:**  Event listeners are used to handle user interactions, such as clicking buttons and selecting options.
-   **Timers:**  A timer is implemented to limit the time for each question.
-   **Conditional Logic:**  The script uses conditional statements to determine the correctness of answers and display appropriate feedback.
-   **Data Structures:**  Questions and answers are stored in a JavaScript object, allowing for easy management and retrieval of quiz data.
-   **Audio Feedback:**  Sound effects are included for correct and incorrect answers.

## Functionality

1.  **Welcome Screen:**  The user is greeted with a welcome screen and a form to enter their name.
2.  **Category Selection:**  Users can select a quiz category from a variety of options (e.g., Tech, GK, English, Sports).
3.  **Age Group Selection:**  Within each category, there are different question sets for Children, Teens, and Adults.
4.  **Quiz Questions:**  The app presents multiple-choice questions one at a time.
5.  **Timer:**  Each question has a time limit. If the timer runs out, the quiz moves to the next question.
6.  **Feedback:**  After each question, the user receives immediate feedback on whether their answer was correct or incorrect.
7.  **Score:**  The user's score is displayed throughout the quiz.
8.  **End of Quiz:**  The quiz ends when all questions are answered or the time runs out. A message is displayed based on the user's score.
9.  **Restart:**  The user can restart the quiz at any time to try again.

## How to Run

1.  Download or clone the repository to your local machine.
2.  Open  `index.html`  in your web browser.
