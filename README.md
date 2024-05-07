Here's a breakdown of its functionality:

- **State Management**: It uses the `useState` hook to manage the state of the calculator, including the current formula, result, and decimal flag.
  
- **Input Handling**: The `handleClick` function updates the calculator's state based on the button clicked. It prevents multiple decimals and consecutive operators, except for the minus sign.

- **Calculation Logic**: The `calculate` function evaluates the mathematical expression using the `eval` function and updates the result and formula states.

- **UI Components**: The calculator's UI is composed of buttons for digits, operators, and a clear button, all arranged in a grid layout.

- **Styling**: The application uses a CSS file for styling, referenced in the import statement.

This code provides a functional calculator that can handle basic arithmetic operations and display the results to the user.
