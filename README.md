# BMI Calculator

A simple and user-friendly Body Mass Index (BMI) Calculator built with HTML, CSS, and JavaScript. This tool helps users calculate their BMI based on their height and weight and provides a BMI weight guide for interpretation.

## Features

- **User Input:** Allows users to input height (in cm) and weight (in kg).
- **Dynamic Calculation:** Calculates BMI dynamically upon form submission.
- **BMI Guide:** Displays a BMI weight guide for easy understanding.
- **Responsive Design:** Works well on different screen sizes and devices.

## Technologies Used

- **HTML**: For structuring the page.
- **CSS**: For styling and making the interface visually appealing.
- **JavaScript**: For handling user interactions and BMI calculations.

## How to Use

1. Open the BMI Calculator in your web browser.
2. Enter your height in centimeters and weight in kilograms.
3. Click the "Calculate" button.
4. View your calculated BMI and compare it to the BMI weight guide displayed below.


## Code Overview

### **HTML**
The `HTML` file contains:
- A form for user input.
- Sections for displaying results and a BMI weight guide.

### **CSS**
The `CSS` file includes:
- Styling for the container, buttons, and form elements.
- Responsive design for different screen sizes.

### **JavaScript**
The `JavaScript` code:
- Captures user inputs for height and weight.
- Validates the inputs to ensure valid numbers.
- Calculates BMI using the formula:
  \[
  \text{BMI} = \frac{\text{weight (kg)}}{\left(\text{height (cm)}\right)^2} \times 10,000
  \]
- Displays the calculated BMI or an error message for invalid inputs.
