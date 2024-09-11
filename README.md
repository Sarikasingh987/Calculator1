# Calculator1
A basic calculator using HTML, CSS, and JavaScript.
**Features**
1= Addition, subtraction, multiplication, division
2= Clear and reset functions
3= Responsive design
**Project Files**
index.html – Structure of the calculator
styles.css – Styling
script.js – Functionality
**Calculator Buttons**
Clear Button (CLR)
Function: Clears the entire input display.
Usage: Click the CLR button to reset the calculator and start a new calculation.
Delete Button (DE)
Function: Deletes the last character entered.
Usage: Click the DE button to remove the last digit or operator from the current input.
**HTML:** This defines the structure of the calculator. It includes:
An input field (<input>) where the result and entered values are displayed.
A series of buttons (<button>) representing numbers, operators, and a clear (CLR) and equals (=) button. Each button has an onclick event that triggers specific JavaScript functions when pressed.
**CSS**: This styles the calculator:
The calculator is centered on the page.
Buttons are given a uniform size and spacing, and the input field is styled for proper display.
**JavaScript:** This controls the calculator's functionality:
appendToDisplay(): Adds the number or operator clicked to the display.
clearDisplay(): Clears the display when the 'CLR' button is pressed.
calculate(): Evaluates the mathematical expression and shows the result when '=' is pressed using JavaScript's eval() function.






