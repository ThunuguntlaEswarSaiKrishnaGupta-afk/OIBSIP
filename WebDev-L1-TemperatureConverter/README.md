# Temperature Converter

## Objective
To build an interactive web tool that converts a temperature between Celsius, Fahrenheit and Kelvin, with input validation and clear error messages, using HTML5, CSS3 and vanilla JavaScript.

## Features
- Numeric input field that rejects non-numeric or empty input with an error message
- Unit selector (Celsius, Fahrenheit, Kelvin)
- Convert button that triggers the calculation
- Results shown for all three units at the same time, with unit labels
- Absolute zero check: values below -273.15°C are rejected with a friendly message
- Clean, centred, responsive layout

## Tools & Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla)
- Visual Studio Code with the Live Server extension
- Git and GitHub

## Steps Performed
1. Designed the layout: a centred card with an input box, a unit dropdown, a Convert button and a results area.
2. Wrote the HTML structure in `index.html`.
3. Styled the page in `style.css` with a centred card, clear labels and a mobile-friendly layout.
4. Wrote the JavaScript logic: validate the input, convert the value to Celsius first, check for absolute zero, then calculate Fahrenheit and Kelvin from it.
5. Displayed the results rounded to 2 decimal places.
6. Tested valid input, invalid input, empty input and values below absolute zero.
7. Uploaded the project and screenshots to GitHub.

## Outcome
A working temperature converter that gives correct results in all three units and handles wrong input safely with clear messages. Screenshots are included in this folder.

## Installation
No installation or dependencies are needed. This is a plain HTML, CSS and JavaScript project.
1. Download this folder (`WebDev-L1-TemperatureConverter`) to your computer.
2. Keep `index.html` and `style.css` in the same folder.
3. Open `index.html` in any browser. Optionally, use the Live Server extension in VS Code.

## How to Verify It Works

| Test | Input | Expected Result |
|---|---|---|
| Valid conversion | `45`, Celsius | 45.00 °C, 113.00 °F, 318.15 K |
| Zero | `0`, Celsius | 0.00 °C, 32.00 °F, 273.15 K |
| Unit switching | `98.6`, Fahrenheit | 37.00 °C, 98.60 °F, 310.15 K |
| Invalid input | `abc` | "Please enter a valid number." |
| Empty input | (blank) | "Please enter a valid number." |
| Below absolute zero | `-300`, Celsius | "Temperature cannot be below absolute zero (-273.15°C)." |
