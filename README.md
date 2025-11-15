In this project, I developed a graphical calculator application in Java using Swing, a toolkit for building desktop-based GUI applications. The calculator performs basic arithmetic operations including addition, subtraction, multiplication, and division, providing a functional and interactive user experience.

The user interface is created using Swing components such as JFrame, JButton, and JTextField. Buttons for numbers (0–9), operations (+, −, ×, ÷), equals (=), and clear (C) are organized in a grid layout, giving the application a clean and intuitive design.

Event handling is implemented using the ActionListener interface. Each button click triggers an event captured by the actionPerformed method. Number buttons append digits to the current input, operator buttons store the first operand and the chosen operation, and the equals button executes the calculation and displays the result. The clear button resets the input.

The calculator maintains its state using variables to track the first number, the operator, and the second number. After each calculation, the result is updated in the display, allowing for continuous operations.

This project demonstrates object-oriented programming principles, event-driven programming, and GUI design. Building this calculator enhanced my skills in Java programming, user interface development, and handling dynamic user input, providing a strong foundation for more advanced desktop applications.
