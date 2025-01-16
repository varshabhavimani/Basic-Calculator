# Basic_Calculator

This is a simple calculator built using HTML, CSS, and JavaScript. It allows you to perform basic arithmetic operations like addition, subtraction, multiplication, and division. It also supports keyboard input for added convenience.

Features
Basic arithmetic operations: Addition, Subtraction, Multiplication, and Division.
Clear functionality (C button) to reset the display.
Results are calculated instantly when the equal (=) button is pressed.
Keyboard input is supported for numeric and operator keys, as well as Backspace and Escape for clearing the display.
Error handling: If an invalid expression is entered, the calculator will show an "Error" message briefly.
Installation
To run the calculator, simply open the index.html file in your web browser.

Clone or download the repository.
Open the index.html file in any modern web browser (Google Chrome, Firefox, etc.).
bash
Copy code
git clone https://github.com/varshabhavimani/Basic-Calculator.git
cd Basic-Calculator

# Open index.html in a browser.

Code Overview
HTML Structure
The HTML code contains a div with the class calculator which serves as the container for the calculator. Inside the calculator, there is an input field (<input>) that serves as the display, and several buttons for the digits, operators, and functions.

CSS Styling
The styles aim to make the calculator visually appealing and responsive:

The calculator has a white background with a slight box shadow.
Buttons have rounded corners and change color on hover.
The layout is responsive and uses CSS Grid to arrange the buttons in a neat grid.
JavaScript Functionality
Appending Values: When a button is clicked (or a corresponding key is pressed), the appendValue function is called, which adds the value to the display.

Clearing the Display: The clearDisplay function clears the current input on the display.

Calculating Result: The calculateResult function uses eval() to evaluate the expression from the display. If the result is not a valid number, an error message is shown.

Keyboard Support: The calculator also listens for keyboard events (keydown), allowing users to interact with the calculator using their keyboard. Valid keys include numbers, operators, and the Enter, Backspace, and Escape keys.

Keyboard Shortcuts
Numeric keys (0-9): Add corresponding number to the display.
Operator keys (+, -, \*, /): Add the operator to the display.
.: Adds a decimal point.
Backspace: Deletes the last character from the display.
Escape: Clears the display.
Enter: Calculates the result of the current expression.
License
This project is licensed under the MIT License - see the LICENSE file for details.
