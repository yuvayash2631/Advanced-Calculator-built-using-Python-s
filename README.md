
## Advanced Calculator built using Python

## Objective

This project is an Advanced Calculator built using Python's Tkinter library for the graphical user interface (GUI), 
with functionalities for basic arithmetic operations, 
as well as advanced features such as square root, exponentiation, and percentage calculations.

![image](https://github.com/user-attachments/assets/3754e466-c299-4d3d-816d-a3749aac9a2b)


## Key Features:

 1.	Basic Operations:

o	Addition, Subtraction, Multiplication, and Division: These basic arithmetic operations are supported by the calculator and can be performed using the corresponding buttons.

 2.	Square Root Function:

o	The √ button allows the user to calculate the square root of any given number. It uses the Python math.sqrt() function to perform this operation.

 3.	Exponentiation (Power):

o	The ^ button handles exponentiation. The user can input a base and an exponent separated by the ^ symbol (e.g., 2^3), and the calculator will compute the result using Python's pow() function.

 4.	Percentage Calculation:

o	The % button allows the user to calculate the percentage of a number (e.g., 50% of a number). This is handled by dividing the number by 100.

 5.	Error Handling:

o	The calculator uses try-except blocks to handle errors, ensuring that when an invalid operation is performed (like dividing by zero or invalid input), it doesn't crash. Instead, it displays "Error" on the screen.

 6.	Clear Functionality:

o	The C button clears the entry field, allowing the user to start fresh.

 7.	GUI Elements:

o	Entry Box: A text field where the user can see the input and the result. It’s styled with a white background, black text, and a solid border.
o	Buttons: All calculator buttons (numbers, operators, special functions) are styled with a light gray background and black text. The buttons are arranged in a grid layout for easy access.
o	Highlighted "=" Button: The = button is given a highlighted color to distinguish it from the rest, indicating its significance in evaluating expressions.

## Working of the Code:

•	Pressing Numbers: When the user clicks a number button (e.g., 7), the number is appended to the existing text in the entry box.
•	Evaluating Expressions: When the user presses the = button, the code evaluates the mathematical expression typed in the entry box using Python's eval() function.
•	If the expression is valid, the result is displayed; otherwise, an error message is shown.

•	Advanced Operations:

o	The √ button calculates the square root of the number inputted in the entry box.
o	The ^ button computes the exponentiation (power) when two numbers are entered separated by the ^ symbol.
o	The % button calculates the percentage value of the entered number.

Layout:

•	Grid System: The calculator buttons are laid out in a 6x4 grid (6 rows and 4 columns) using Tkinter's grid layout manager. This grid system allows for an organized structure where buttons are properly aligned.

## Error Handling:

•	The calculator includes error handling for:
o	Invalid operations (like dividing by zero or entering non-numeric input).
o	Incorrect input for advanced functions such as the square root and power functions.
o	Any errors encountered will display "Error" on the screen, ensuring the program doesn't crash.

# Appearance and Design:

•	The GUI is clean and simple, with a modern color scheme featuring a dark background and contrasting button colors.
•	The calculator buttons are large and easy to press, making it user-friendly.

# How to Use:

1.	Basic Operations: Click the number buttons and use +, -, *, / for basic calculations.
2.	Advanced Functions:
o	Press the √ button for square roots.
o	Use ^ for exponentiation (e.g., 2^3 to calculate 2 raised to the power of 3).
o	Press % to calculate percentages (e.g., 50%).

3.	Evaluate Expressions: Press = to compute the result of the entered expression.
4.	Clear Input: Press C to clear the input field.

## Example:

•	Input: 5 + 3
o	Click 5, +, 3, =
o	Output: 8
•	Input: 9^2
o	Click 9, ^, 2, =
o	Output: 81
## Conclusion:

This project serves as an intuitive and user-friendly Advanced Calculator with basic and advanced mathematical capabilities, suitable for quick calculations. 
By leveraging Tkinter for the graphical interface, it provides a simple yet efficient way to perform mathematical operations, making it a good example of GUI-based applications in Python.
