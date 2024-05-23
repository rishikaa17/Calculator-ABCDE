# Calculator App

This is a React-based scientific calculator application. It supports various mathematical operations including trigonometric functions, logarithms, exponentiation, and more. Additionally, it features a light and dark theme toggle and an animated confetti explosion when the input includes both "4" and "3".

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, division.
- Scientific functions: trigonometric (sin, cos, tan, sinh, cosh, tanh), logarithms (ln, log10), square root, cube root, factorial, etc.
- Theme toggle: switch between light and dark themes.
- Confetti explosion animation when the input includes both "4" and "3".
- Keypress support for "Enter" key to calculate the result.
- Input handling for special constants like π (Pi) and e (Euler's number).

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/calculator-app.git
    ```

2. Navigate to the project directory
    ```
    cd calculator-app
    ```
3. Install the dependencies
    ```
    npm install
    ```
4. Start the application
    ```
    npm start
    ```
5. Open your browser and go to http://localhost:3000 to see the app in action
    
## Usage 
- Use the buttons on the calculator interface to input your calculations.
- Use the +/- button to toggle the sign of the current input.
- Use the C button to clear the input and output.
- Use the = button to calculate the result of the expression.
- Click the theme toggle button to switch
## Components
- App.js: The main component that holds the state and logic of the calculator.
- Buttons.js: A component that renders all the calculator buttons.
- Display.js: A component that displays the current input and output.
- ToggleButton.js: A component that toggles the theme between light and dark.
- ConfettiExplosion: A third-party component used to display confetti animation.
