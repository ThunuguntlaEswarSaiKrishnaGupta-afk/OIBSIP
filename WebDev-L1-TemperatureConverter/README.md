# Temperature Converter

An interactive web tool to convert temperatures between Celsius, Fahrenheit, and Kelvin, built as Task 3 (Level 1) of the Web Development & Designing track for the Oasis Infobyte SIP internship.

## Features
- Input validation (rejects non-numeric input)
- Unit selector (Celsius, Fahrenheit, Kelvin)
- Converts and displays the value in all three units simultaneously
- Edge case handling: rejects temperatures below absolute zero (-273.15°C)
- Clean, centered, responsive UI

## Tech Stack
HTML5, CSS3, JavaScript (Vanilla)

## Installation

No installation or dependencies required — this is a pure HTML/CSS/JavaScript project that runs directly in any web browser.

1. Download or clone this folder (`WebDev-L1-TemperatureConverter`) to your computer
2. Make sure `index.html` and `style.css` are in the same folder
3. Open `index.html` by double-clicking it, or right-click → "Open with" → your browser

**Optional (for live-reload while editing):**
1. Install [VS Code](https://code.visualstudio.com/)
2. Install the "Live Server" extension (by Ritwick Dey) from the Extensions marketplace
3. Open this project folder in VS Code
4. Right-click `index.html` → "Open with Live Server"

## How to run
Open `index.html` in any browser, or use the VS Code "Live Server" extension for live preview.

## How to verify it works

Try these test cases to confirm the converter is functioning correctly:

| Test | Input | Expected Result |
|---|---|---|
| Valid conversion | Enter `45`, select Celsius, click Convert | Shows: Celsius: 45.00 °C, Fahrenheit: 113.00 °F, Kelvin: 318.15 K |
| Valid conversion | Enter `0`, select Celsius, click Convert | Shows: Celsius: 0.00 °C, Fahrenheit: 32.00 °F, Kelvin: 273.15 K |
| Invalid input | Enter `abc` (letters), click Convert | Shows error: "Please enter a valid number." |
| Empty input | Leave the field blank, click Convert | Shows error: "Please enter a valid number." |
| Absolute zero violation | Enter `-300`, select Celsius, click Convert | Shows error: "Temperature cannot be below absolute zero (-273.15°C)." |
| Unit switching | Enter `98.6`, select Fahrenheit, click Convert | Shows: Celsius: 37.00 °C, Fahrenheit: 98.60 °F, Kelvin: 310.15 K |

If all these cases produce the expected output, the converter is working correctly.
