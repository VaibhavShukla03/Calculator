#Basic Calculator
This is a basic calculator implemented in JavaScript. The calculator has buttons for numbers, operators, equals, AC (all clear), and DEL (delete).

# How it works
The calculator uses an event listener to capture button clicks. When a button is clicked, the event listener function is executed. The function checks the innerHTML property of the clicked button to determine what action to take.

Equals (=) Button: Evaluates the current input string using eval() and updates the input field with the result.
AC (All Clear) Button: Resets the input string to an empty string and updates the input field.
DEL (Delete) Button: Removes the last character from the input string and updates the input field.
Other Buttons: Appends the button's innerHTML to the input string and updates the input field.
