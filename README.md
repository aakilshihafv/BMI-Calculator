# BMI Calculator

This project is a simple BMI (Body Mass Index) calculator application built with React. It allows users to input their height and weight to calculate their BMI and determine their weight status.

## Features

- Input height in centimeters and weight in kilograms
- Calculate BMI and display the result
- Show weight status based on the calculated BMI
- Clear input fields and results

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/aakilshihafv/bmi-calculator
    cd bmi-calculator
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm start
    ```

## Usage

- Enter your height in centimeters in the height input field.
- Enter your weight in kilograms in the weight input field.
- Click the "Calculate BMI" button to see your BMI and weight status.
- Click the "Clear" button to reset the input fields and results.

## File Structure

- `App.js`: Main application component that handles user input, calculates BMI, and displays the results.
- `App.css`: Styles for the application.

## React Hooks Used

- `useState`: Used to create state variables `height`, `weight`, `bmi`, `bmiStatus`, and `errorMessage`.

## Screenshot

![BMI Calculator](https://github.com/aakilshihafv/bmi-calculator/blob/main/image/bmi-design.png)

## Contributing

Feel free to fork this repository, make enhancements, and submit pull requests. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
