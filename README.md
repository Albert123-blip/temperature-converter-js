# Temperature Conversion Program

A simple web app that converts temperatures between Celsius and Fahrenheit. Enter a value, choose a unit, and get the converted result instantly.

## How to Use

1. Type a temperature into the text box.
2. Select the unit you want to convert **to**: Fahrenheit or Celsius.
3. Click the convert button.
4. The result appears on the page, rounded to one decimal place.

## Features

- Convert Celsius to Fahrenheit
- Convert Fahrenheit to Celsius
- Results rounded to 1 decimal place
- Prompts you to select a unit if none is chosen

## Formulas Used

| Conversion | Formula |
|---|---|
| Celsius to Fahrenheit | `°F = °C × 9/5 + 32` |
| Fahrenheit to Celsius | `°C = (°F − 32) × 5/9` |

## Getting Started

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Albert123-blip/temperature-converter-js.git
   ```
2. Open the project folder:
   ```bash
   cd temperature-converter-js
   ```
3. Open `index.html` in your browser, or use the **Live Server** extension in VS Code.

## Project Structure

```
├── index.html   # Page structure
├── index.js     # Conversion logic
├── style.css    # Styling
└── README.md    # Project documentation
```

## Built With

- HTML
- CSS
- JavaScript

## Ideas for Improvement

- Add input validation for empty or non-numeric values
- Add Kelvin as a third unit
- Convert automatically as the user types
- Add a clear/reset button
- Improve the layout for mobile screens

## Author

**Albert Morka**
GitHub: [@Albert123-blip](https://github.com/Albert123-blip)
